# Project Overview
This repository presents a modular pipeline for multiclass intrusion detection using the CSE-CIC-IDS2018 dataset. It goes through preprocessing, label mapping, model training and performance evaluation across the selected algorithms. Model selection was guided by comparative performance observed on the NSL-KDD dataset, where candidate algorithms—Deep Learning, Logistic Regression, Decision Tree, Random Forest, SVM, KNN, XGBoost and Naive Bayes were benchmarked on precision, recall, and F1 metrics for binary intrusion classification. The top performers, XGBoost, and Deep Learning, were selected for CSE-CIC-IDS2018.

## CSE-CIC-IDS2018 Dataset 
This project uses the CSE-CIC-IDS2018 dataset for network intrusion detection modeling.
The dataset files (e.g., `02-20-2018.csv`) are not included in the repository due to size constraints.
To run this project, download the dataset used from (https://www.kaggle.com/datasets/solarmainframe/ids-intrusion-csv) 

The CSE-CIC-IDS2018 dataset is large and segmented by day, with each file corresponding to specific attack types and traffic patterns.
For this project, only four days were selected: `02-14-2018.csv`, `02-15-2018.csv`, `02-22-2018.csv`, `03-02-2018.csv`. 

## Attack Types
 02-14-2018.csv - FTP-BruteForce, SSH-Bruteforce
 02-15-2018.csv - DoS-Slowloris, DoS-GoldenEye
 02-22-2018.csv - Brute Force Web, Brute Force XSS, SQL Injection
 03-02-2018.csv - Botnet 






