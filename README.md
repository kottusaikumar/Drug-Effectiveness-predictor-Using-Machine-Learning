# 🧪 Drug Effectiveness Predictor Using Machine Learning

This project focuses on predicting the effectiveness of a drug based on various patient health attributes using supervised machine learning regression algorithms.

## 📁 Project Structure

- `ML_Regression.ipynb`: Main Jupyter notebook containing data analysis, model training, and evaluation.
- `requirements.txt`: Contains required Python packages to run the project.
- `README.md`: Project documentation.

---

## 🎯 Objective

The main goal is to build regression models that can predict a target health value (e.g., drug dosage, effectiveness score, or other medical metric) using clinical or synthetic data. This helps in understanding how various patient attributes influence medical outcomes.

---

## 🧠 Machine Learning Models Implemented

The notebook implements and compares three different regression models:

1. **Linear Regression**  
   - Assumes a linear relationship between input features and target variable.

2. **Decision Tree Regressor**  
   - A tree-based model that learns decision rules from data.

3. **Random Forest Regressor**  
   - An ensemble method combining multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 🔍 Dataset Overview

> 📌 Note: You need to update this section with the actual dataset name and source if it’s public.

- The dataset includes several numeric features such as:
  - Age
  - Blood pressure
  - Glucose levels
  - Body Mass Index (BMI)
  - Insulin
  - Diabetes Pedigree Function
  - Outcome/Drug Effectiveness Score (target)

- Shape: `(n_samples, n_features)`

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for missing values and data types.
- Visualized distributions using histograms and seaborn plots.
- Checked feature correlations using a heatmap.

---

## 🔎 Feature Selection and Processing

- Selected key features with high correlation to the target.
- Normalized/standardized if needed.
- Split data into train and test sets (typically 80/20).

---

## 🏁 Model Evaluation

Models are evaluated using:

- **R² Score**: Measures how well predictions approximate the actual values.
- **Mean Squared Error (MSE)**: Average squared difference between predicted and true values.

| Model                 | R² Score | Mean Squared Error |
|----------------------|----------|--------------------|
| Linear Regression     | 0.93     | 0.59              |
| Decision Tree         | 1.00    | 0.63              |
| Random Forest         | 0.97     | 0.160             |

> 📌 Update this table after running your notebook.

---

## 🛠️ Libraries and Tools Used

- Python 3.8+
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## ▶️ How to Run the Project

### 1. Clone the repository 

```bash
git clone https://github.com/kottusaikumar/Drug-Effectiveness-predictor-Using-Machine-Learning.git
cd Drug-Effectiveness-predictor-Using-Machine-Learning   



## 📬 Contact
For questions, contact [kottusaikumar2003@gmail.com](mailto:kottusaikumar2003@gmail.com).
