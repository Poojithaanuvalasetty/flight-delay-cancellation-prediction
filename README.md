# flight-delay-cancellation-prediction
Analyzing and predicting flight delays and cancellations using PySpark and machine learning

# ✈️ Flight Delay & Cancellation Prediction

This project analyzes 3+ million flight records to identify patterns and build models to predict delays and cancellations in the Washington, DC area using PySpark and Databricks.

---

## 🎯 Objectives
- Identify high-risk time periods and airlines for delays/cancellations
- Build predictive models using Spark MLlib for classification

---

## 📦 Dataset
- [Kaggle: Flight Delay and Cancellation Dataset (2019–2023)](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023)  
- Includes 3M+ records, 79,000+ flights originating from DC airports

---

## 🛠️ Tools & Stack
- **Databricks (DBFS)**  
- **PySpark** for data wrangling and EDA  
- **Spark MLlib** for modeling  
- **Visualization** using PySpark + Databricks notebooks

---

## 📊 Key Findings (Exploratory Analysis)
- **Most delayed airline:** Allegiant Air (50.9%)  
- **Best on-time performance:** Endeavor Air (17.9% delays)  
- **Most delays by hour:** 2 PM–12 AM (33–39%)  
- **Season with most delays:** Summer (34.2%)  
- **Most cancellations:** Mornings; top city = New York

---

## 🧠 Model Results
| Model                | Cancellation Accuracy | Delay Accuracy |
|----------------------|-----------------------|----------------|
| Random Forest        | 0.95                  | 0.69           |
| XGBoost              | 0.94                  | 0.68           |
| Gradient Boosting    | 0.92                  | 0.66           |
| Logistic Regression  | 0.73                  | 0.64           |
| ANN (MLP)            | 0.62                  | 0.54           |

> Best performance for cancellation: Random Forest (95%)  
> Delay prediction moderately accurate (~68–69%)

---

## 📄 Report
[📑 Final Project Report (PDF)](./Flight%20Delay%20and%20Cancellation%20Prediction.pdf)

---

## 🔗 Portfolio Link
[View full write-up ➜](https://www.notion.so/SELECT-FROM-Poojitha-1fb0edb9699f80279cf7e15926b7a349?pvs=4)
