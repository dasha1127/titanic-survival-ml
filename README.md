# Titanic Survival Prediction 🚢

This project builds a **machine learning model** to predict whether a passenger survived the Titanic disaster using the classic Kaggle Titanic dataset.

The goal is to understand the **full end-to-end ML workflow**, including:
- data exploration
- handling missing values
- feature preprocessing
- model training
- model evaluation

---

## 📌 Problem Statement

Given passenger information such as age, sex, ticket class, fare, and port of embarkation,  
**predict whether a passenger survived (1) or did not survive (0).**

This is a **binary classification problem**.

---

## 📂 Dataset

Source: Kaggle Titanic Dataset

### Files used:
- `train.csv` – training data (includes target `Survived`)
- `test.csv` – test data (no target, used for predictions)

### Important columns:
| Column | Description |
|------|------------|
| PassengerId | Unique passenger ID |
| Survived | Target variable (0 = No, 1 = Yes) |
| Pclass | Ticket class (1, 2, 3) |
| Sex | Gender |
| Age | Age in years |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Fare | Ticket fare |
| Embarked | Port of embarkation |

---

## 🎯 Target and Features

### Target (y)
```text
Survived
