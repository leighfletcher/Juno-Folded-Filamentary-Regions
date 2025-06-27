# Microwave Radiometer (MWR)

Raw MWR data are available via the [Planetary Data System](https://pds-atmospheres.nmsu.edu/PDS/data/jnomwr_1100/), but we displayed processed versions of the data in Fletcher et al. (2025).  This sub-directory contains the following data:

* `mwr_global_PJ3-40.zip`: Zip directory contains `.png` files used to assemble the global views of MWR data in the appendices.  These are shown for both unfiltered (i.e., no correction for synchrotron and auroral contamination) and filtered (with synchotron/auroras filtered out), and for both polar equidistant projections, and Mollweide projections.

* `coefficients.h5`:  HDF file containing the perijove-averaged model for the latitude-dependent brightness temperature and limb darkening.  This file contains the latitude and emission angle grids for the zonally-averaged brightness temperatures (`ATM-TB-MODEL`) and the correction needed to convert off-nadir brightness to nadir brightness (`ATM-CORRECTION`), as shown in Fig. 8.  It also contains the latitude-dependent coefficients c0, c1, and c2 for each channel, as shown in Fig. 7.

* 
