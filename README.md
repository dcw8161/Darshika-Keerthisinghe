# Darshika Keerthisinghe Portfolio
Data Science Portfolio

## [Project 1: Redcross Donor Analysis: Project Overview](https://github.com/dcw8161/Redcross-Donor-Analysis)

* Created the classification model that estimates the Redcross donor indicator that guide the client to allocate their limited resources more efficiently by contacting the most positive prospects
* Visualized the data using Tableau and SweetViz for analysis process
* Feautre engineering by
   * Feature scaling for continuous variables: Normalization method (zscore) was used in PyCaret 
   * Encoding for categorical variables: Encoding was done by PyCaret
   * Simple imputation was used in PyCaret setup
   * Anomalies were found using the PyCaret Anomaly detection.
* Analyzed using different methods,
   * Auto ML with PyCaret
   * H2O AI packeage for Advanced Ml and Deep Learning packages
   * Azure-ML

![](https://user-images.githubusercontent.com/48637798/148803726-5574ccc2-bcd4-42d3-addf-8e09256e9c93.png)

## [Project 2: New Jersey Community FoodBank Analysis: Project Overview](https://github.com/dcw8161/New-Jersey-Community-FoodBank-Data-Analysis)

* Created the regression model that predict the poverty rate which guides the organization to allocate the limited resoiurces more efficiently
* Visualized the data using Tableau and SweetViz for analysis process
* Feature engineering by
   * Feature scaling for continuous variables:  Normalization method (zscore) was used in PyCaret 
   * Encoding for categorical variables: Encoding was done by PyCaret
   * Simple imputation was used in PyCaret setup
   * Anomalies were found using the PyCaret Anomaly detection.
* Analyzed using different methods,
   * Auto ML with PyCaret
   * H2O AI packeage for Advanced Ml and Deep Learning packages
   * Azure-ML

![](https://user-images.githubusercontent.com/48637798/148815382-ee5d2e9a-d001-4edf-bf61-18477c0d420c.png)

## [Project 3: Texas Highschool Performance: Project Overview](https://github.com/dcw8161/Texas-High-School-Data-Analysis)

* Built a regression model to predicts the performance of the Texas Highschools as a guide to get an ideal about school performace for future years
* Visualized the data using Tableau and SweetViz for analysis process
* Feature engineering by
    * Feature scaling for continuous variables:  Min-Max Scaling was performed for the continuous variables
    * Encoding for categorical variables: Categorical variables were encoded using One-Hot encoding
    * New feature, Consecutive_G, was created by summing up PrevFYGiving, PrevFY1Giving, PrevFY2Giving, PrevFY3Giving, PrevFY4Giving, and CurrFYGiving by considering visualizations
    * Outliers were calculated using the percentile method
    * Anomalies were found using the PyCaret Anomaly detection
* Analyzed using different methods,
   * Auto ML with PyCaret
   * H2O AI packeage for Advanced Ml and Deep Learning packages
   * Azure-ML

![](https://user-images.githubusercontent.com/48637798/148813273-e73399b7-a380-4cb0-a717-86ac9c43dbd8.png)


## [Project 4: Cluster Analysis for Zillow Tarrant County Dataset: Project Overview](https://dcw8161.github.io/Cluster-analysis-Zillow-Tarrant-County/)

* Performed cluster analyzing for the Zillow Tarrant Count Dataset eventually to predict the real estate price 
* Visualized the data using Tableau and SweetViz for analysis process
* Feautre engineering by
   * Feature scaling for continuous variables: Normalization method (zscore) was used in PyCaret 
   * Encoding for categorical variables: Encoding was done by PyCaret
   * Simple imputation was used in PyCaret setup
   * Anomalies were found using the PyCaret Anomaly detection.
* Analyzed using different methods,
   * Auto ML with PyCaret
   * H2O AI packeage for Advanced Ml and Deep Learning packages
* Performed cluster analysis using PyCaret kmeans model
* Used elbow method to find the k value and elbow was found at k = 5
* Built the regession model for the entier dataset 
* Used the cluster which has maximum number of data points from cluster analysis and built the regression model for that cluster
* Compared accuracies and cluster analysis increases the accuracy of the regression model

![](https://github.com/dcw8161/Darshika-Keerthisinghe/blob/main/Images/Screen%20Shot%202022-01-30%20at%2010.52.19%20PM.png)
