📌**Project Overview**

This project predicts the likelihood of a patient having a stroke based on health records. Using a Random Forest Classifier, the model analyzes factors such as age, hypertension, heart disease, glucose level, BMI, and smoking status to determine stroke risk.

The project demonstrates the end-to-end Data Science workflow:

Data exploration & visualization

Data preprocessing & feature engineering

Machine learning model building

Model evaluation with multiple metrics

Insights from feature importance

📊 **Dataset**

Source: Healthcare Stroke Prediction Dataset

Rows: 5,110

Target Column: stroke (1 = stroke, 0 = no stroke)

Features:

age, gender, hypertension, heart_disease, ever_married

work_type, Residence_type, avg_glucose_level, bmi, smoking_status

⚙️ **Tech Stack**

Language: Python

Libraries:

Data Handling → pandas, numpy

Visualization → matplotlib, seaborn

Machine Learning → scikit-learn


🚀 **Steps to Run**

Clone the repository:

git clone https://github.com/<your-username>/stroke-prediction.git
cd stroke-prediction


Create and activate a virtual environment (recommended):

python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate # On Mac/Linux


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook Stroke_risk_factor.ipynb

📈 **Model Performance**

Evaluation Metrics Used:

Accuracy

Precision

Recall

F1 Score

ROC-AUC

🔍 **Insights**

Age and Average Glucose Level are the strongest predictors of stroke.

Patients with hypertension and heart disease have higher stroke risk.

Handling class imbalance is crucial since stroke cases are rare in the dataset.



👤 **Author**

Vedant Malpure
