## Epigenetic Aging Clocks for Canines
Using DNA methylation (DNAm) data and regression models to develop epigenetic clocks that can estimate canine age.
This was performed as part of a research training grant challenge, led by UCLA's Institute for Quantitative and Computational Biosciences (QCBio)  and supported by NIH's Big Data to Knowledge (BD2K) initiative

## Content
- [canineAge_dataMatrix.txt.gz](canineAge_dataMatrix.txt.gz)  &nbsp;&nbsp;&nbsp;   Input file, with sample methylation levels at CpG sites
- [canineAge_regressionModeling.ipynb](canineAge_regressionModeling.ipynb)&nbsp;&nbsp;&nbsp;  Jupyter notebook with data analysis workflow
> 1. Data Preparation
> 2. PCA Feature Reduction
> 3. Linear Regression
> 4. Hyperparameter Tuning
> 5. Elastic Net Regression
> 6. Bootstrapping for Enhanced Variable Selection
> 7. Distance-Weighted Prediction Interpolation
> 8. Age Estimates Output
