# TreeSummarizedExperiment_Coxmodel
This repository implements a Cox proportional hazards regression model on microbiome data stored in a TreeSummarizedExperiment object. The microbial abundance table is transformed using the all-pairs log-ratio (PLR) transformation

1. Install Required Packages
To facilitate reproducibility, this project relies on a Docker image that includes many of the required dependencies. Instructions for installing and running the Docker image can be found here:
https://microbiome.github.io/OMA/docs/devel/pages/session_info.html#sec-docker-image

Additionally, users should install any remaining R packages listed at the beginning of the script if they are not already installed.

2. The data on which the analysis is performed can be found in this repository "biom.Rdata".
