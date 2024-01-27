# Diabetes Prediction Project

In this project, we addressed a supervised machine learning problem using a dataset related to diabetes. The dataset, originating from the National Institute of Diabetes and Digestive and Kidney Diseases, aims to predict whether a patient has diabetes based on diagnostic measurements.

### Steps
1. Importing Packages:
   
We started by importing necessary Python packages to facilitate our analysis and model training.

2. Loading the Dataset:
   
The diabetes dataset was loaded for exploration and modeling.

3. Exploratory Data Analysis (EDA):
   
We conducted an in-depth exploratory data analysis, covering aspects such as missing values, relationships between predictor variables and the dependent variable, correlation between predictors, distribution analysis, and outlier detection.

4. Preprocessing and Feature Engineering:
   
Steps included dividing the dataset into training and testing sets, handling missing values, treating outliers, scaling and normalization, and addressing class imbalance using SMOTE.

5. Training the Model:
   
We trained various models, including Random Forest and Logistic Regression, on both imbalanced and balanced datasets. Model evaluation metrics, including recall, precision, and accuracy, were used to assess performance. Hyperparameter tuning was performed to optimize model performance.

6. Final Model Selection:
   
The Random Forest model, with hyperparameter tuning and feature selection, demonstrated the best performance, and it was chosen as the final model.

8. Model Deployment:
   
The final Random Forest model was retrained on the entire dataset and saved as a joblib file for future use.

### Repo Structure
Notebooks: 

Contains the Jupyter notebook for the predictive modeling.

Diabetes: 

Holds the original diabetes dataset in CSV format.

Model: 

Contains the final trained Random Forest model saved in a joblib file.

Readme: 

This file providing an overview and instructions on how to use the repo.

### Instructions for Use
Clone the repository to your local machine.
Open the Jupyter notebook in the "Notebooks" folder to review the predictive modeling process.
Explore the "Diabetes" folder for the original dataset.
Access the final trained model in the "Model" folder.
Follow the guidance in this README file for a comprehensive understanding of the project.

### Key Findings
Blood pressure was found to be a non-significant predictor and was dropped from the feature set.
Random Forest, after hyperparameter tuning and feature selection, emerged as the best-performing model with a test recall of 80%.
