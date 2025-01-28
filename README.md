# Diseases-classification-with-decision-trees

1. Project Goal: The goal of this project was to attempt to create a classification model designed to predict autoimmune diseases based on a set of symptoms and medical examination results. 

2. Data: The data for training the classification model was taken from Kaggle - Comprehensive Autoimmune Disorder Dataset (https://www.kaggle.com/datasets/abdullahragheb/all-autoimmune-disorder-10k/data). The dataset contains clinical data of 12,500 patients, both healthy individuals and those diagnosed with various autoimmune diseases (approximately 130 different diseases). Due to the small number of cases for some diseases, they were grouped into 10 groups of diseases affecting various physiological systems of the human body (e.g., neurological diseases, blood diseases, kidney and urinary tract diseases, etc.). An attempt was made to build a classification model for these aggregated data.

3. The repository contains the following files:

EDA: This file contains exploratory data analysis and data preparation for modeling, including verification of data types, analysis and removal of missing data, duplicates and erroneous values, and outliers, feature scaling, and conversion of categorical variables to numerical ones.

Clustering_model: In this file, I attempted to group (cluster) cases using the k-means method to verify whether any naturally occurring patient segments could be distinguished in the dataset. The created clusters were also compared with disease groups created based on medical (domain) knowledge.

Decision_trees_with_clusters: This file presents an attempt to build a classification model with clusters as labels for the classification variable using the decision tree algorithm.

Decision_trees: This file contains an attempt to build, using the decision tree algorithm, a classification model assigning patients to a given disease group representing diseases of a specific physiological system of the human body.

Both classification models were compared with each other, and finally, due to the low quality of classification, I created a classification model with 6 disease groups.
