# Module 10 Challenge

## Cluster Cryptocurrency Data with K-means and Optimize Results using Primary Component Analysis (PCA)

In this challenge we import and prepare a given data set of many cryptocurrencies for analysis.  Once completed we implement K-means testing and PCA to determine the best value for *k* based on visual plots of the given data after it has been analyzed and cleaned for comparison.

1) Collect the data
2) prepare the data
3) analyze the data

The visuals produced with 

---

## Technologies

The code is written to run in the 'dev' environment we set up in Python version 3.7.1, (now running python version 3.10.9.final.0) on a [JupyterLab](https://jupyter.org) Notebook (version 3.4.4).

This notebook requires the following libraries and modules:

1) *'[pandas](https://pandas.pydata.org/)'* library is required in order to analyze a 2-dimensional *DataFrame* in Python programming language.
2) *'Path'* which is a class included as part of the 'pathlib' module in Python's standard library is needed to import data with the "read_csv" command.
3) *'hvplot'* must be imported in order to *'plot'* our data for analysis and used to create meaningful visual representations of DataFrames.
    + hvplot.line
    + hvplot.scatter

4) import the required classes from 3 modules found in the *'scikit-learns'* Python library to analyze DataFrames with assistance of *machine learning*
    + implement the *'Kmeans'* class from the *'cluster'* module which is an unsupervised machine learning algorithim for grouping and clustering data points based on their features.
    + implement the *'PCA'* class from the *'decomposition'* module to help identify the most important components of the data.
    + implement the *'StandardScaler'* class from the *'preprocessing'* module to ensure features have a similar scale which can improve the performance and stability of models.
    
5) the built-in Python *'matplotlib'* library is utilized to call the *'plot'* function for creating visualizations from DataFrames.

---

## Installation Guide

if your current Python environment does already not have *'pandas'* or *'scikit-learn'* libraries installed, download them from *Python Package Index (PyPI)* and then complete the installation for use:
        
        pip install pandas
        pip install hvplot *OR* conda install -c pyviz hvplot
        pip install scikit-learn *OR* conda install scikit-learn


---

## Usage

First, navigate to my github repo called "10_crypto_clustering" and activate your 'dev' environment for python 3.7, clone the repo locally

Next, type "jupyter lab" to open a new kernel, then navigate to open *'crypto_investments.ipynb'* listed in the 'code' folder.

Finally, run the code from your new *Jupyter Notebook* in your browser.

---

## Contributors

Mark Beers: 
[Linked In](https://www.linkedin.com/in/markwbeers/)
---

## License

MIT License 

