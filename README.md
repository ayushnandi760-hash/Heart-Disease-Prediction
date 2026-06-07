# Heart Disease Prediction Using Machine Learning

## Project Overview

This project aims to predict the presence of heart disease in patients using machine learning algorithms. The dataset was analyzed, preprocessed, and used to train multiple classification models. The performance of the models was compared to identify the most effective algorithm for heart disease prediction.

## Dataset

**Dataset:** Heart Disease Dataset

The dataset contains medical information such as age, sex, chest pain type, blood pressure, cholesterol levels, maximum heart rate, and other health-related attributes used to predict heart disease.

## Objective

* Perform data preprocessing and cleaning.
* Analyze feature importance and correlations.
* Train multiple machine learning models.
* Compare model performance using evaluation metrics.
* Select the best model for heart disease prediction.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## Project Workflow

### 1. Data Preprocessing

* Loaded and explored the dataset.
* Checked for missing values and data consistency.
* Split data into training and testing sets (80:20).
* Applied feature scaling using StandardScaler.

### 2. Feature Engineering

* Performed correlation analysis using a heatmap.
* Evaluated feature importance using Random Forest.
* Identified key features influencing heart disease prediction.

### 3. Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

### 4. Model Evaluation

Models were compared using:

* Accuracy
* Precision
* Recall
* F1 Score

A comparison table was created to evaluate and compare model performance.

### 5. Best Model Analysis

The best-performing model was selected based on evaluation metrics and analyzed further using a confusion matrix.

## Results

The trained models achieved strong classification performance. Model comparison helped identify the algorithm with the best balance of accuracy, precision, recall, and F1 score.

## Key Findings

* Feature importance analysis highlighted the most influential medical attributes.
* Machine learning models can effectively predict heart disease.
* Proper preprocessing and feature scaling improved model performance.
* Model comparison enabled selection of the most reliable classifier.

## Conclusion

Three machine learning algorithms were trained and evaluated for heart disease prediction. Performance was measured using Accuracy, Precision, Recall, and F1 Score. Feature importance analysis identified significant predictors of heart disease. The best-performing model achieved strong classification results and demonstrated reliable predictive capability. This project demonstrates the practical application of machine learning in healthcare analytics.

## Repository Structure

```text
Heart-Disease-Prediction/
│
├── Project_2.ipynb
├── README.md
├── requirements.txt
└── heart.csv
```

## Author

Ayush Nandi

Machine Learning Internship Project
