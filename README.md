# 🚢 Titanic Survival Prediction

![Docker Pulls](https://img.shields.io/docker/pulls/cekim63/titanic-app?style=flat-square&logo=docker)

## 🎯 Project Goal
Predicting which passengers survived the Titanic shipwreck using Machine Learning.
**Accuracy achieved: ~75.8%**

## 🛠 Tech Stack
* **Python**
* **Pandas** (Data Cleaning & Feature Engineering)
* **Scikit-Learn** (Random Forest Classifier)
* **Matplotlib** (Feature Importance Visualization)
* **Docker** (Containerization & Deployment)

## 🧠 Key Insights
1. **Data Cleaning:** Imputed missing age values using the average age.
2. **Feature Engineering:** Converted categorical data (Sex, Embarked) into numerical values.
3. **Model Finding:** The most important factor for survival was the **Ticket Price (Fare)**, followed by **Gender**.

## 🚀 How to use

### Option 1: Run via Docker (Recommended 🐳)
You don't need to install Python or Pandas. If you have Docker installed, just run this command in your terminal to see the model in action:

```bash
docker run cekim63/titanic-app
