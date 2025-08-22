
# Sleep Disorder Prediction Using Machine Learning
## Discription
This project aims to predict sleep disorders such as Insomnia, Sleep Apnea, or None using machine learning models trained on lifestyle and health-related data.
The dataset includes features such as Age, Gender, Occupation, BMI, Stress Level, Sleep Duration, Heart Rate, and Blood Pressure.

By analyzing these factors, we use Exploratory Data Analysis (EDA) and multiple ML algorithms (Logistic Regression, Decision Tree, Random Forest, XGBoost) to build prediction models.
## Problem solution
To achieve the project's goal, a classifier will be constructed to predict the presence of a sleep disorder based on various columns in the dataset.

## Project Structure
- Sleep_health_and_lifestyle_dataset.csv: The main dataset file.
- sleep2.ipynb:Jupyter Notebook containing the data analysis code.

## Dataset
The dataset used is: Sleep_health_and_lifestyle_dataset.csv
Key Features:

- Gender
- Age
- Occupation
- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- BMI Category
- Blood Pressure (Systolic/Diastolic)
- Heart Rate
- Daily Steps
- Sleep Disorder (Target Variable)

## Project Workflow
1. Load Dataset – Import the CSV file containing sleep and lifestyle data.
Data Cleaning – Remove unnecessary columns, handle missing values, and split blood pressure into systolic/diastolic.

2. Data Visualization (EDA) – Create graphs and charts to understand patterns in stress, sleep duration, occupation, etc.

3. Feature Encoding – Convert categorical data (like Gender, Occupation, BMI Category) into numeric format.

4. Model Training – Train different ML models: Logistic Regression, Decision Tree, Random Forest, XGBoost.

5. Model Evaluation – Check accuracy and classification reports to compare models.

6. Results – Random Forest & XGBoost give better predictions.

7. Future Work – Improve with tuning, and deploy as a web app using Streamlit/Flask.

## Exploratory Data Analysis (EDA)

- Distribution of Sleep Disorders (Bar & Pie Charts)
- Gender, Occupation, and BMI Analysis
- Stress Level comparison by Gender
- Daily Steps variation across Occupations
- Blood Pressure trends with Age
- Outlier Detection using IQR
- Correlation Heatmap of Features

📊 Visualizations were done using Matplotlib, Seaborn, and Plotly.

## 🤖 Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

📌 Evaluation Metrics:

- Accuracy
- Classification Report (Precision, Recall, F1-Score)

## 📦 Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- plotly
- scikit-learn
- xgboost


## Installation

1️⃣ Install Dependencies

```bash
  pip install -r requirements.txt
```

2️⃣ Run the Code

```bash
  python sleep_disorder_prediction.py
```
    