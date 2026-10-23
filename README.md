# Customer Churn Analysis 

**Telecommunications Customer Churn Analysis**
A data analytics and machine learning project focused on understanding customer churn in the telecommunications industry through data preparation, customer segmentation, predictive modeling, and business-oriented analysis.

**Project Overview**

Customer churn occurs when customers discontinue a service or subscription. Understanding the factors associated with churn helps telecommunications providers identify customer segments, investigate churn patterns, and make informed customer retention decisions.

This project applies data preparation and machine learning techniques to telecommunications customer data, explores customer segments through clustering, and develops predictive models to support churn analysis.

The project is organized into four main areas:

Data Preparation: Cleaning, preprocessing, encoding, scaling, and splitting the dataset.
Clustering Analysis: Applying K-Means clustering to explore customer segments and visualize their characteristics.
Predictive Modeling: Developing and evaluating machine learning models for customer churn analysis.
Final Report: Consolidating the project's methodology, analysis, findings, and conclusions.


## Repository Structure

```text
Team4-Customer-Churn-Analysis/
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
│   ├── ANN Architecture Documentation.docx
│   ├── Stage3_ANN_Churn_Prediction_PyTorch.ipynb
│   └── ann_churn_model.pt
│
├── Final_Report/
│   ├── Documentation of Limitations and Proposed Solutions.docx
│   ├── Identification of Factors Contributing to Churn and Retention.docx
│   ├── Recommendations for Targeted Retention Strategies.docx
│   └── Summary of key findings.docx
│
├── Dataset_ATS_v2.csv
├── Stage2_Data_Preparation_and_Clustering.ipynb
└── README.md
```

Note: The Predictive_Modeling/ and Final_Report/ directories may contain additional files and subdirectories.

**Dataset**

The project uses a telecommunications customer dataset containing customer information, service subscriptions, contract details, billing information, tenure, and churn status.

Source dataset: Dataset_ATS_v2.csv
Preprocessed dataset: [Data_Preparation/preprocessed_dataset.csv](Data_Preparation/preprocessed
Project Workflow

**1. Data Preparation**

The data preparation stage prepares the dataset for machine learning by applying preprocessing techniques and organizing the data for training and evaluation.

Key deliverables:
File	Description
preprocessed_dataset.csv	Dataset after cleaning and categorical encoding.
train_set.csv	Training partition used in the modeling workflow.
test_set.csv	Held-out testing partition.
Train_Test_Split_Documentation.md	Documents the splitting method, dataset sizes, and class-balance verification.
Scaling_Techniques_Documentation.md	Explains the feature-scaling techniques and their rationale.
The documented workflow uses an 80/20 stratified train-test split and scaled features. Refer to the accompanying documentation for details about the specific preprocessing and scaling methods.

**2. Clustering Analysis**

The clustering stage applies K-Means to explore customer groups with similar characteristics.

The documented workflow uses K-Means with four clusters (k = 4). The elbow method supports the selection of the cluster count, while PCA-based visualization helps illustrate the resulting clusters.

Key deliverables:
File	Description
kmeans_model.pkl	Saved K-Means clustering model.
elbow_method.png	Elbow-method plot used to assess the number of clusters.
cluster_visualization.png	PCA scatter plot visualizing the resulting clusters.
Optimal_Clusters_Documentation.md	Documents the elbow-method analysis and rationale for selecting four clusters.
Cluster_Visualization_and_Labeling.md	Describes cluster profiles, labels, and associated business insights.
These outputs support exploratory customer segmentation and help identify patterns that may inform customer retention strategies.

**3. Predictive Modeling**

The Predictive_Modeling/ directory contains the project's predictive modeling deliverables.

This stage focuses on applying machine learning techniques to investigate customer churn prediction. Refer to the files in this directory for the implemented algorithms, model training procedures, evaluation metrics, and model comparisons.

Predictive modeling complements clustering analysis: clustering explores customer groups, while supervised learning evaluates the ability to predict customer churn from available features.

**4. Final Report**

The Final_Report/ directory contains the consolidated reporting deliverables for the project.

This section presents the overall methodology, analysis, findings, conclusions, and business implications documented by the project team.

The final report should be read alongside the supporting notebooks, datasets, and technical documentation for a complete understanding of the analysis.

**Main Notebook**

Stage2_Data_Preparation_and_Clustering.ipynb contains the executed Stage 2 workflow for data preparation and clustering.

It provides the code and analysis associated with the preprocessing outputs, clustering methodology, and visualizations documented in the repository.

**Technology Stack**

The project uses a Python-based data science workflow, incorporating:

Python for data processing and machine learning.
Pandas and NumPy for data manipulation and numerical operations.
Scikit-learn for preprocessing and machine learning workflows.
Matplotlib and Seaborn for data visualization.
Jupyter Notebook for interactive analysis and documentation.
Refer to the notebooks and project files for the exact libraries and configurations used.
Project Deliverables

The repository includes:

Source telecommunications customer dataset.
Preprocessed dataset and train-test partitions.
Documentation for data splitting and feature scaling.
Trained K-Means clustering model.
Elbow-method and cluster visualization figures.
Documentation covering cluster selection, interpretation, and labeling.
Predictive modeling deliverables.
Final project report.
Executed notebook documenting the Stage 2 data preparation and clustering workflow.

**Conclusion**

This project combines data preparation, customer segmentation, and predictive modeling to investigate telecommunications customer churn.

By bringing together datasets, notebooks, trained models, visualizations, and technical documentation, the repository provides a structured workflow for analyzing customer behavior and exploring data-driven approaches to customer retention.

The findings and recommendations should be interpreted in the context of the models, evaluation metrics, and results documented in the corresponding project deliverables.
