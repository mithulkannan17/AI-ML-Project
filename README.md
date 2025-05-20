#  Income Prediction Using Machine Learning

This project uses various machine learning models to predict whether an individual has high income based on attributes like age, education level, work hours, and experience.

---

##  Dataset

- **File**: `income_dataset.csv`
- **Features**:
  - `age`
  - `education_level`
  - `hours_per_week`
  - `experience_years`
- **Target**:
  - `high_income`: Binary value (1 = High Income, 0 = Not High Income)

---

##  Machine Learning Models Used

| Model                | Description                                      |
|---------------------|--------------------------------------------------|
| Linear Regression    | Used with threshold for binary classification    |
| Logistic Regression  | Predicts probability of high income              |
| K-Nearest Neighbors  | Classifies based on closest data points          |
| Naive Bayes          | Probabilistic model based on feature independence|
| Random Forest        | Ensemble model using decision trees              |

---

##  Model Performance

Model accuracy was evaluated using standard test/train split and accuracy metrics:

 ##  Models Applied & Accuracy

The following models were trained and evaluated. Accuracy scores were calculated using a standard 80/20 train-test split:

| Model                | Accuracy |
|---------------------|----------|
| Linear Regression    | 0.7575   |
| Logistic Regression  | 0.6700   |
| K-Nearest Neighbors  | 0.6600   |
| Naive Bayes          | 0.7500   |
| Random Forest        | 0.7500   |

 **Top Performers**:
- **Linear Regression** (used with threshold ≥ 0.5)
- **Random Forest**
- **Naive Bayes**

