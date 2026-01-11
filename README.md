# Cancer Analysis (KMeans + Logistic Regression)

This project works with a cancer dataset and uses two machine learning methods:  
KMeans is used to find groups in the data.  
Logistic Regression is used to predict cancer type.

## Project Goal

Understand the data using KMeans clustering.  
Build a model to predict cancer type.  
Check the model performance.

## Dataset

The dataset is loaded from UCI using `ucimlrepo`.  
Dataset ID: 17.  
The data is converted into a Pandas DataFrame.  
The features are numeric.

## Data Preparation

Converted the dataset into a DataFrame.  
Scaled the features using StandardScaler and MinMaxScaler.  
Split the data into training and test sets.  
Used PCA to reduce dimensions and visualize the data.

## Models Used

### KMeans (Unsupervised Learning)

Applied KMeans clustering.  
Used inertia (elbow method) to understand clustering behavior.

### Logistic Regression (Supervised Learning)

Trained a Logistic Regression model.  
Evaluated the model using:
- Accuracy  
- Recall  
- F1-score  
- Confusion Matrix  
- Classification Report
