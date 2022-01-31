# Repository Content
Project for the course FIN-525: Finantial Big Data by Leidi Mauro and Lock Kilian.

In this project we analyze different techniques for creating financial portfolios. We analize how Louvian clustering and max likelyhood clustering are working and the difference in performance between the standard Markowitz portfolio optimization techniques in contrast with two clustering techniques: Louvian clustering and max likelyhood clustering.
# Code organization
## Notebooks
- [Clustering_analysis.ipynb](Clustering_analysis.ipynb) : Notebook containing the main part of the project used to perform the comparaison between the different tested models.
- [libClusteringGiadaMarsiliFast.R](libClusteringGiadaMarsiliFast.R) : R-script necessary to import the max likelyhood clustering algorithm implemented by Giada & Marsili.
- [Clustering_exploration.ipynb]() : Notebook containing analysis of the two Clustering techniques, exploration of the clusters, study of similarities and differences.
## DATA files
- [us_equities_logreturns.parquet](us_equities_logreturns.parquet) : Data file containing US-equities daily log returns.
- The files containing the results of our simulations are exceeding the 100 MB git limit. You can find them here https://drive.google.com/drive/folders/15zJEOOPcjwBF6n17TJrzpc-u7lLA5Klv?usp=sharing
- [INDUSTRIES_AND_CO.xlsx](INDUSTRIES_AND_CO.xlsx) : Data file containing the industries associated to the stocks.
## Scripts and project wide utilities
- [helpers.py](helpers.py) : Project wide constants, file paths, helper and utility functions.
