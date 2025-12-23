# Student-Depression-Prediction-A-Safety-First-ML-Approach
# Student Depression Prediction: A Safety-First ML Approach

##  Overview
Mental health is a critical issue in academic environments. This project develops a Machine Learning solution to identify students at risk of depression using a dataset of **27,901 entries**. 

The core philosophy of this project is **"Clinical Recall"**: we prioritized minimizing False Negatives to ensure that at-risk students are not overlooked by the system.

## Key Results
- **Recall (Sensitivity):** 90.2% (Optimized for clinical safety)
- **AUC-ROC:** 0.917
- **Impact:** Identified **54 additional students** in distress compared to standard AI models by fine-tuning the decision threshold to **0.47**.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn, Optuna (for Hyperparameter tuning)
- **Model:** Random Forest (Ensemble Learning)

## Methodology
1. **Exploratory Data Analysis (EDA):** Identified 58.5% prevalence of depression in the cohort.
2. **Data Cleaning:** Treated outliers (Age > 50, CGPA 0) using **Winsorization**.
3. **Handling Imbalance:** Applied **Class Weights** to handle the majority class distribution.
4. **Optimization:** Threshold tuning using the Precision-Recall Curve to reach the >90% Recall clinical standard.

## Analysis of Predictors
The model identified the following as top predictors for depression:
1. **Suicidal Thoughts** (Highest importance)
2. **Academic Pressure**
3. **Financial Stress**
## 📧 Contact
**Coralia SHAN** - [LinkedIn](URL_DE_TON_LINKEDIN)
