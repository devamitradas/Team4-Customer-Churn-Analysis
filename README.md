# Customer Churn Analysis — Stage 2 Submission

Telecommunications Customer Churn Analysis project, Stage 2: Data Preparation and Modeling.

## Repository Structure

```
├── Data_Preparation/
│   ├── preprocessed_dataset.csv
│   ├── train_set.csv
│   ├── test_set.csv
│   ├── Train_Test_Split_Documentation.md
│   └── Scaling_Techniques_Documentation.md
├── Clustering_Analysis/
│   ├── kmeans_model.pkl
│   ├── elbow_method.png
│   ├── cluster_visualization.png
│   ├── Optimal_Clusters_Documentation.md
│   └── Cluster_Visualization_and_Labeling.md
├── Stage2_Data_Preparation_and_Clustering.ipynb
└── README.md
```

## What's in Each Deliverable

### Data_Preparation/
- **preprocessed_dataset.csv** — full dataset after cleaning and encoding categorical variables.
- **train_set.csv / test_set.csv** — 80/20 stratified split, scaled features.
- **Train_Test_Split_Documentation.md** — split method, size, and class-balance verification.
- **Scaling_Techniques_Documentation.md** — which features were scaled, method used, and why.

### Clustering_Analysis/
- **kmeans_model.pkl** — trained K-Means model (k=4).
- **elbow_method.png** — elbow chart used to select k.
- **cluster_visualization.png** — PCA scatter plot of the resulting clusters.
- **Optimal_Clusters_Documentation.md** — full elbow-method analysis and reasoning for k=4.
- **Cluster_Visualization_and_Labeling.md** — cluster profiles, labels, and business insights.

### Stage2_Data_Preparation_and_Clustering.ipynb
The full, executed notebook containing all code for data preparation and clustering — this is the source for every file and figure listed above.


