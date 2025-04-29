# Cirrhosis Patient Survival Prediction

This project is part of **Lab 1** for the course **Applied Artificial Intelligence (IAA), Fall 2023/24**. The goal is to develop a predictive model for patient survival using 17 clinical features. The target variable is `Status`, indicating whether the patient survived or not.

## Project Structure

- `Code_ZhiqianZhou.ipynb`: Jupyter Notebook with all the code needed to reproduce the analysis and modeling steps.
- `IAA_23_24_Q1_Tardor_Laboratori_Report.pdf`: Full report containing explanations, figures, and tables for each stage of the pipeline.
- Dataset: [Cirrhosis Patient Survival Prediction Dataset](https://archive.ics.uci.edu/dataset/878/cirrhosis+patient+survival+prediction+dataset-1)

## Workflow Overview

### 1. Data Analysis and Preprocessing
- Statistical description of each feature
- Class distribution and handling imbalance
- Missing value analysis and imputation strategy
- Outlier detection and treatment
- Train/test or train/validation/test split

### 2. Variable Preparation
- Normalization of numerical features
- Correlation matrix analysis
- Categorical variable analysis
- Dimensionality reduction with PCA

### 3. Model Definition
- Training of 3 models: K-Nearest Neighbors, Decision Tree, and Support Vector Machine
- Hyperparameter selection and justification
- Metric definition and evaluation strategy

### 4. Model Selection
- Comparison of trained models
- Selection of the best-performing model and discussion of limitations
- Final performance evaluation on the test set
  
## Common libraries used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Dataset Citation
If you use this dataset, please cite it as follows:

Dickson, E., Grambsch, P., Fleming, T., Fisher, L., & Langworthy, A. (1989). Cirrhosis Patient Survival Prediction [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5R02G.

## Author
Name: Zhiqian Zhou

Course: Applied Artificial Intelligence (IAA)

Term: Fall 2023/24
