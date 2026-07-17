Churn Prediction Model

An end-to-end machine learning pipeline to analyze customer profiles and predict multi-class feedback categories (churn indicators) using a Random Forest Classifier.

 Project Overview
Processes customer profile data (`Churn.csv`), handles missing values, encodes categorical features, and evaluates an ensemble classification model.

 Setup & Installation
bash
# Clone the repository
git clone [https://github.com/RakshanaQ/Churn-predicton.git](https://github.com/RakshanaQ/Churn-predicton.git)
cd Churn-predicton

# Install dependencies
pip install numpy pandas seaborn matplotlib scikit-learn

Workflow
Preprocessing & Cleaning: Missing data imputation (region_category, points_in_wallet, etc.) and data type coercion.

Feature Engineering: LabelEncoder transformations for categorical features. Drops unneeded IDs (customer_id, security_no, etc.).

Training: 80/20 train-test split using a RandomForestClassifier.

 Baseline Performance
Model Accuracy: 0.20
