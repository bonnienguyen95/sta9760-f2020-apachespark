# Analyzing 10Gb of Yelp Reviews Data
This project is a part of the STA9760 - Big Data Technologies class at Baruch College, City University of New York. 

## Project Description
We will analyze a subset of Yelp's business, reviews and user data. This dataset comes to us from [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset) although we have taken steps to pull this data into a private s3 bucket.

### Methods Used
* Hypothesis Testing
* Data Visualization

### Technologies
* AWS EMR Spark
* AWS Jupyter Notebook
* Python
* Pandas, Numpy, Scipy, Matplotlib, Seaborn

## Analysis

This project is broken down into 4 parts:
### Part I: Installation and Initial Setup

In this portion, we will import the necessary dependencies (pandas and matplotlib, seaborn is optional) and load the dataset as a pyspark dataframe.

### Part II: Analyzing Categories

For this part, we will denormalize the categories that are associated with each business and then running some basic analysis on the result.

### Part III: Do Yelp Reviews Skew Negative?

For this next part, we will attempt to answer the question: are the (written) reviews generally more pessimistic or more optimistic as compared to the overall business rating. 

### Part IV: Should the Elite be Trusted? (Or, some other analysis of your choice)
For this final part, we will perform a hypothesis test to determine whether elite users should be trusted with their business ratings.

## Getting started

1. Download all three datasets from [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset)
2. Configure an AWS S3 bucket and upload said datasets to it
3. Download the Analysis.ipynb file from the [link attached](https://github.com/bonnienguyen95/sta9760-f2020-apachespark/blob/master/Analysis.ipynb)
4. Configure an AWS EMR Spark cluster and Jupyter notebook following the cluster and notebook configurations
5. In the Analysis.ipynb file, update the path to your corresponding S3 object in order to appropriately locate and load these datasets into Spark. 
6. Run the file.


## Cluster and Notebook Configs
### Cluster Configuration
![cluster](https://raw.githubusercontent.com/bonnienguyen95/sta9760-f2020-apachespark/master/assets/cluster_configuration.png)

### Notebook Configuration
![notebook](https://raw.githubusercontent.com/bonnienguyen95/sta9760-f2020-apachespark/master/assets/notebook_configuration.png)
