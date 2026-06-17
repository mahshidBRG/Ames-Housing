# Ames Housing Aplied Data Science 

A complete end-to-end Data Science project based on the **Ames Housing Dataset**, covering the entire workflow from data exploration and preprocessing to machine learning modeling.

The repository is organized into two branches:

| Branch | Description |
|----------|------------|
| `master` | Assignment 1 – Exploratory Data Analysis (EDA), Data Cleaning, Feature Engineering, Encoding, Feature Selection, and PCA |
| `modeling` | Assignment 2 – Regression, Binary Classification, and Multiclass Classification models built using the processed dataset from Assignment 1 |

---

# Dataset

**Ames Housing Dataset**

The dataset contains detailed information about residential homes sold in Ames, Iowa, including:

- Physical characteristics
- Property size
- Construction quality
- Neighborhood information
- Sale price

Target variable:

- **SalePrice**

---

# Repository Structure

## Branch: `master`

Data preprocessing and feature engineering pipeline.

### Main Tasks

- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Outlier Analysis
- Feature Engineering
- Categorical Encoding
  - Ordinal Encoding
  - One-Hot Encoding
- Feature Scaling
- Feature Selection
- PCA Analysis
- Exporting processed datasets

### Outputs

```text
eda_cleaning/
encoding_details/
scaling_details/
selecting_details/
pca_details/
fe_pre_pca/
```

### Notebook

```text
EDA_&_Cleaning.ipynb
```

---

## Branch: `modeling`

Machine Learning modeling using the processed dataset generated in Assignment 1.

### Regression

Predicting house sale prices.

Notebook:

```text
Regression/Regression_Methods.ipynb
```

Tasks include:

- Model training
- Model comparison
- Performance evaluation
- Regression metrics analysis

---

### Binary Classification

Predicting whether a house is:

- Expensive
- Normal

Target:

```text
IsExpensive
```

Notebook:

```text
Classification/Binary_classification_Methods.ipynb
```

Tasks include:

- Binary target generation
- Model training
- Evaluation and comparison
- Classification metrics analysis

---

### Multiclass Classification

Predicting house price categories.

Notebook:

```text
Classification/Multiclass_Classification_Methods.ipynb
```

Tasks include:

- Quartile-based price categorization
- Multiclass model training
- Evaluation and comparison
- Confusion matrix and performance analysis

---

# Project Highlights

- End-to-end Data Science workflow
- Extensive Exploratory Data Analysis
- Advanced Feature Engineering
- Multiple Encoding Strategies
- Feature Selection Techniques
- PCA Dimensionality Reduction
- Regression Modeling
- Binary Classification Modeling
- Multiclass Classification Modeling
- Model Evaluation and Comparison

---

# Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---
