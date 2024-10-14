# Wine_quality
This project applies various regression models to predict the quality of red wine based on a dataset containing chemical properties of different wine samples. We explore multiple machine learning algorithms, evaluate their performance, and discuss areas for improvement.

**Dataset**
The dataset used is the WineQuality dataset, which contains data about various chemical components found in red wine, along with the wine’s quality score. The goal is to predict the quality of the wine based on its features (e.g., acidity, alcohol content, pH, etc.).

Features: Chemical components (e.g., fixed acidity, volatile acidity, citric acid, residual sugar, alcohol, pH, etc.).
Target: Wine quality score, which is a categorical variable (quality from 0 to 10).
Problem Statement
We are tasked with building a machine learning model that predicts the quality of red wine based on its chemical composition. Since wine quality is a categorical variable, this is a classification problem.

**Models Implemented**
The following machine learning models were tested on the dataset:

**KNeighborsClassifier
Decision Tree Classifier
Random Forest Classifier
Gaussian Naive Bayes
Classification Bin**
Since wine quality is a somewhat subjective measure, we created an arbitrary classification bin to simplify the predictions. This allows the models to classify the wine quality into broader categories, making the classification task easier.

**Model Performance Summary**
Best Performing Model:
**KNeighborsClassifier** with an accuracy score of **0.8984.**
Worst Performing Model:
**Gaussian Naive Bayes** with an accuracy score of **0.8358.**
**Overfitting Issue**
The Decision Tree Classifier and Random Forest Classifier were prone to overfitting, which reduced their generalization ability on the test set. Further tuning of these models is required to mitigate overfitting.

