# ML_Project_Healthcare_Premium_Prediction
This machine learning project aims to predict health insurance premium amounts based on user demographic, medical, and lifestyle features. The project is designed to assist insurance providers in accurately pricing policies using data-driven insights.
<img width="905" height="762" alt="image" src="https://github.com/user-attachments/assets/b1dc781a-167f-4abe-afee-207114f7566d" />
Overview

This project predicts the healthcare insurance premium for individuals based on demographic, lifestyle, and medical features. The goal is to assist insurance companies in pricing policies accurately and fairly.

Dataset

Features include: age, bmi, smoking_status, region, pre_existing_conditions, etc.

Target: insurance_premium (continuous value).

Approach

Data Preprocessing: Handle missing values, encode categorical variables, scale numeric features.

Models Used: Linear Regression, XGBoost.

Evaluation Metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), R² score.

Cross-Validation: K-Fold CV to ensure model generalization.

Usage

Clone the repository:

git clone <repo-url>


Install dependencies:

pip install -r requirements.txt


Run the notebook or script to train and evaluate models.

Key Insights

Age, BMI, and smoking status are major factors affecting premiums.

Tree-based models (Random Forest, Gradient Boosting) outperform linear regression in predictive accuracy.

Feature importance helps identify key contributors to premium pricing.

Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
