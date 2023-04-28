# miripsfs
MIRI empirical PSFs

This repository contains empirical PSF models for JWST/MIRI imaging. The models are supplied as fits files with an oversampling of 2x2 (i.e. a pixelscale of 0.055 arcsec/pixel) and do not contain any spatial variation over the MIRI detector. 

The PSF models are constructed by stacking stars from MIRI calibration programs on the LMC. Note that these models are created from drizzled images with the purpose of getting an overall acceptable model that also characterizes the wings (including the MIRI cruciform pattern). 

Currently available models (work in progress):
- F560W

The models are supplied as-is, if you decide to use them for published work make sure to check that they are applicable to what you need (in particular the note on drizzled images above). If you use them please add a citation to xxx.
