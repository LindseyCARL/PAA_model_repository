# PAA_model_repository

## Contributors

Daibo Zhang and Stephanie E. Lindsey, Ph.D.. Mechanical and Aerospace Engineering, UC San Diego, La Jolla, CA, USA

## General Information

Repository of chick embryonic pharyngeal arch arteries (PAAs) anatomical models and flow curves needed to run PAA hemodynamic simulations. The models and subsequent simulation results are reported in reference (1).

## Data and file overview

HH26Control_LSFM_nativeSizeCGS.vtp is the anatomical reconstruction of a Hamburger-Hamilton Stage 26 (HH26, day 5) control Rhode Island red chick embryo PAA based on LSFM images. HH26Control_4DUS_nativeSizeCGS.vtp is the anatomical reconstruction for the same embryo based on 4DUS images. The length unit for both models is centimeter. HH26Control_FlowCurve.png is the representative inflow curve used as boundary condition for hemodynamic simulations in the two models.

## Methodological information

LSFM sample preparation and imaging protocol were detailed in reference (1) and (2). 4DUS imaging and post-processing protocol were described in (1).

The models were constructed using SimVascular's built-in segmentation tools, and simulations were performed using its solvers. We recommend using SimVascular to reproduce any desired hemodynamic simulation. For more informations on SimVascular, please visit: https://simvascular.github.io/

## Sharing and access information

Please cite reference (1) and (2) when reporting any result generated from HH26Control_LSFM_nativeSizeCGS.vtp. Please cite reference (1) when reporting any result generated from HH26Control_4DUS_nativeSizeCGS.vtp and HH26Control_FlowCurve.png. 

## References

(1) Zhang, Daibo, and Stephanie E. Lindsey. "3D vascular quantitation with application to computational modeling: a pre-clinical light sheet microscopy, high resolution ultrasound, nano-computed tomography comparison study." bioRxiv (2026): 2026-03. doi: https://doi.org/10.64898/2026.03.13.711685

(2) Zhang, Daibo, and Stephanie E. Lindsey. "Rapid whole-mount high-resolution imaging of small animal vasculature for quantitative studies." JoVE (Journal of Visualized Experiments) 219 (2025): e68206. DOI: 10.3791/68206-v

The LSFM facility is supported by grant P30 NS047101. The ultrasound facility is supported by grant S10 OD032268
