
# Vehicle CO₂ Emission Prediction using Regression Models 🚗📉

This project demonstrates a comprehensive machine learning workflow to predict CO₂ emissions of vehicles based on engine and fuel parameters. Using multiple regression techniques, it explores relationships within the data and evaluates model performance with statistical metrics.

---

## 📌 Project Overview

This notebook walks through the complete machine learning pipeline:

- ✅ Loading & inspecting the dataset
- ✅ Cleaning missing and redundant values
- ✅ Exploratory Data Analysis (EDA) with visualizations
- ✅ Feature selection and correlation analysis
- ✅ Model building:
  - Linear Regression
  - Multiple Linear Regression
- ✅ Evaluation metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² score
- ✅ Visual interpretation of actual vs predicted results
- ✅ Final model comparison and result analysis

---
## Link to the kaggle notebook
-  (https://www.kaggle.com/code/pushkararora/multi-reg)

## 📊 Dataset
The dataset is from the Canadian Government’s open data portal and contains fuel usage and CO₂ emission stats for various vehicles.

- 📎 Download link: [FuelConsumption.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%202/data/FuelConsumptionCo2.csv)

- **Size**: 1,064 vehicle records
- **Key features used**:
  - `ENGINESIZE`
  - `CYLINDERS`
  - `FUELCONSUMPTION_CITY`
  - `FUELCONSUMPTION_HWY`
  - `CO2EMISSIONS` (target variable)


## 📈 Key Results

- ✅ **Best performing model**: Polynomial Regression (Degree = 2)
- 🎯 **R² Score**: **0.99998** — nearly perfect prediction accuracy
- 🧮 **Mean Squared Error (MSE)**: 0.088
- 🧾 **Residual Sum of Squares (RSS)**: 18.88
- 🌀 **Variance of y_test**: 4,983.14

The polynomial model captures the non-linear relationship between variables with extreme precision, indicating a near-perfect fit to the validation data. Residual errors are minimal, making this model the most accurate of all tested regressors.



## 🛠️ Tech Stack

This project is built using the following tools and libraries:

| Tool | Purpose |
|------|---------|
| **Python** | Programming language |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical computations |
| **Matplotlib / Seaborn** | Data visualization |
| **Scikit-learn** | Model building and evaluation |

---

## 📁 Files in the Repository

- `multireg_git.ipynb` – Complete code and outputs for CO₂ emission prediction
- `images/` *(optional)* – Visuals used in README or LinkedIn post

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/vehicle-co2-prediction.git
   cd vehicle-co2-prediction
   
## 🤝 Let's Connect 

Want to chat machine learning, CO₂ emissions, or data viz?
- [LinkedIn](https://www.linkedin.com/in/pushkar-arora-0b3599356/)
- [Kaggle](https://www.kaggle.com/pushkararora)
