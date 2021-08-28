

# Crypto Investments


This application uses unsupervised machine learning tools including KMeans and PCA to compare the effects of using optimized data and the best K value to create predicted clusters shown via scatter plots. 





---

## Technologies

This prodject uses Python 3.7 with the following packages:
* ### **os** - Allows inreaction with the operating system
* ### **pandas** - A package of intuitive data analysis tools
* ### **hvplot** - Creates static plots from API's with feetures like hovering, zooming, and scanning
* ### **pathlib** - To format file imported and saved
* ### **scikit** - Libraby of machine learning tools





---

## Installation Guide

First, install the following:
    
    conda list hvplot
    conda install scikit-learn -y
    conda install -c pyviz hvplot -y
    
    
For PC users first import the following:

    import os
    os.environ["OMP_NUM_THREADS"] = "1" # export OMP_NUM_THREADS=4
    os.environ["OPENBLAS_NUM_THREADS"] = "4" # export OPENBLAS_NUM_THREADS=4 
    os.environ["MKL_NUM_THREADS"] = "6" # export MKL_NUM_THREADS=6
    os.environ["VECLIB_MAXIMUM_THREADS"] = "4" # export VECLIB_MAXIMUM_THREADS=4
    os.environ["NUMEXPR_NUM_THREADS"] = "6" # export NUMEXPR_NUM_THREADS=6

    os.environ["MKL_NUM_THREADS"] = "1" 
    os.environ["NUMEXPR_NUM_THREADS"] = "1" 
    os.environ["OMP_NUM_THREADS"] = "1" 

To run the application with the following libraries:  
    
    import pandas as pd
    import hvplot.pandas
    from pathlib import Path
    from sklearn.cluster import KMeans
    from sklearn.decomposition import PCA
    from sklearn.preprocessing import StandardScaler


---

## Usage
Within the pyviz environment:

* ### Use the StandardScaler module to normalize the data in the imported CSV file
* ### Use the elbow method to find the best K value
* ### Use the KMeans model slong with the K value to graph a scatter plot of predicted clusters
* ### With the original data optimize the data using the PCA model and be sure to take note of the explained variance ratio
* ### With this new data again find the best K value and use the KMeans model to graph the clusters. 
* ### Compare the two scatter plots and K values to see the effects of optimizing the data before training machine learning tools








---

## Contributors

A.Nansamba Ssensalo
[LinkedIn](www.linkedin.com/in/a-nansamba-ssensalo)

---

## License

[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)
