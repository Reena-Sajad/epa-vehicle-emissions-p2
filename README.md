# EPA Vehicle Emissions Regression - Part 2

This project is a continuation of Part 1, focusing on **advanced regression modeling** techniques to predict the **Greenhouse Gas (GHG) Score** from EPA vehicle data. It emphasizes robust model building, preprocessing pipelines, and performance comparisons using scikit-learn's best practices.

---

## 📌 Project Objectives

- Refine and expand upon the regression pipeline from Part 1.
- Incorporate **scikit-learn pipelines** for streamlined preprocessing and model training.
- Evaluate models using **cross-validation**.
- Compare multiple regressors to identify the best-performing approach for predicting **GHG emissions**.

---

## 🗃️ Dataset

The project uses the **EPA Fuel Economy Dataset**, containing vehicle specifications and environmental ratings.  
**Target Variable**: `Greenhouse Gas Score`

Key features include:
- Vehicle characteristics: `Displacement`, `Cylinders`, `Transmission`
- Fuel metrics: `City MPG`, `Highway MPG`, `Fuel Type`
- Environmental impact: `Air Pollution Score`, `Fuel Cost`, etc.

---

## 🧰 Tools & Libraries

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

---

## 🧪 Regression Models Evaluated

1. **Linear Regression**
2. **Ridge Regression**
3. **Lasso Regression**
4. **Random Forest Regressor**
5. **Gradient Boosting Regressor**
6. **K-Nearest Neighbors Regressor**
7. **Support Vector Regression (SVR)**

---

## ⚙️ Preprocessing Techniques

- Handling missing values
- One-hot encoding for categorical variables
- Feature scaling using `StandardScaler`
- Pipeline integration using `ColumnTransformer` and `Pipeline`

---

## 📊 Evaluation Strategy

Models are evaluated using:
- **Cross-validation scores**
- **R² Score**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

---

## 📁 Project Structure

```bash
epa-vehicle-emissions-regression-part2/
├── epa-vehicle-emissions-p2
└── README.md
