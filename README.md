# Water Quality Prediction using Machine Learning Algorithms

## Project Overview

Water quality plays a crucial role in human health and environmental sustainability. This project aims to predict water quality using physicochemical properties of water by applying machine learning algorithms.

The project analyzes water quality indicators such as pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity to classify water as safe or unsafe for drinking.

---

## Objective

To develop a machine learning model that can accurately predict water quality based on various physical and chemical characteristics of water.

---

## Dataset Features

The dataset contains the following attributes:

* pH
* Hardness
* Solids
* Chloramines
* Sulfate
* Conductivity
* Organic Carbon
* Trihalomethanes
* Turbidity
* Potability (Target Variable)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* XGBoost
* Google Colab

---

## Data Preprocessing

The following preprocessing steps were performed before training the models:

* Loaded the dataset using Pandas.
* Checked dataset structure and summary statistics.
* Identified missing values.
* Replaced missing values using mean imputation.
* Applied StandardScaler for feature scaling.
* Split the dataset into training and testing sets.

---

## Machine Learning Models Used

### Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy.

### AdaBoost Classifier

A boosting algorithm that combines weak learners to improve classification performance.

### XGBoost Classifier

An advanced gradient boosting algorithm known for its efficiency and high predictive performance.

---

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

The performance of Random Forest, AdaBoost, and XGBoost algorithms was compared to identify the most effective model for water quality prediction.

---

## Visualization

A bar chart was generated using Matplotlib to compare the accuracy of all three machine learning models.

---

## Prediction System

The trained model accepts new water quality parameter values and predicts whether the water is:

* Safe for Drinking (Potable)
* Unsafe for Drinking (Non-Potable)

Based on the predicted result, the system provides a classification of water quality.

---

## Project Workflow

* Data Collection
* Data Preprocessing
* Handling Missing Values
* Feature Scaling
* Model Training
* Model Evaluation
* Accuracy Comparison
* Water Quality Prediction

---

## Project Files

* Water_Quality_Prediction.ipynb
* water_quality.csv
* Water_Quality_Prediction.pdf

---

## Model Accuracy Comparison

### Accuracy Graph


---

## Conclusion

This project demonstrates how machine learning techniques can be used to analyze water quality parameters and predict water potability. By comparing multiple classification algorithms, the project identifies XGBoost as the most effective model for water quality prediction and provides valuable insights for water quality monitoring applications.

