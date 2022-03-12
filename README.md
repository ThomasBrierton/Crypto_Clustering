# Crypto_Clustering

This project utilizes machine learning to cluster cryptocurrencies using the K-Means method. The cryptocurrencies are clustered by their performance, and the optimal value for k was determined using the Elbow Curve method. The optimal value for k is seen on the line graph where there is a bend, or elbow displayed in the line. Adding additional clusters beyond this point will not have a large affect in decreasing the inertia. This project applies the K-Means algorithm to two different data types, the original data and the PCA, or Principal Component Analysis. 

---

## Technologies

This project uses Jupyter Notebook (within JupyterLab) and the standard Python 3.8 libraries. This project requires the following libraries and/or dependencies:

- [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation.
- [hvplot](https://hvplot.holoviz.org/) - provides a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data in all the abovementioned formats.
- [Path](https://pypi.org/project/path/) - implements path objects as first-class entities, allowing common operations on files to be invoked on those path objects directly.
- [sklearn](https://scikit-learn.org/stable/) - Simple and efficient tools for predictive data analysis · Accessible to everybody, and reusable in various contexts · Built on NumPy, SciPy, and matplotlib.

---

## Installation

The following dependencies must be installed before running the application:
```
Install Anaconda Package
Pip install Jupyter
pip install -U scikit-learn
conda install -c pyviz hvplot 
```
---

## Methods

To complete this analysis, the following steps were performed:

1. Import and prepare the data.
2. Find the original data's optimal value for k using the Elbow Curve Method.
3. Visualize the cryptocurrencie's clusters by plotting a scatter plot via HvPlot.
4. Repeat steps 1-3 for the PCA data.
5. Compare the results of the original data and the PCA data to determine any differences in the efficiency and tightness of clusters. 

---

## Analysis

The following photo shows the Elbow Curve and scatter plots of the two different data types

![](https://github.com/ThomasBrierton/Crypto_Clustering/blob/main/Photos/Screen%20Shot%202022-03-12%20at%208.49.37%20AM.png)

The Elbow Curve from both data types shows that the optimal value for k is 4. The scatter plot shows tighter clusters using the PCA data. Using HvPlot, one can hover over the value of k=4 on the Elbow Curve to visualize the inertia of the clusters. The PCA data has a smaller inertia, or tighter clusters and runs more efficiently. 

---

## Contributors 

Thomas Brierton and UCB

---

## License

MIT