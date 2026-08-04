# MVSE-Index-P

This repository contains the datasets supporting the analyses presented in "Evaluating Index P as a predictor of Dengue Transmission Risk: A Nationwide Provincial Analysis of Thailand, 2012-2021", spanning all 77 provinces of Thailand from January 2012 to December 2021 (n = 9,240 province-month observations).

Datasets include: monthly province-level dengue fever (DF) and dengue haemorrhagic/shock syndrome (DS) case counts from Thailand's national dengue surveillance system, province-level humidity data interpolated via Inverse Distance Weighting (IDW) in QGIS, used as climatic input to the MVSE framework, monthly Index P estimates for all provinces calculated using the MVSE package (v1.01r) with Aedes aegypti transmission priors adapted from Obolski et al. (2019).

Spearman correlation coefficients between Index P and case counts across 0–6 month lag windows, along with lag-optimization results and provincial consistency scores summarizing year-to-year stability of Index P–case correlations and a latitude regression dataset pairing province centroid latitude with Index P performance metrics.

Together, these datasets enable full reproduction of the national, spatial, temporal, and latitudinal analyses reported in the paper.
