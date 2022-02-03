# Data Cleansing Article for Medium

## Introduction
<b>This code only runs in Jupyterlab because Mito is only supported in Jupyterlab.</b><br>
You can remove Mito references and it will run in Jupyter notebook<br><br>
This code is used in my Medium article on Data cleansing and Plotting
It is here to serve the purpose of illustrating what I did and how I did it.
This code only runs in Jupyterlab because Mito is only supported in Jupyterlab.

Mito in this demo needs to be installed using the instructions from its site.
https://docs.trymito.io/getting-started/installing-mito

## Technologies
* Python 3.9
* jupyterlab==3.1.18
* pandas==1.3.3
* plotly==5.3.0
* mitoinstaller==0.0.96     
* mitosheet3==0.3.157

## A note on config-sample.py
You need to add your mapbox token to this file and rename it to config.py before running your notebook.
This file and token saves your token out of the main codebase as it is mentioned in the .gitignore file
