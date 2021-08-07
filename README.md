

# San Francisco Housing

This application uses data visulization tools including aggregation, interactive visualizations, and geospatial analysis to analyze the trend of rent and price per square footage in San Francisco from 2010 to 2016. The tools allow the convinence of organizing data by neighborhood, and/or year making it easy to decide which neighborhood would be best to invest in and can yield the biggest profit from the highest rent with the lowest buying price. 





---

## Technologies

This prodject uses Python 3.7 with the following packages:
* ### **os** - Allows inreaction with the operating system
* ### **pandas** - A package of intuitive data analysis tools
* ### **plotly express** - Can create dynamic graphs, plots, and figures
* ### **hvplot** - Creates static plots from API's with feetures like hovering, zooming, and scanning
* ### **pathlib** - To format file imported and saved
* ### **dotenv** - Loads environment variables from an env file




---

## Installation Guide

First, install the following:
    
    conda create -n pyvizenv python=3.7 -y
    conda activate pyvizenv
    conda install ipykernel -y
    conda install -c conda-forge jupyterlab=2 -y
    conda install -c plotly plotly=4.13. -y
    conda install -c pyviz hvplot -y
    conda install -c conda-forge nodejs=12 -y
    conda install streamz -y
    pip install python-dotenv decorator==4.3 networkx
    conda install nb_conda_kernels ipykernel -y
    jupyter labextension install jupyterlab-plotly@4.13.0 --no-build
    jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.13.0 --no-build
    jupyter labextension install @pyviz/jupyterlab_pyviz --no-build
    conda list plotly
    conda list hvplot
    conda list nodejs
    pip install questionary

Then import the following:
    
    import os
    import pandas as pd
    from pathlib import Path
    from dotenv import load_dotenv
    import plotly.express as px
    import hvplot.pandas


---

## Usage

Within the pyviz environment complete installations and imports and run code. Be sure to use various tools within the plots further analyze the data (ex. zoom, scan, hover ). 






---

## Contributors

A.Nansamba Ssensalo
[LinkedIn](www.linkedin.com/in/a-nansamba-ssensalo)

---

## License

[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)
