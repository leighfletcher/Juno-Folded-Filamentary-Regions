# JIRAM

## FITS Files
Cylindrical projections of JIRAM 5-micron (M-band) observations of Jupiter from PJ3-40, as used in Fletcher et al. (2025) to study Jupiter's Folded Filamentary Regions.

These are stored as GZIP-compressed `.fits` files, one for the north, and one for the south.  Raw JIRAM observations have been sampled on a 0.1x0.1 degree grid, such that the .fits files have 3600 pixels in the x-direction (360W on the left, 0W on the right) and 900 pixels in the y-direction (90S to 0S, and 0N to 90N, planetocentric latitudes).

There has been no attempt to correct for emission angle, nor have distant observations been filtered out.  Pixels are registered based on Juno SPICE kernels, and have not been corrected for any offsets associated with the tilt mirror (i.e., we have not used the limb position to correct the pointing).  For higher-precision processing we urge the user to extract JIRAM maps directly from the [Planetary Data System](https://atmos.nmsu.edu/PDS/data/PDS4/juno_jiram_bundle/data_calibrated/).

## PNG Files
Polar projections of PJ3-40 are also provided as PNG files, saved in the `.zip` directories above.  These are plotted for latitudes from 50 to 90 degrees in each hemisphere, based on the data contained in the `.fits' files.
