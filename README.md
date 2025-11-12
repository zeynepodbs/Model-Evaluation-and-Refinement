# Model-Evaluation-and-Refinement

This project was completed as part of the **IBM Developer Skills Network / Coursera: “Data Analysis with Python”** course.  
The notebook focuses on evaluating regression models using cross-validation, polynomial regression, and Ridge regularization techniques.

---

## Project Overview

This notebook demonstrates practical steps for **model evaluation** and **overfitting control** in a regression problem.

### Objectives
1. **Load & prepare** a dataset of laptop features and prices  
2. **Apply Cross-Validation** to evaluate model generalization  
3. **Explore Polynomial Regression** to observe underfitting/overfitting behavior  
4. **Use Ridge Regression** for regularization  
5. **Perform Grid Search (GridSearchCV)** to tune hyperparameters

---

## Technologies Used
- **Python** (NumPy, Pandas, Matplotlib, Seaborn)
- **Scikit-Learn** (LinearRegression, PolynomialFeatures, Ridge, GridSearchCV)
- **Jupyter Notebook**

---

## Dataset
The dataset (`laptops.csv`) was downloaded from **IBM Skills Network** (Coursera).  
> **Note:** This dataset is publicly accessible and provided by IBM for educational use only.

---

## Example Results

**Polynomial Degree vs R²:**
- Training R² increases with degree
- Test R² peaks at moderate degree (2–3), then declines due to overfitting

**Ridge Alpha vs R²:**
- As `alpha` increases, variance reduces and generalization improves

## Acknowledgment
> **Data Source & Course Notice**  
> This notebook was developed as part of the **IBM Developer Skills Network / Coursera: “Data Analysis with Python”** course practice lab.  
> The lab materials and datasets are publicly accessible via IBM Skills Network and used **for educational purposes**.  
> All analysis and code in this repository are **my own work**; no proprietary Coursera content or autograder cells are included.

---
