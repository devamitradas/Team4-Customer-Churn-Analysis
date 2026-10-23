# Customer Churn Analysis 

Telecommunications Customer Churn Analysis
A data analytics and machine learning project focused on understanding customer churn in the telecommunications industry through data preparation, customer segmentation, predictive modeling, and business-oriented analysis.

This repository brings together the datasets, notebooks, trained models, visualizations, technical documentation, and final report developed throughout the project.

Project Overview

Customer churn occurs when customers discontinue a service or subscription. Understanding the factors associated with churn helps telecommunications providers identify customer segments, investigate potential churn patterns, and make more informed customer retention decisions.

The objective of this project is to analyze telecommunications customer data using data preparation and machine learning techniques, explore customer segments through clustering, and develop predictive models to support churn analysis.

The repository organizes the work into the following areas:

Data Preparation: Cleaning, preprocessing, encoding, scaling, and splitting the dataset.
Clustering Analysis: Applying K-Means clustering to explore customer segments and visualize their characteristics.
Predictive Modeling: Developing and evaluating machine learning models for customer churn analysis.
Final Report: Consolidating the project's methodology, analysis, findings, and conclusions.
Repository Structure


Team4-Customer-Churn-Analysis/
│
├── Data_Preparation/
│   ├── preprocessed_dataset.csv
│   ├── train_set.csv
│   ├── test_set.csv
│   ├── Train_Test_Split_Documentation.md
│   └── Scaling_Techniques_Documentation.md
│
├── Clustering_Analysis/
│   ├── kmeans_model.pkl
│   ├── elbow_method.png
│   ├── cluster_visualization.png
│   ├── Optimal_Clusters_Documentation.md
│   └── Cluster_Visualization_and_Labeling.md
│
├── Predictive_Modeling/
│   └── Predictive modeling deliverables
│
├── Final_Report/
│   └── Final project report and supporting deliverables
│
├── Dataset_ATS_v2.csv
├── Stage2_Data_Preparation_and_Clustering.ipynb
└── README.md
Note: The Predictive_Modeling/ and Final_Report/ directories are summarized here. Their exact contents may include additional files and subdirectories.

Dataset

The repository includes Dataset_ATS_v2.csv, a telecommunications customer dataset containing 7,043 customer records, with variables covering customer demographics, service subscriptions, contract information, monthly charges, tenure, and churn status. The dataset includes a Churn target column.

The dataset is used as the starting point for the project's preprocessing and subsequent analysis.

Source dataset: Dataset_ATS_v2.csv
Preprocessed dataset: Data_Preparation/preprocessed_dataset.csv
Project Workflow

1. Data Preparation

The data preparation stage establishes a consistent dataset for subsequent analysis and machine learning.

Key deliverables include:


File	Description
preprocessed_dataset.csv	Dataset after preprocessing and categorical encoding.
train_set.csv	Training partition used in the modeling workflow.
test_set.csv	Held-out testing partition.
Train_Test_Split_Documentation.md	Documents the splitting method, dataset sizes, and class-balance verification.
Scaling_Techniques_Documentation.md	Explains the feature-scaling methods and their rationale.
The documented workflow uses an 80/20 stratified train-test split and scaled features. Consult the accompanying documentation for the exact preprocessing and scaling details.

2. Clustering Analysis

This stage uses K-Means clustering to explore patterns among customers and identify groups with similar characteristics.

The documented clustering workflow uses K-Means with four clusters (k = 4). The elbow method supports the choice of cluster count, while PCA-based visualization helps illustrate the resulting customer groups.


File	Description
kmeans_model.pkl	Saved K-Means model.
elbow_method.png	Elbow-method plot used to assess the number of clusters.
cluster_visualization.png	PCA scatter plot visualizing the resulting clusters.
Optimal_Clusters_Documentation.md	Documents the elbow-method analysis and rationale for selecting four clusters.
Cluster_Visualization_and_Labeling.md	Describes cluster profiles, assigned labels, and associated business insights.
These outputs support exploratory customer segmentation. Cluster membership should be interpreted alongside the documented profiles rather than treated as a direct prediction of churn.

3. Predictive Modeling

The Predictive_Modeling/ directory contains the project's predictive modeling deliverables.

This stage focuses on using customer data to investigate churn prediction through machine learning. The relevant files should be consulted for the implemented algorithms, training procedures, evaluation metrics, and model comparisons.

The predictive modeling results complement the clustering analysis: clustering explores customer groups, while supervised predictive modeling evaluates the ability to distinguish customers who churn from those who remain.

For reproducibility and interpretation, refer to the notebooks, saved artifacts, and evaluation documentation provided in this directory.

4. Final Report

The Final_Report/ directory contains the project's consolidated reporting deliverables.

Refer to this section for the overall methodology, interpretation of results, conclusions, and business implications documented by the project team.

The report should be read alongside the supporting notebooks and documentation when reviewing the analysis or validating individual findings.

Main Notebook

Stage2_Data_Preparation_and_Clustering.ipynb contains the executed Stage 2 workflow for data preparation and clustering.

It serves as the primary notebook reference for the corresponding preprocessing outputs, clustering analysis, and visualizations.

Technology Stack

The project uses a Python-based data science workflow. The core techniques and artifacts documented in the repository include:

Data preparation: Data cleaning, categorical encoding, feature scaling, and train-test splitting.
Machine learning: K-Means clustering and predictive modeling.
Dimensionality reduction and visualization: PCA-based cluster visualization and the elbow method.
Development environment: Jupyter Notebook.
Data and model artifacts: CSV datasets, PNG visualizations, Markdown documentation, and a serialized Python model.

