# Titanic Survival Prediction – Exploratory Data Analysis & Modeling

## Overview
This project performs **Exploratory Data Analysis (EDA)** and builds predictive models on the Titanic dataset to determine which passengers were likely to survive the tragic event. The workflow covers data preprocessing, visualization, and model building using various machine learning algorithms.

The goal is to:
- Understand the patterns and relationships within the data.
- Identify key features affecting survival.
- Build and evaluate predictive models.

---

## Dataset
The dataset used in this project is the **Titanic Passenger Dataset**, typically available from [Kaggle](https://www.kaggle.com/c/titanic/data).  
It contains details for each passenger, including:
- **PassengerId** – Unique identifier
- **Pclass** – Ticket class (1 = First, 2 = Second, 3 = Third)
- **Name** – Passenger name
- **Sex** – Gender
- **Age** – Age in years
- **SibSp** – Number of siblings/spouses aboard
- **Parch** – Number of parents/children aboard
- **Ticket** – Ticket number
- **Fare** – Passenger fare
- **Cabin** – Cabin number
- **Embarked** – Port of embarkation
- **Survived** – Survival status (0 = No, 1 = Yes)

---

## 📊 Results
- **Logistic Regression**: Achieved baseline accuracy for classification.
- **Random Forest**: Improved accuracy due to its ability to capture non-linear patterns.
- **SVC**: Competitive performance depending on kernel choice.
  
Overall, the Random Forest Classifier achieved the highest accuracy among tested models.

---


## 🚀 How to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/titanic-eda-ml.git
   cd titanic-eda-ml

