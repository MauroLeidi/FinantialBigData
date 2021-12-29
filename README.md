# Repository Content
Project for the course FIN-525: Finantial Big Data

In this project we analyze different techniques for creating financial portfolios. The main focus is to try to study the difference in performance between the standard Markowitz portfolio optimization techniques in contrast with two clustering techniques: Louvian clustering and max likelyhood clustering.
# Code organization
## Notebooks
- [Clustering_analysis.ipynb](Clustering_analysis.ipynb) : Notebook containing the main part of the project used to perform the comparaison between the different tested models.
- [libClusteringGiadaMarsiliFast.R](libClusteringGiadaMarsiliFast.R) : R-script necessary to import the max likelyhood clustering algorithm implemented by Giada & Marsili.
## DATA files
- [us_equities_logreturns.parquet](us_equities_logreturns.parquet) : Data file containing US-equities daily log returns.
## Scripts and project wide utilities
- [helpers.py](helpers.py) : Project wide constants, file paths, helper and utility functions.
