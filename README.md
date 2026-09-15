# Customer Churn Analysis and Feature Scaling

## 📌 Overview

This project demonstrates basic **Data Preprocessing** techniques using Python and Pandas.

The project focuses on:

- Customer Churn Dataset analysis
- Handling missing values
- Mean and Median calculation
- Removing columns containing missing values
- Feature Scaling
- Min-Max Normalization
- Standardization using StandardScaler

These techniques are commonly used in **Data Analytics and Machine Learning** projects.

---

## 📂 Notebooks

### 1. Churn Notebook

The `Churn_Notebook.ipynb` demonstrates basic data preprocessing on a customer churn dataset.

#### Operations Performed:

- Importing required Python libraries
- Loading the CSV dataset
- Checking dataset information using `info()`
- Checking missing values
- Removing columns containing missing values
- Calculating the mean of the `Age` column
- Calculating the median of the `Age` column
- Filling missing values in the `Age` column using the mean

### 2. Feature Scaling Notebook

The `FeatureScaling_Notebook.ipynb` demonstrates feature scaling techniques using Scikit-learn.

#### Operations Performed:

- Loading the customer churn dataset
- Exploring the dataset using `head()`, `tail()`, and `describe()`
- Selecting `Age` and `Tenure` features
- Checking and handling missing values
- Applying **Min-Max Scaling**
- Applying **Standard Scaling**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 📊 Dataset

The notebooks use customer churn datasets:

- `Churn_modelling.csv`
- `Churn_Modelling1.csv`

The datasets contain customer-related information that can be used for customer churn analysis and preprocessing demonstrations.

---

## 🔧 Data Preprocessing

### Missing Value Handling

Missing values are identified using:

```python
df.isnull().sum()
