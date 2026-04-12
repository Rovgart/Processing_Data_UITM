# Data Processing and Integration Project 📊

This repository contains a comprehensive data preprocessing and machine learning pipeline developed as part of the "Data Processing" course. The project focuses on transforming raw, "dirty" datasets into a machine-learning-ready format through advanced engineering techniques.

## 🚀 Project Overview
The main objective of this project is to demonstrate a robust ETL (Extract, Transform, Load) process. It covers everything from integrating disparate data sources to validating the quality of the processed data using a baseline ML model.

## 🛠 Tech Stack
* **Language:** Python 3.x
* **Environment:** Virtualenv / Jupyter Notebook
* **Key Libraries:** * `Pandas` - Data manipulation and integration
    * `NumPy` - Numerical operations
    * `Scikit-learn` - Preprocessing and ML modeling
    * `Matplotlib` & `Seaborn` - Data visualization and quality validation

## 📋 Pipeline Architecture
The project follows a strict engineering workflow:
1. **Data Integration:** Merging multiple data sources into a single coherent structure.
2. **Data Cleaning:** * Handling missing values (Imputation strategies).
    * Outlier detection and management (IQR Method).
3. **Feature Engineering:**
    * Categorical Data Encoding (One-Hot / Label Encoding).
    * Data Normalization & Standardization (`StandardScaler` / `MinMaxScaler`).
    * Creating new synthetic attributes to enhance model performance.
4. **Dimensionality Reduction:** Optimizing the feature space for better performance.
5. **Quality Validation:** Using a baseline **Decision Tree** model to verify the integrity of the processed data.

## 🧠 Key Insights
> "Data is the new oil, but only if it's refined." 
This project treats methodology not just as a formal requirement, but as a technical wrapper for solving real-world data inconsistency problems.

## ⚡ How to Run
1. Create a virtual environment: `python -m venv venv`
2. Activate: `source venv/bin/activate` (or `.\venv\Scripts\activate` on Windows)
3. Install dependencies: `pip install -r requirements.txt`
4. Run the notebook: `jupyter notebook`