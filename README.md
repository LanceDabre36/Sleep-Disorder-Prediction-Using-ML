# Sleep-Disorder-Prediction-Using-ML
📌 Overview

This project aims to predict sleep disorders such as Insomnia, Sleep Apnea, or None using machine learning models trained on lifestyle and health-related data.
The dataset includes features such as Age, Gender, Occupation, BMI, Stress Level, Sleep Duration, Heart Rate, and Blood Pressure.

By analyzing these factors, we use Exploratory Data Analysis (EDA) and multiple ML algorithms (Logistic Regression, Decision Tree, Random Forest, XGBoost) to build prediction models.

📊 Dataset

The dataset used is: Sleep_health_and_lifestyle_dataset.csv
Key Features:

Gender

Age

Occupation

Sleep Duration

Quality of Sleep

Physical Activity Level

Stress Level

BMI Category

Blood Pressure (Systolic/Diastolic)

Heart Rate

Daily Steps

Sleep Disorder (Target Variable)

🔍 Exploratory Data Analysis (EDA)

Distribution of Sleep Disorders (Bar & Pie Charts)

Gender, Occupation, and BMI Analysis

Stress Level comparison by Gender

Daily Steps variation across Occupations

Blood Pressure trends with Age

Outlier Detection using IQR

Correlation Heatmap of Features

📊 Visualizations were done using Matplotlib, Seaborn, and Plotly.

⚙️ Data Preprocessing

Removed irrelevant column: Person ID

Handled missing values in Sleep Disorder (replaced with "None")

Converted Blood Pressure into Systolic and Diastolic

One-Hot Encoding for categorical features (Gender, Occupation, BMI Category)

Label Encoding for target variable (Sleep Disorder)

🤖 Machine Learning Models

We trained and evaluated multiple ML models:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

📌 Evaluation Metrics:

Accuracy

Classification Report (Precision, Recall, F1-Score)

🏆 Results

Random Forest & XGBoost performed better compared to Logistic Regression.

Feature Importance showed that Sleep Duration, Stress Level, and BMI were highly correlated with sleep disorders.

🚀 Installation & Usage
1️⃣ Clone the Repository
git clone https://github.com/your-username/Sleep-Disorder-Prediction-Using-ML.git
cd Sleep-Disorder-Prediction-Using-ML

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Code
python sleep_disorder_prediction.py

📦 Requirements

Python 3.x

numpy

pandas

matplotlib

seaborn

plotly

scikit-learn

xgboost

(You can create a requirements.txt file with the above libraries.)

📌 Future Enhancements

Deploy the model using Streamlit / Flask for interactive predictions.

Improve model performance with Hyperparameter Tuning.

Try Deep Learning approaches (ANN, LSTM).