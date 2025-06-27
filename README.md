# Juno Folded Filamentary Regions

Repository of supplementary information for Fletcher et al. (2025):  
*Structure and Energetics of Jupiter's High-Latitude Storms:  Folded Filamentary Regions Revealed by Juno*

DOI for this repository: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15755741.svg)](https://doi.org/10.5281/zenodo.15755741)

Raw data from Juno's instruments are available via the [Planetary Data System](https://pds-atmospheres.nmsu.edu/data_and_services/atmospheres_data/JUNO/juno.html), but we have processed these observations (as described in the main text) in order to study the meteorology of Jupiter's high latitudes.  The processed versions of the data, used to generate the figures in Fletcher et al. (2025), are available in the sub-directories provided here.  Each sub-directory contains a `README` file describing the data format.

* `junocam`: Polar and orthographic projections of JunoCam observations (PJ3-40) are used in Figs. 5, 6, 9, 10 and 17.  The raw `.tif` files on an equidistant polar projection are available here.

* `jiram`:  North and south polar projections of JIRAM 5-micron observations (PJ4-40) are used in Figs. 4, 5, 6, and Appendix A.  Cylindrically-mapped `.fits` files containing the calibrated data are provided for both the northern and southern hemispheres.

* `mwr`:  Microwave radiometer directory contains `.h5` files enabling reproduction of nadir-equivalent brightness temperature maps, TB residual maps, FFR location/strength statistics, and channel-1 lightning detection maps.  Individual maps combined into Figs. 7-17 are also provided.

* `figures-alt:` Figures in the main article include lines and circles to indicate the locations of FFRs.  This directory includes the same figures, but without annotation.
