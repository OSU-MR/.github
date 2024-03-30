** ----- This GitHub page is currently under construction ----- **

## Welcome to Ohio State University's MRI Reconstruction (OSU-MR) Toolbox
### PI's website: https://u.osu.edu/ahmad/

Welcome to OSU-MR. Our primary focus is to share code for MR data acquisition, pre-processing, and reconstruction. Our codebase is built on the principle of transparency, accessibility, and reproducibility.

## Public code repositories
### Data Sampling (GRO, CAVA, VISTA, OPRA, PR4D)
* MATLAB code: https://github.com/OSU-CMR/cmr-sampling
* Related publication: https://arxiv.org/abs/2206.03630
* Description: Implementation of pseudo-random Cartesian sampling patterns for 2D cine, 2D flow, 3D cine, and 4D flow
      
### Image Reconstruction (HICU)
* MATLAB code: https://github.com/OSU-CMR/HICU
* Related publication: https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.28721
* Description: Implementation of a calibrationless k-space reconstruction for 2D static, 3D static, and 2D+t dynamic applications

### Surface coil intensity correction (SCC)
* Python code: https://github.com/OSU-MR/SCC
* Related publication: https://arxiv.org/abs/2312.00936
* Description: Implementation of a surace coil intensity correction for data collected on Siemens scanners

## Public data repositories
### Open-Access Multi-Coil k-Space Dataset for CMR (OCMR)
* Python/MATLAB code: https://github.com/MRIOSU/OCMR/tree/master
* Link to download data: https://ocmr.info/download/
* Related publication: https://arxiv.org/pdf/2008.03410.pdf
* Description: A k-space data repository for cardiac cine along with the code to read the data 
