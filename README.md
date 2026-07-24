# 🩺 Diabetes Prediction using Logistic Regression

## 📌 Project Overview

This project predicts whether a patient is likely to have diabetes using the **Logistic Regression** classification algorithm.

The notebook demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

---

## 🎯 Objective

Develop a machine learning classification model that predicts diabetes based on patients' medical information.

---

## 📂 Dataset

**Dataset:** `diabetes.csv`

The dataset contains diagnostic measurements used to predict whether a patient has diabetes.

### Features

| Feature | Description |
|----------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree score |
| Age | Age of the patient |
| Outcome | Target Variable (0 = Non-Diabetic, 1 = Diabetic) |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

Performed the following analyses:

- Dataset overview
- Statistical summary
- Class distribution analysis
- Univariate Analysis
- Bivariate Analysis
- Pair Plot
- Correlation Heatmap
- Distribution plots
- Boxplots for outlier detection

---

## 🧹 Data Preprocessing

The preprocessing pipeline includes:

- Checking missing values
- Checking duplicate records
- Replacing invalid zero values with median values
- Feature scaling using **StandardScaler**
- Correlation analysis for feature selection

---

## 🤖 Machine Learning Model

### Algorithm

- Logistic Regression

### Train-Test Split

- Training Data: 70%
- Testing Data: 30%

---

## 📈 Model Evaluation

The model was evaluated using multiple classification metrics.

| Metric | Score |
|---------|-------|
| Accuracy | **75.32%** |
| Precision | **67.27%** |
| Recall | **48.68%** |
| F1 Score | **56.49%** |
| ROC-AUC Score | **0.6854** |

Confusion Matrix and Classification Report were also generated for detailed performance analysis.

---

## 📁 Project Structure

```
logistic_regression_ML_Project_2/
│
├── Logistic_Regression.ipynb
├── diabetes.csv
├── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-github-username/logistic_regression_ML_Project_2.git
```

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Open the notebook

```
Logistic_Regression.ipynb
```

### 4. Run all cells

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Feature Scaling
- Logistic Regression
- Classification
- Model Evaluation
- ROC Curve Analysis
- Confusion Matrix Interpretation

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Compare with Decision Tree, Random Forest, and SVM
- Deploy the model using Flask or Streamlit
- Build an interactive web application

---

## 👨‍💻 Author

**Gagan B T**

Computer Science Engineering Student

GitHub: https://github.com/Gaganbt03

---

⭐ If you found this project useful, consider giving it a star!
