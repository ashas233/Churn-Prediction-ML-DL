Churn Prediction using ML & DL

Overview
Predict customer churn for a telecom company using the Telco Customer Churn dataset (7,043 rows, 20 features, binary churn label).

Technologies
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · Joblib · TensorFlow/Keras · Google Colab

Data Preprocessing

Renamed columns → snake_case

Handled missing values & duplicates

Mapped service columns to binary (e.g., No internet service → No)

Encoded target: Churn → 1/0

Split numeric vs. categorical features

EDA

Churn distribution

Histograms (numeric)

Bar plots (categorical vs. churn)

Modeling (Planned)
Preprocessing pipeline with ColumnTransformer, SimpleImputer, OneHotEncoder, StandardScaler
Models: Logistic Regression · Random Forest · XGBoost · Neural Network (Keras)

Next Steps

Train models & compare results

Report metrics (Accuracy, Precision, Recall, F1, AUC)

How to Run

Upload dataset to Colab

Run notebook cells sequentially

Train & evaluate models
