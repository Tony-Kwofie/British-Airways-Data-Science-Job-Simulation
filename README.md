# British Airways Data Science Job Simulation (Forage)

🚀 **Project:** Predicting Flight Booking Behavior  
📅 **Completed:** May 30, 2025  
👤 **Author:** Anthony Eddei Kwofie  
📚 **Program:** British Airways x Forage Job Simulation

---

## 📌 Objective

Build a classification model to predict whether a customer will complete a flight booking using British Airways' historical customer data.

---

## 🔍 Dataset Overview

- Simulated data from Forage
- Target: `booking_complete` (binary)
- Key Features: `purchase_lead`, `flight_duration`, `length_of_stay`, `booking_origin`
- Notable issue: Class imbalance (~15% positive class)

---

## ⚙️ Approach

1. **Preprocessing:**
   - Categorical encoding
   - Outlier detection
   - Feature scaling (if applicable)
2. **Balancing:**
   - Applied SMOTE for balanced training data
3. **Modeling:**
   - Algorithm: Random Forest Classifier
   - Training/Test Split: 80/20
4. **Evaluation Metrics:**
   - Accuracy: 84%
   - Recall: 23%
   - F1 Score: 0.30

---

## 📊 Visuals

- ✅ Confusion Matrix
- ✅ Feature Importance Plot

Visuals stored in the `/plots/` directory.

---

## 🧠 Key Findings

- **Booking Origin (e.g. Malaysia)** is a strong predictor of conversion.
- Longer stays and early purchases increase booking likelihood.
- Class imbalance significantly impacts recall.

---

## ✅ Recommendations

- Explore alternative models: XGBoost, Logistic Regression
- Tune model threshold for business-oriented recall
- Consider richer feature engineering (e.g. temporal trends)

---

## 💻 Tools Used

- Python (Jupyter Notebook)
- Scikit-learn, Pandas, Matplotlib, Seaborn
- imbalanced-learn (SMOTE)

---

## 📁 Repository Structure

| Folder        | Description                          |
|---------------|--------------------------------------|
| `notebooks/`  | Jupyter Notebook with full workflow  |
| `plots/`      | Model evaluation visualizations      |
| `presentation/` | Summary slide for stakeholder review |
| `data/`       | Data description or access info      |
| `README.md`   | Project overview                     |
| `requirements.txt` | List of dependencies            |

---

## 📬 Contact

**Anthony Eddei Kwofie**  
📧 tonyjnr1990@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)
