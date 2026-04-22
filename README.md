# housing-price-prediction
Housing price prediction using machine learning (Kaggle dataset)
# 🏠 Housing Price Prediction (Kaggle Project)

## 📌 Overview

This project builds a machine learning model to predict housing prices using a real-world dataset from Kaggle. It demonstrates an end-to-end data science workflow, including data cleaning, feature engineering, model development, and performance evaluation.

---

## 📊 Dataset

* Source: Kaggle – *House Prices: Advanced Regression Techniques*
* Size: ~1,400 samples with 80+ features
* Includes both numerical and categorical variables with missing values

---

## 🔧 Data Processing

* Handled missing values:

  * Numerical features → imputed with mean
  * Categorical features → filled with `"None"`
* Applied one-hot encoding to transform categorical variables
* Final dataset expanded to ~300 features after encoding

---

## 🤖 Modeling

### 🔹 Baseline Model: Linear Regression

* Simple and interpretable
* Test R²: **~0.44**

### 🔹 Improved Model: Random Forest

* Captures non-linear relationships
* Test R²: **~0.89**

---

## 📈 Model Evaluation

* Used **train-test split (random_state=42)** for reproducibility
* Applied **5-fold cross-validation** for robust performance estimation

**Results:**

* Test R²: **~0.89**
* Cross-validation R²: **~0.86**

👉 The close alignment between these scores indicates strong model stability and generalization.

---

## 📊 Visualization

### 🔹 Actual vs Predicted

* Scatter plot comparing predicted vs actual prices
* Shows strong alignment, indicating good model performance

### 🔹 Feature Importance

* Visualized top features using a horizontal bar chart
* Added value labels for interpretability

---

## 🔍 Key Insights

Top features influencing housing prices:

* OverallQual (overall quality)
* GrLivArea (above-ground living area)
* TotalBsmtSF (basement area)
* GarageArea (garage size)

👉 These results align with real-world housing valuation factors.

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy, Scikit-learn)
* Matplotlib (visualization)
* Jupyter Notebook

---

## 🚀 Key Takeaways

* Built a complete machine learning pipeline using real-world data
* Handled missing values and categorical features effectively
* Compared multiple models and improved performance
* Applied cross-validation for reliable evaluation
* Interpreted model results using feature importance and visualization

---

## 📁 Project Structure

```
housing-price-project/
│
├── data/
│   └── train.csv
│
├── notebook/
│   └── housing_analysis.ipynb
│
├── README.md
└── requirements.txt
```

---

## 📎 Quick Access

👉 [View Notebook](./notebook/housing_analysis.ipynb)

---

## 📬 Contact

Feel free to connect or reach out for discussion or collaboration.
