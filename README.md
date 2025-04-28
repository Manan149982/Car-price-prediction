# Car-price-prediction
Predicting the price of a car based on various features such as make, model, year, mileage, fuel type, etc.
This project uses machine learning algorithms to build a predictive model and analyze the key factors influencing car prices.

📂 Project Structure
kotlin
Copy
Edit
car-price-prediction/
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── notebooks/
│   └── car_price_prediction.ipynb
├── models/
│   └── model.pkl
├── app/
│   └── app.py
├── requirements.txt
├── README.md
└── LICENSE
🛠️ Tech Stack
Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-Learn

Streamlit (for deployment)

Jupyter Notebook

📈 Problem Statement
Build a machine learning model that can predict the price of a used car based on its features like:

Brand

Model

Year

Mileage

Fuel Type

Transmission

Engine Size

Number of Previous Owners, etc.

📊 Dataset
Source: [Kaggle / custom dataset]

Rows: 10,000+

Features: 10–15 columns

Dataset is available inside the data/ folder (raw_data.csv).

🧹 Data Preprocessing
Handling missing values

Encoding categorical variables

Outlier detection and removal

Feature scaling

🤖 Model Building
Train-Test Split

Feature Selection

Models Used:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Hyperparameter Tuning

Evaluation Metrics:

RMSE (Root Mean Squared Error)

R² Score
