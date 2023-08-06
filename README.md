# Customer Segmentation Project
 This project aims to segment customers based on their buying behavior and geographic location using the RFM (Recency, Frequency, Monetary Value) analysis technique. Additionally, the project implements classifiers to classify customers into different types based on their purchasing patterns.

# Project Overview
The project is divided into several steps:

Data Preprocessing: The dataset containing online retail data is loaded and preprocessed to remove missing values, negative quantities, and create a TotalPrice column.

Customer Segmentation (RFM Analysis): The customers in the United Kingdom are segmented using the RFM analysis. The RFM table is created, and customers are classified into different segments based on their recency, frequency, and monetary value scores.

Visualizing Customer Segmentation: The segmented customers are visualized using a 3D scatter plot, showing the clusters of customers with similar buying behavior.

Customer Segmentation for Other Countries: The same segmentation and visualization process is performed for other countries in the dataset, such as Germany and France.

Customer Type Classification: The dataset is preprocessed to prepare it for classification. Random Forest Classifier, SVD and KNN Classifier, PCA and Decision Tree Classifier, and LDA and KNN Classifier are implemented to classify customers into different types based on their RFM scores and country.

# Dependencies
The project requires the following Python libraries:

numpy
pandas
matplotlib
scikit-learn
plotly
datetime

# Author
This project is developed by G Mukund. Feel free to contact me at mukund.1@iitj.ac.in for any questions or feedback.

# License
This project is licensed under the MIT License. Feel free to use the code for educational and non-commercial purposes.