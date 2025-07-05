# Heart-Disease-Prediction System
Developed an intelligent web-based system to predict the likelihood of heart disease in patients based on clinical input parameters such as age, blood pressure, cholesterol levels, and more. The system leverages machine learning models for binary classification using techniques like Logistic Regression, Decision Trees, and Random Forest. Performed data preprocessing, feature selection, and model evaluation (accuracy, F1-score, ROC-AUC). Integrated the ML model into a user-friendly interface for real-time predictions.

heart_disease_prediction/
│
├── heart.csv
├── model_training.py         # New: trains and saves model
├── app.py                    # Optional Flask API
├── streamlit_app.py          # Streamlit UI (you already have)
├── heart_model.pkl           # Auto-created by model_training.py
├── scaler.pkl                # Auto-created by model_training.py
├── requirements.txt
└── README.md

## Language Used:
•	Language: Python
•	ML Libraries: Pandas, NumPy, Matplotlib/Seaborn, Scikit-learn
•	Model: Logistic Regression / Random Forest / XGBoost
•	Deployment: Flask 
•	Frontendl: Streamlit/HTML 

### Highlights:
- Achieved over 85% prediction accuracy on test data
- Built using Flask/FastAPI for model deployment
- Designed an interactive web UI for user input and live prediction
- Conducted EDA and visualized insights using Matplotlib & Seaborn
