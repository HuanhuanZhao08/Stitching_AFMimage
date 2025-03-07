[![Paper](https://img.shields.io/badge/paper-arXiv%3AXXXX.YYYYY-B31B1B.svg)](https://arxiv.org/abs/XXXX.YYYYY)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://zenodo.org/badge/latestdoi/XXXXYYYYY)

# A bi-channel Aided Stitching of Atom Force Microscopy Images 

**Huanhuan Zhao**, Ruben Millan Solsona, Spenser R. Brown, Marti Checa, Liam Collins, **Arpan Biswas** 

[arXiv:XXXX.YYYYY](https://arxiv.org/abs/XXXX.YYYYY)

### Abstract
Microscopy is an essential tool in scientific research, enabling the visualization of structures at micro- and nanoscale resolutions. However, the field of microscopy often encounters limitations in field-of-view (FOV), restricting the amount of sample that can be imaged in a single capture. To overcome this limitation, image stitching techniques have been developed to seamlessly merge multiple overlapping images into a single, high-resolution composite. The images collected from microscope need to be optimally stitched before accurate physical information can be extracted from post analysis. However, the existing stitching tools either struggle to stitch images together when the microscopy images are feature sparse or cannot address all the transformations of images when performing image stitching. To address, in this paper, we propose a two-channel aided feature-based image stitching method and showcased on Atomic Force Microscopy (AFM) generated biofilm images as experimental data. The topographical channel image of AFM data captures the morphological details of the sample, and a stitched topographical image is desired for researchers. We utilize the amplitude channel of AFM data to maximize the matching features and to estimate the position of the original topographical images. We see the proposed two-channel aided stitching method outperforms the traditional direct stitching approach in AFM topographical image stitching task. Furthermore, we found that the differentiation of the topographical images along the x-axis provides similar feature information to the amplitude channel image, which generalizes our approach when the amplitude images are not available. Here we demonstrated the application on AFM, but similar could be employed of optical microscopy with brightfield and fluoresce channels. We believe this proposed workflow can serve as a valuable augmentation strategy for microscopy image stitching tasks and will benefit the experimentalist to avoid erroneous analysis and discovery due to incorrect stitching.

![image](https://github.com/user-attachments/assets/5cd9fadd-c037-4a04-9cf2-9bbfd6e1840f)

Proposed approach of feature-based bi-channel aided image stitching of microscopy images. Here fig. (a) shows the traditional single-channel stitching of stack of overlapped microscopy images of interest (eg. topographical images) where (b) shows the bi-channel stitching of the topographical images via our proposed approach of using physical information from optimal second imaging channel (Eg. amplitude image). 

### Description
This repository includes links, code, scripts, and data to generate the figures in a paper.

### Data
The samples used in this study correspond to **Pantoea sp. YR343**. The dataset was collected from AFM images, acquired using the DriveAFM system from Nanosurf, as described in [1]. More information on the dataset is provided in the main paper and notebook. The raw dataset is provided in **Data** folder [here](https://github.com/arpanbiswas52/Stitching_AFMimage/tree/main/data). 

### Requirement
A minimal environment to execute these notebooks can be installed via `pip install -r requirements.txt`


### Support

The authors acknowledge the use of facilities and instrumentation at the UT Knoxville Institute for Advanced Materials and Manufacturing (IAMM) and the Shull Wollan Center (SWC) supported in part by the National Science Foundation Materials Research Science and Engineering Center program through the UT Knoxville Center for Advanced Materials and Manufacturing [DMR-2309083](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2309083&HistoricalAwards=false). AFM imaging was performed at the Center for Nanophase Materials Sciences (CNMS), which is a US Department of Energy, Office of Science User Facility at ORNL.

<img width="400px" src="https://mrsec.org/sites/default/files/MRSEC%20logo_clear%20background.png">


### Reference
[1]Millan-Solsona, R. et al. Analysis of Biofilm Assembly by Large Area Automated AFM. Preprint at https://doi.org/10.21203/rs.3.rs-5537963/v1 (2025).


