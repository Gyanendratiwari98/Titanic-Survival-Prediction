# Titanic Survival Prediction — Logistic Regression & KNN

A comprehensive project using the Kaggle Titanic dataset to explore and compare classification models: **Logistic Regression** and **K-Nearest Neighbors (KNN)**.

---

##  Objective

Build and evaluate models to predict Titanic passenger survival using features such as:

- Passenger class (`Pclass`)
- Gender (`Sex`)
- Age (`Age`)
- Port of Embarkation (`Embarked`)
- Other engineered or selected features

---

##  Concepts & Techniques

- Models:
  - **Logistic Regression** (`sklearn.linear_model.LogisticRegression`)
  - **KNN** (`sklearn.neighbors.KNeighborsClassifier`)
- Data preprocessing:
  - Missing value handling (e.g., `Age`, `Embarked`)
  - Dropping irrelevant columns (`Name`, `Ticket`, `Cabin`)
  - Encoding categorical variables (`Sex`, `Embarked`)
  - Optional feature scaling for KNN (e.g., `StandardScaler`)
- Model evaluation:
  - Accuracy
  - Confusion matrix
  - Classification report (Precision, Recall, F1-score)

---

##  Dataset

- **Source**: Kaggle Titanic Dataset ([link](https://www.kaggle.com/c/titanic/data))  
- **File**: `train.csv` — place this in the project root before running notebooks.

---

##  Project Structure

```text
.
├── README.md
├── train.csv                                 # Titanic dataset (must be added)
├── titanic_logistic.ipynb                    # Logistic Regression notebook
├── titanic_logistic2.ipynb                   # Variant or extended pipeline
├── titanic_knn.ipynb                         # KNN classification notebook
└── Titanic Survival Prediction (Logistic Regression + KNN).ipynb
     Combined notebook comparing both models
