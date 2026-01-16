
---

# Sales Prediction using Simple Linear Regression

### 📊 Project Overview

This project builds a predictive model to determine the relationship between **TV advertising budgets** and **Sales**. Using the classic Advertising dataset from ISLR, I implemented a Simple Linear Regression model to forecast sales based on marketing spend.

### 🎯 Problem Statement

The goal is to provide actionable insights for a marketing team by answering:

* *How much impact does TV advertising have on total sales?*
* *Can we reliably predict sales performance based on a specific budget allocation?*

### 🛠️ Technical Stack

* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Modeling:** Statsmodels (for detailed statistical summary), Scikit-Learn (for train-test split and evaluation)

### 📈 Key Insights & Results

* **Feature Selection:** Through Exploratory Data Analysis (EDA) and Heatmap correlation, **TV advertising** was identified as the strongest predictor of Sales compared to Radio and Newspaper.
* **Model Performance:** * **R-squared:** **0.816** (Train) | **0.792** (Test). This indicates that ~80% of the variance in sales is explained by TV spend.
* **RMSE:** **2.019**, showing high predictive accuracy on unseen data.


* **Statistical Significance:** The P-value for the TV coefficient is practically **0.000**, confirming that the relationship is statistically significant and not due to chance.

### 🧪 Model Assumptions & Validation

To ensure the reliability of the model, I performed a residual analysis:

1. **Normality of Errors:** Plotted a histogram of residuals which followed a normal distribution centered at zero.
2. **Homoscedasticity:** Validated error terms across the range of the predictor variable to confirm the reliability of the inference.

### 📂 Repository Structure

* `notebooks/`: Contains the Jupyter Notebook with step-by-step EDA and modeling.
* `data/`: The Advertising dataset.
* `requirements.txt`: List of dependencies to reproduce the environment.

---

### 🚀 How to Run

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to view the full analysis and visualization.

---
