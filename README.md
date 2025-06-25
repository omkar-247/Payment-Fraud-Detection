# 🛡️ Payment Fraud Detection & Risk Scoring

This project simulates a real-world fraud detection system used by fintech and banking firms to proactively identify and score high-risk financial transactions using machine learning.

---

## 🚨 Problem Statement

Payment fraud costs companies billions annually. Detecting fraud early using behavioral transaction patterns is critical for preventing losses. This project builds an anomaly detection model to assign a **risk score** to each transaction and provides **interactive dashboards** for fraud analysts.

---

## 🎯 Objectives

- Detect risky or anomalous transactions using unsupervised learning
- Score each transaction with a binary risk score (1 = risky, 0 = safe)
- Build a Power BI dashboard for quick fraud investigation and reporting

---

## 🧰 Tech Stack

| Tool           | Purpose                         |
|----------------|----------------------------------|
| **Python**     | Data wrangling, modeling         |
| **Isolation Forest** | Anomaly detection algorithm |
| **Power BI**   | Dashboard for business insights |
| **Pandas / NumPy** | Data handling                |
| **Matplotlib / Seaborn** | Exploratory analysis   |

---

## 🧠 Key Features Engineered

- `NormAmount`: Scaled version of transaction amount
- `Hour`: Extracted from raw transaction time to analyze behavior by time of day
- `risk_score`: Predicted by Isolation Forest (1 = risky, 0 = safe)
- `Class`: Actual fraud label (used for evaluation only)

---

## 📊 Dashboard Highlights (Power BI)

- Total vs. risky transaction cards
- Pie chart showing safe vs. risky split
- Bar chart: risky transactions by hour
- Slicers for risk filtering and hourly patterns

![Dashboard Preview](https://github.com/omkar-247/Payment-Fraud-Detection/blob/main/Dashboard.png) <!-- Optional if you upload an image -->

---

## 📈 Model Results

- Used Isolation Forest to flag outliers based on behavioral features
- Achieved ~85% precision on known frauds using unsupervised scoring
- Found majority of risky transactions occurred during **1 AM – 5 AM**

---

## 🗂️ Dataset

- Source: [Credit Card Fraud Detection – Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Size: ~285,000 transactions
- Highly imbalanced: fraud accounts for ~0.17% of data

---

## 🧾 Files Included

| File                      | Description                               |
|---------------------------|-------------------------------------------|
| `fraud_scores.csv`        | Final dataset with risk_score & features  |
| `model_fraud_detection.ipynb` | Python notebook for modeling       |
| `dashboard.pbix`          | Power BI interactive dashboard file       |
| `README.md`               | This documentation                        |

---

## ✨ Author
Omkar | Data Analyst | [LinkedIn](https://www.linkedin.com/in/omkar-k-453037324/) |

