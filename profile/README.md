** ----- This GitHub page is currently under construction ----- **

## Welcome to Ohio State University's MRI Reconstruction (OSU-MR) Toolbox
### PI's website: https://u.osu.edu/ahmad/

Welcome to OSU-MR. Our primary focus is to share code for MR data acquisition, pre-processing, and reconstruction. Our codebase is built on the principle of transparency, accessibility, and reproducibility.

## Public code repositories
### Data sampling (GRO, CAVA, VISTA, OPRA, PR4D)
Implementation of pseudo-random Cartesian sampling patterns for 2D cine, 2D flow, 3D cine, and 4D flow
* MATLAB code: https://github.com/OSU-CMR/cmr-sampling
* Related publication: https://arxiv.org/abs/2206.03630

### Calibrationless image reconstruction (HICU)
Implementation of a calibrationless k-space reconstruction for 2D static, 3D static, and 2D+t dynamic applications
* MATLAB code: https://github.com/OSU-CMR/HICU
* Related publication: https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.28721

### Image reconstruction with posterior sampling (CNF)
Implementation of conditional normalizing flow for accelerated multi-coil MRI reconstruction
* Python code: https://github.com/OSU-MR/mri_cnf
* Related publication: https://proceedings.mlr.press/v202/wen23a

### Self-supervised image reconstruction (ReSiDe)
A plug-and-play-based self-supervised MRI reconstruction method
* Python code: https://github.com/OSU-MR/reside
* Related publication: https://arxiv.org/abs/2304.12890

### Motion-robust volumetric CMR reconstruction (CORe)
Image reconstruction with outlier rejection for motion-robust free-running 3D imaging
* MATLAB code: https://github.com/OSU-MR/motion-robust-CMR
* Related publication: https://arxiv.org/abs/2308.02088

### Surface coil intensity correction (SCC)
Implementation of a surace coil intensity correction for data collected on Siemens scanners
* Python code: https://github.com/OSU-MR/SCC
* Related publication: https://arxiv.org/abs/2312.00936
  
## Public data repositories
### Open-access multi-coil k-space dataset for CMR (OCMR)
* Python/MATLAB code: https://github.com/MRIOSU/OCMR/tree/master
* Link to download data: https://ocmr.info/download/
* Related publication: https://arxiv.org/pdf/2008.03410.pdf
* Description: A k-space data repository for cardiac cine along with the code to read the data 
