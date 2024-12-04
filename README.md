![Python](https://img.shields.io/badge/Python-3.x-blue)

# Data Wrangling Project

Welcome to the **Data Wrangling Project** repository! This project focuses on analyzing and cleaning transactional retail data using Python. The main objectives include identifying and resolving dirty, missing, and outlier data across various CSV files, ensuring the dataset is clean and ready for analysis.

---

## 📁 Dataset Background

The dataset represents transactional retail data from **DigiCO**, a fictional online electronics store based in Melbourne, Australia. DigiCO operates exclusively online with three warehouses in Melbourne to handle customer deliveries.

- **Each row** in the dataset corresponds to an individual order.
- The dataset contains various issues, including missing values, anomalies, and outliers, which must be addressed to enable effective analysis.

---

## 🛠️ Key Project Steps

### 1️⃣ **Exploratory Data Analysis (EDA)**  
   - Perform **graphical** and **non-graphical** EDA to understand the dataset.  
   - Use EDA to identify:
     - Anomalies
     - Missing data
     - Outliers  
   - Document findings and insights in the project report.  

---

### 2️⃣ **Impute Missing Values**  
   - File: `missing_data.csv`  
   - **Objective**: Impute missing values using appropriate methods.  
   - **Approach**:
     - Apply multiple imputation techniques.
   - **Note**: impute missing values where present

---

### 3️⃣ **Detect and Fix Errors**  
   - File: `dirty_data.csv`  
   - **Objective**: Identify and fix anomalies in the dataset.  
   - **Approach**:
     - Each row contains at most one anomaly with one possible fix.
     - Ensure the cleaned data conforms to the correct dataset structure.  
   - Document EDA techniques used to detect errors and outline the cleaning process in the report.  

---

### 4️⃣ **Detect and Remove Outliers**  
   - File: `outlier_data.csv`  
   - **Objective**: Identify and remove outliers based on the `delivery_charges` attribute.  
   - **Approach**:
     - Perform outlier detection.
     - Remove outliers while ensuring data validity.  
   - **Note**: This file contains only outliers and no other anomalies.  

---

### 5️⃣ **Validate Delivery Charges with a Model**  
   - **Objective**: Train a regression model to validate `delivery_charges`.  
   - **Modeling Approach**:
     - Use a **linear regression model**.
     - Factors to include:
       - Distance between the customer and the nearest warehouse.
       - Expedited delivery status.
       - Customer satisfaction (via sentiment analysis).  
   - Ensure an **R² score of at least 0.95**.  

---

## 📊 Tools and Techniques

- **Python Libraries**: 
  - Pandas
  - NumPy
  - Matplotlib for visualization
  - Scikit-learn for modeling
  - Datetime
- **EDA Methods**:
  - Statistical summaries
  - Visualization techniques for identifying trends and anomalies
- **Imputation Techniques**:
  - Mean/median substitution
  - K-Nearest Neighbors (KNN)
  - Regression-based methods
- **Outlier Detection**:
  - IQR (Interquartile Range)
  - Visualization-based methods

---

## 📋 Deliverables

- **Cleaned Datasets**:
  - `missing_data_solution.csv`
  - `dirty_data_solution.csv`
  - `outlier_data_solution.csv`
- **Project Report**:
  - Detailed documentation of EDA, cleaning methods, and model training.
- **Trained Model**:
  - A regression model for validating delivery charges.

---

## 🚀 Getting Started

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/data-wrangling-project.git
