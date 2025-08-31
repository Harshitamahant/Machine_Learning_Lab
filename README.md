# 📘 Machine Learning Lab Notebooks

This repository contains Jupyter notebooks for various foundational machine learning concepts and algorithms, implemented with Python libraries such as NumPy, Pandas, Matplotlib, and Scikit-learn.

---

## 📚 Contents

### 1. `simple_linear_regression_ML01.ipynb`
- Implements **Simple Linear Regression** using a housing dataset.
- Predicts house prices based on a single independent variable.
- Dataset used:  
  - `houseprice_dataset (1).csv`  
  - `improper_houseprice (1).csv` (to test error handling with missing/improper values)

### 2. `Introduction_to_ml_tools_and_libraries_ML_02.ipynb`
- Introduces popular **ML tools and libraries** such as:
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib and Seaborn
- Includes basic usage examples and visualizations.

### 3. `DataPreprocessing_and_cleaning_ML_03.ipynb`
- Covers essential **data preprocessing and cleaning techniques** such as:  
  - Handling missing values (mean/median imputation)  
  - Detecting outliers using Interquartile Range (IQR)  
  - Label encoding of categorical features  
  - Feature scaling (Standardization and Normalization)  
- Includes visualizations (boxplots) for outlier detection  
- Uses the **Boston Housing** dataset as an example.  

### 4. `PCA_04_ML.ipynb`
- Performs **Principal Component Analysis (PCA)** for dimensionality reduction and visualization.
- Standardizes features using `StandardScaler` and extracts top principal components with `PCA` from Scikit-learn.
- Visualizes:
  - 2D projection using the first two principal components.
  - Scree plot to show cumulative explained variance.
- Helps understand data patterns in reduced dimensions.

### 5. `KNN_05_ML.ipynb`
- Implements **K-Nearest Neighbors (KNN)** classification using a small, manually defined dataset.
- Classifies input points based on height and weight features using `k=3`.
- Includes:
  - Model training and prediction on test data
  - Evaluation using a **confusion matrix**
  - Confusion matrix visualization with `matplotlib`

### 6. `Decision_tree_ML_06.ipynb`  
- Implements **Decision Tree Classification** using Scikit-learn.  
- Demonstrates splitting rules, Gini index, and entropy.  
- Visualizes the **decision tree structure** for better understanding.  
- Includes prediction and accuracy evaluation on a sample dataset.  

### 7. `Naive_Bayes_07_ML.ipynb`  
- Implements **Naive Bayes Classification**.  
- Covers:  
  - **Gaussian Naive Bayes** for continuous features  
  - Application on a small dataset for classification tasks  
- Demonstrates training, prediction, and evaluation.  

### 8. `Random_forest_08_ML.ipynb`  
- Implements **Random Forest Algorithm** for classification.  
- Demonstrates:  
  - Ensemble learning approach  
  - Feature importance extraction  
- Evaluates model performance using accuracy and confusion matrix.  

### 9. `Linear_regression_09_ML.ipynb`  
- Implements **Multiple Linear Regression**.  
- Predicts dependent variable using multiple independent features.  
- Compares model accuracy between **simple and multiple regression**.  
- Visualization included for regression fitting.  

---

## 📊 Datasets

- **houseprice_dataset (1).csv**: Clean dataset with house prices for regression tasks.  
- **improper_houseprice (1).csv**: Contains missing or improper data to explore preprocessing techniques like handling null values.  
- **Boston Housing**: [Download Link](https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv)  
- **Sample dataset** for KNN and PCA: Hardcoded arrays used within the notebooks for demonstration.

---



## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Harshitamahant/Machine_Learning_Lab.git
   cd Machine_Learning_Lab
