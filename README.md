# Titanic Survival Prediction 🚢

This project uses the **Titanic dataset** to predict whether a passenger survived the disaster using **Exploratory Data Analysis (EDA)** and a **Decision Tree Classifier**.

---

## 📌 Project Overview
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  
This project analyzes passenger data and builds a machine learning model to predict survival based on features such as gender, age, passenger class, and fare.

---

## 📂 Dataset
- Source: Kaggle Titanic Dataset
- Files used:
  - `tested.csv`

### Key Features
- `Survived` (Target Variable)
- `Pclass`
- `Sex`
- `Age`
- `SibSp`
- `Parch`
- `Fare`
- `Embarked`

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to understand:
- Survival distribution
- Impact of gender, class, age, and fare on survival
- Missing values and data quality issues

### Key Insights
- Females had a much higher survival rate than males
- 1st class passengers survived more than 3rd class
- Higher fare correlated with higher survival chances
- Age and family size influenced survival probability

---

## 🛠 Data Preprocessing
- Missing values handled:
  - `Age`: filled with median
  - `Embarked`: filled with mode
  - `Cabin`: dropped
- Categorical variables encoded using **One-Hot Encoding**
- Features scaled implicitly (not required for Decision Tree)

---

## 🌲 Model Used
**Decision Tree Classifier**
- Criterion: Gini
- Max Depth: 5
- Train-test split: 80% / 20%

---

## 📈 Model Performance
- Accuracy: ~1.0%
- Model evaluation using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## 🧰 Libraries Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-decision-tree.git
