# Experiment 14  
## Data Normalization and Turning Categorical Variables into Quantitative Variables in Python
## Arddra Soni
## 25070123022
## ENTC A1

---

## Aim
To study and perform data normalization and convert categorical variables into quantitative variables using various Python functions and operations.

---

## Theory
In data analysis and machine learning, raw data often contains different scales of numerical values and categorical variables. Before analysis, the data must be preprocessed so that it becomes suitable for computational models.

Two important preprocessing techniques are:

- Data Normalization  
- Categorical Variable Encoding  

These techniques help in improving data quality, consistency, and analysis accuracy.

---

## 1. Data Normalization

### Definition
Data normalization is a technique used to scale numerical data into a common range so that all features contribute equally to the analysis.

#### Example

| Feature      | Range        |
|--------------|-------------|
| Price        | 500 – 50000 |
| Rating       | 1 – 5       |
| Units Sold   | 10 – 1000   |

Without normalization, features with larger ranges dominate smaller ones.

### Benefits
- Standardizes the scale of data  
- Improves performance of machine learning models  
- Makes comparisons between variables easier  

---

## Types of Normalization

### 1. Min-Max Normalization
This method scales values between 0 and 1.

**Functions / Operations**
- `min()`
- `max()`

---

### 2. Z-score Normalization (Standardization)
This method transforms data based on mean and standard deviation.

**Functions / Operations**
- `mean()`
- `std()`

It indicates how far a value is from the average value of the dataset.

---

### 3. Decimal Scaling
In this method, the decimal point of values is shifted so that all values fall within a smaller range.

**Operation**
- Division by powers of 10

---

## Useful Functions for Normalization

### Summary Statistics
- `describe()`

Displays:
- Mean  
- Standard deviation  
- Minimum  
- Maximum  

---

### Identify Data Types
- `dtypes`

Used to identify numerical columns that require normalization.

---

### Select Columns
- `loc[]`
- `iloc[]`

Used to apply normalization to specific columns of the dataset.

---

## 2. Turning Categorical Variables into Quantitative Variables

### Definition
Many datasets contain categorical variables, which represent qualitative data.

#### Examples

| Variable          | Values               |
|------------------|---------------------|
