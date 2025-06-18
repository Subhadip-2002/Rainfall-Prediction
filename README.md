🌧️ Rainfall Prediction Using Machine Learning
This project focuses on predicting whether it will rain tomorrow based on historical weather data using various machine learning algorithms. It includes data preprocessing, imputation, model training, evaluation, and comparison.

📂 Project Structure
Rainfall Prediction.ipynb: Main Jupyter Notebook with complete implementation

README.md: Project overview and instructions

📊 Dataset
The dataset contains daily weather observations such as:

Sunshine

Humidity at 9am

Cloud cover at 3pm

Temperature, wind, and pressure metrics

Target: RainTomorrow (Yes/No)

Note: Data imputation is handled using Multiple Imputation by Chained Equations (MICE).

🧰 Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn

LightGBM, CatBoost, XGBoost

MLxtend (for ensemble and visualization)

✅ Models Implemented
Model	Status
Logistic Regression	✅
Decision Tree	✅
Neural Network (MLP)	✅
Random Forest	✅
LightGBM	✅
CatBoost	✅
XGBoost	✅
Ensemble Voting	✅ (soft voting using top models)

📈 Evaluation Metrics
Accuracy

ROC AUC

Cohen's Kappa

Execution Time

📊 Visualizations
ROC Curve

Confusion Matrix

Model Comparison Bar Charts

Decision Regions (for top 3 features)
