# British Airways Data Science Job Simulation (Forage)

🚀 **Project Title:** Predicting Customer Booking Behavior

📅 **Completion Date:** May 30, 2025  
🎓 **Program:** Forage x British Airways Data Science Job Simulation  
📍 **Author:** Anthony Eddei Kwofie

---

## 🧠 Objective

The goal of this project is to predict the likelihood of a customer completing a flight booking, using historical booking data from British Airways.

---

## 📊 Dataset Summary

- Source: Simulated customer booking data from Forage
- Key fields: `purchase_lead`, `flight_duration`, `booking_origin`, `length_of_stay`, etc.
- Class Imbalance: Only ~15% of records were positive bookings

---

## ⚙️ Workflow

1. **Data Cleaning & Preprocessing**
   - One-hot encoding of categorical variables
   - Train-test split (80/20)
   - SMOTE applied to handle class imbalance

2. **Modeling**
   - Model: Random Forest Classifier
   - Reason: High interpretability, handles mixed data types well

3. **Evaluation**
   - Accuracy: 84%
   - Precision: 0.45 | Recall: 0.23 | F1 Score: 0.30
   - Confusion matrix and feature importance charts included

---

## 🔍 Insights

- Passengers from Malaysia had a higher booking rate
- Early purchases and longer stays correlated with successful bookings

---

## 📈 Visualizations

- Confusion Matrix
- Feature Importance Chart

---

## ✅ Recommendations

- Explore alternative models (XGBoost, Logistic Regression)
- Improve class balance techniques
- Tune hyperparameters and prediction threshold

---

## 🛠️ Tools Used

- Python (Pandas, Scikit-learn, Imbalanced-learn)
- Jupyter Notebook
- Matplotlib & Seaborn

---

## 📁 Repository Contents

| Folder | Description |
|--------|-------------|
| `notebooks/` | Data preprocessing, modeling code |
| `plots/` | Evaluation visualizations |
| `presentation/` | Summary slides |
| `requirements.txt` | Python packages used |

---

## 📬 Contact

**Anthony Eddei Kwofie**  
📧 tonyjnr1990@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)  
