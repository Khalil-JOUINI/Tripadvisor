# Tripadvisor
Machine learning project
Exploring TripAdvisor Reviews with Data Analysis

🔍 Objective:
Conducted a comprehensive analysis of TripAdvisor reviews using Python, Pandas, Seaborn, and Scikit-learn. 
The project aimed to uncover patterns and groupings within the dataset for enhanced insights.

Project Workflow:

Data Import:

Imported necessary libraries: Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.
Loaded the TripAdvisor reviews dataset ('tripadvisor_review.csv').
Checked data information and null values using info() and isnull().sum().
Data Exploration:

Explored statistical summaries of the dataset using describe().
Data Visualization:

Created a pairplot to visualize pairwise relationships among features using Seaborn.
Data Preprocessing:

Standardized the data using StandardScaler to ensure uniformity across features.
Normalized the standardized data using the normalize function.
Dimensionality Reduction:

Implemented Principal Component Analysis (PCA) to reduce the dataset's dimensions to two components.
Clustering Analysis:

Utilized Agglomerative Clustering with the WARD method to categorize data into five clusters.
Visualization of Clusters:

Visualized clustered data points in a scatter plot using the first and second principal components.
Key Findings:

Successfully identified patterns and relationships within the TripAdvisor reviews dataset.
Reduced the dataset dimensions for efficient analysis using PCA.
Clustered data points into distinct groups using Agglomerative Clustering.
