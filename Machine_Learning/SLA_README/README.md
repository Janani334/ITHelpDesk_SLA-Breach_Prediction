
# IT Help Desk SLA Breach Prediction – Machine Learning

## Project Overview

The **IT Help Desk SLA Breach Prediction** project focuses on developing a machine learning model to predict whether IT Help Desk tickets will meet or breach their Service Level Agreement (SLA).

The project uses ticket-related information, exploratory data analysis, and datetime-based feature engineering to identify patterns associated with SLA performance.

The prediction task is a binary classification problem:

- **Met:** Ticket meets the SLA.
- **Not Met:** Ticket breaches the SLA.

## Project Objectives

- Analyze IT Help Desk ticket data.
- Perform Exploratory Data Analysis (EDA).
- Clean and prepare the dataset.
- Perform feature engineering.
- Extract meaningful features from datetime information.
- Identify patterns associated with SLA breaches.
- Build a machine learning classification model.
- Evaluate model performance.
- Predict potential SLA breaches.

## Tools and Technologies Used

| Category | Tools and Technologies |
|---|---|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Model Development | Jupyter Notebook |
| Model Storage | Pickle |
| Development Environment | Google Colab / Jupyter Notebook |
| Version Control | Git and GitHub |

## Machine Learning Workflow

### 1. Data Loading

Load the IT Help Desk ticket dataset and examine its structure, columns, and data types.

### 2. Data Preprocessing

Prepare the dataset for machine learning by handling data quality issues and organizing the required features.

### 3. Exploratory Data Analysis (EDA)

Perform exploratory analysis to understand:

- Ticket distribution.
- SLA status distribution.
- Ticket-related patterns.
- Relationships between features and SLA outcomes.

### 4. Feature Engineering

Extract meaningful information from ticket data, including datetime-based features, to improve the model's ability to identify SLA breach patterns.

### 5. Model Development

Develop a machine learning classification model to predict SLA outcomes.

The model classifies tickets into two categories:

- SLA Met
- SLA Not Met

### 6. Model Evaluation

Evaluate the trained model using appropriate classification evaluation metrics.

### 7. Model Saving

Save the trained model and required feature information for future use.

## Project Files

| File / Folder | Description |
|---|---|
| `SLA_Breach_Prediction_Prjct.ipynb` | Main machine learning implementation notebook |
| `models/` | Model-related files |
| `sla_breach_model.pkl` | Saved SLA breach prediction model |
| `sla_feature_columns.pkl` | Saved feature column information |
| `catboost_info/` | Model training information |
| `Vdo/` | Project demonstration video |

## Project Demonstration Video

[▶ Watch Machine Learning Project Demonstration](../Vdo/SLA_Breach_Prediction_Prjct.ipynb_Compressed.mp4)

## Key Outcomes

- Performed exploratory analysis on IT Help Desk ticket data.
- Applied data preprocessing and feature engineering.
- Extracted datetime-based features.
- Developed a machine learning approach for SLA breach prediction.
- Worked on binary classification of SLA outcomes.
- Saved the trained model and feature information.

## Skills Demonstrated

- Python Programming
- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Datetime Feature Extraction
- Machine Learning
- Classification
- Model Evaluation
- Model Serialization
- Jupyter Notebook
- Git and GitHub

## Conclusion

This project demonstrates the application of machine learning techniques to IT Help Desk ticket data for predicting SLA compliance.

Through data preprocessing, exploratory analysis, feature engineering, and model development, the project aims to identify tickets that may meet or breach their defined Service Level Agreements.
