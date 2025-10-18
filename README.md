# Distributed-Data-Analysis-and-Mining-Project

The project folder is divided into two main folders containing the datasets (not included in the repository due to size limitations) and the code for each of the four case studies: North, South, East, and West of the addressed problem. It also includes a PDF report describing the work carried out.

Specifically, the Codes folder is further divided into four subfolders, each containing the logic related to the tasks completed in the four different case studies:

- Data Understanding & Feature Extraction
- Data Preparation
- Clustering
- Classification

The code was entirely developed in a Spark environment, using the main libraries associated with the PySpark module:
- ml -> to concatenate normalization, vectorization, and model training activities within dedicated Pipelines.
- mllib -> to apply the main Machine Learning algorithms and evaluate their performance using key metrics.
- sql -> to perform SQL operations on distributed data.
 
Additional libraries such as Seaborn and Pandas were used when necessary to properly visualize specific results.
