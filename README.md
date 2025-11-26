Heart Disease Prediction Model

A Machine Learning project that predicts the likelihood of heart disease based on patient medical attributes. The goal of this project is to assist in early risk assessment using data-driven insights.

📊 Project Overview

This project uses a heart disease dataset containing clinical features such as age, sex, cholesterol levels, ECG results, chest pain type, blood pressure, and more.
After performing Exploratory Data Analysis (EDA) and preprocessing, a Logistic Regression model is trained to classify whether a patient has heart disease (1) or not (0).

🚀 Features

✔ Exploratory Data Analysis (EDA)

✔ Handling missing values

✔ Encoding categorical variables

✔ Feature scaling using StandardScaler

✔ Model training (Logistic Regression)

✔ Evaluation using Accuracy, Confusion Matrix, Classification Report

✔ Model saved as .pkl using joblib

✔ Gradio app for real-time predictions

🛠 Technologies Used
Component	Library
Data handling	Pandas, NumPy
Visualization	Matplotlib, Seaborn
ML Model	Scikit-learn
Model Saving	Joblib
Web App	Gradio
Notebook	Jupyter Notebook
📁 Project Structure
📦 Heart-Disease-Prediction
│
├── notebook.ipynb          # EDA + Model Training
├── model.pkl               # Saved trained model
├── scaler.pkl              # Saved StandardScaler
├── app.py                  # Gradio prediction app
├── dataset.csv             # Heart disease dataset (optional)
└── README.md               # Project documentation

🧠 Model Details

Algorithm: Logistic Regression

Target Variable: HeartDisease (0 = No, 1 = Yes)

Metrics Used:

Accuracy

Confusion Matrix

Precision, Recall, F1 Score

🖥 How to Run the Project
1. Clone the repository
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction

2. Install dependencies
pip install -r requirements.txt

3. Run the Gradio App
python app.py


Gradio will open a local web interface for predictions.

▶ Dataset Information

The dataset contains the following features:

Age

Sex

ChestPainType

RestingBP

Cholesterol

FastingBS

RestingECG

MaxHR

ExerciseAngina

Oldpeak

ST_Slope

HeartDisease (Target)

🎯 Objective

To create a reliable machine learning model that helps in early heart disease detection using patient clinical data.

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📜 License

This project is open-source and available under the MIT License.
