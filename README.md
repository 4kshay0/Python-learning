# 🩺 Machine Learning for Early-Stage Diabetes Risk Prediction

An exploratory data analysis and classification pipeline built in Python to predict diabetes diagnosis risk based on clinical patient attributes.

---

## 📊 Executive Summary
Using patient health data from 768 individuals, this project trains a **Random Forest Classifier** to evaluate risk factors associated with diabetes onset. The model achieves an overall accuracy of 72.08%

### Key Findings:
- **Primary Predictor:** `Glucose` level is the single strongest indicator of diabetes risk according to feature importance scoring.
- **Secondary Predictor:** `BMI` (Body Mass Index) acts as the second most dominant physical metric.
- **Actionable Insight:** Interventions targeting glucose control and body composition yield the highest clinical predictive value compared to age or insulin levels alone.

---

## 🛠️ Tech Stack & Methods
- **Language:** Python 3 (Google Colab Environment)
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (Random Forest Classifier, Train-Test Split, Feature Importance Analysis)

---

## 📈 Model Performance & Methodology

1. **Preprocessing:** Split data 80/20 into training and validation sets (`random_state=42`).
2. **Model Training:** Trained a Random Forest ensemble (`n_estimators=100`).
3. **Evaluation:** Generated precision, recall, and feature importance matrices to isolate key risk drivers.

---

## 🚀 How to Run in Google Colab
You can run this notebook directly in your browser without local installation:
1. Open the `.ipynb` notebook file in this repository.
2. Click **"Open in Colab"** at the top.
3. Select `Runtime` ➔ `Run all`.




