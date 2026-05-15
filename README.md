# Medical Insurance Cost Prediction Using Decision Tree Regression

## Project Overview

This project is a Machine Learning application developed to predict medical insurance charges using the Decision Tree Regression algorithm. The project demonstrates a complete Machine Learning workflow, including:

- Data preprocessing
- Feature engineering
- Feature scaling
- Decision Tree model training
- Model serialization
- Deployment using Streamlit

The application predicts medical insurance costs based on customer information such as age, BMI, smoking status, gender, and number of children.

---

## Project Structure

```text
Medical-Insurance-Cost-Prediction-DT/
│
├── 01_Decision_Tree_Model.ipynb
├── 02_Deployment_Decision_Tree_.ipynb
├── app.py
├── insurance_pre.csv
├── Finalized_DT_model.sav
├── requirements.txt
└── README.md
```

---

## Technologies Used

| Category | Tools / Libraries |
|---|---|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas |
| Numerical Computing | NumPy |
| Data Visualization | Matplotlib |
| Model Deployment | Streamlit |
| Feature Scaling | StandardScaler |
| Model Serialization | Pickle |

---

## Dataset Information

The dataset contains customer-related information used for predicting medical insurance costs.

### Features Used

| Feature Name | Description |
|---|---|
| age | Customer age |
| bmi | Body Mass Index |
| children | Number of dependent children |
| sex | Gender |
| smoker | Smoking status |
| charges | Insurance charges (target variable) |

---

## Machine Learning Workflow

### 1. Import Required Libraries

Libraries are imported for:

- Data preprocessing
- Feature scaling
- Visualization
- Model training
- Deployment

---

### 2. Load Dataset

The dataset is loaded using Pandas for data analysis and preprocessing.

The workflow includes:

- Dataset inspection
- Missing value checking
- Data cleaning
- Feature analysis

---

### 3. Data Preprocessing

Categorical variables are converted into numerical values.

Example encoding:

- Male → 1
- Female → 0
- Smoker → 1
- Non-Smoker → 0

Feature scaling is performed using:

```python
StandardScaler
```

---

### 4. Feature Selection

### Input Features

```text
Age
BMI
Children
Gender
Smoking Status
```

### Target Variable

```text
Insurance Charges
```

---

### 5. Model Training

The project uses:

```python
Decision Tree Regression
```

Decision Tree Regression is used to learn decision-based patterns from customer health and demographic data.

---

### 6. Model Saving

The trained model is saved using Pickle serialization.

```text
Finalized_DT_model.sav
```

---

### 7. Model Deployment

The trained Decision Tree model is deployed using Streamlit.

Users can enter customer details and instantly predict medical insurance costs.

---

## Streamlit Application

The Streamlit application provides an interactive interface for insurance charge prediction.

### User Inputs

| Input | Description |
|---|---|
| Age | Customer age |
| BMI | Body Mass Index |
| Number of Children | Dependents count |
| Gender | Male / Female |
| Smoker | Smoking status |

---

### Application Output

```text
Predicted Medical Insurance Cost
```




---

## Run the Streamlit Application

```bash
streamlit run app.py
```

---

## Example Prediction Workflow

### Sample Inputs

| Feature | Example Value |
|---|---|
| Age | 41 |
| BMI | 31.5 |
| Children | 3 |
| Gender | Male |
| Smoker | No |

### Predicted Output

```text
6761.72
```

---

## Learning Outcomes

This project demonstrates practical understanding of:

- Decision Tree Regression
- Feature scaling
- Data preprocessing
- Machine Learning workflow
- Streamlit deployment
- Interactive ML applications
- Model serialization using Pickle

---

## Future Improvements

Potential enhancements for this project:

- Hyperparameter tuning
- Improve model accuracy
- Add model evaluation metrics
- Add visualization dashboards
- Deploy on cloud platforms
- Add responsive UI design
- Build REST API integration

---

## Author

**MANIKANDAPRABHU.S**

Machine Learning and Artificial Intelligence Enthusiast
