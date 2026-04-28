# Medical Insurance Cost Prediction using Decision Tree Regression

### Author: MANIKANDAPRABHU.S

### Project Type: Machine Learning – Regression

---

## 1) Project Overview

This project predicts medical insurance costs using a **Decision Tree Regression** model.

The model learns patterns from customer demographic and health-related data to estimate insurance charges. Decision Tree is a non-linear model that can capture complex relationships between input features and the target variable.

---

## 2) Dataset

File used: `insurance_pre.csv`

The dataset contains:

* Age
* BMI (Body Mass Index)
* Number of Children
* Gender
* Smoking Status
* Charges (Target Variable)

The goal is to predict insurance cost based on these features.

---

## 3) Workflow

1. Import required libraries
2. Load dataset using pandas
3. Handle categorical variables using encoding
4. Prepare feature matrix (X) and target variable (y)
5. Split dataset into training and testing sets
6. Train Decision Tree Regression model
7. Make predictions
8. Evaluate model using:

   * R² Score
   * Mean Squared Error (MSE)
   * Root Mean Squared Error (RMSE)
9. Analyze feature importance
10. Visualize results
11. Save trained model using pickle

---

## 4) Model Evaluation

* Decision Tree captures non-linear relationships effectively.
* Model performance is evaluated using R² Score, MSE, and RMSE.
* Feature importance helps identify the most influential variables affecting insurance charges.

---

## 5) Project Files

* `01_Decision_Tree_Model.ipynb` – Model training and evaluation
* `02_Deployment_Decision_Tree.ipynb` – Model deployment and prediction
* `insurance_pre.csv` – Dataset
* `decision_tree_model.sav` – Trained model
* `requirements.txt` – Required Python libraries

---

## 6) Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Pickle

---

## 7) Model Deployment

* Model is saved using pickle
* Deployment implemented using Jupyter Notebook
* User input is taken and passed to the trained model for prediction

---

## 8) Conclusion

* Implemented Decision Tree Regression for insurance cost prediction
* Model captures complex relationships without requiring feature scaling
* Feature importance provides insights into key influencing factors
* Demonstrates effectiveness of tree-based models for regression tasks

---

## 9) Use Case

This project can help insurance companies estimate customer charges based on personal and health-related factors, enabling better pricing and risk assessment strategies.
