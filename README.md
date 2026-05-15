# 🏦 Credit Risk Model

A machine learning project that predicts credit risk using classification models and interactive visualizations.  
Deployed as a Streamlit web app: [Credit Risk Model App](https://credit-risk-model-avengers.streamlit.app/)

---

## 📌 Project Overview
Credit risk assessment is a critical task in the financial industry. This project leverages machine learning techniques to classify loan applicants into **low-risk** and **high-risk** categories based on their financial and demographic attributes.

The app provides:
- 📊 **Interactive dashboard** for exploring data and predictions  
- 🤖 **Machine learning models** (Logistic Regression, Random Forest, XGBoost, etc.)  
- ⚡ **Real-time predictions** via a user-friendly Streamlit interface  

---

## 🚀 Features
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales numerical features.  
- **Model Training**: Implements multiple ML algorithms with hyperparameter tuning.  
- **Evaluation Metrics**: Accuracy, ROC-AUC, Precision, Recall, and F1-score.  
- **Deployment**: Streamlit app for interactive exploration and prediction.  

---

## 🛠️ Tech Stack
- **Python 3.11**  
- **Libraries**:  
  - `numpy`, `pandas` for data handling  
  - `scikit-learn` for ML models and evaluation  
  - `xgboost` for gradient boosting  
  - `streamlit` for deployment  
  - `joblib` for model persistence  

---

## 📂 Repository Structure
Credit-Risk-Model/
│
├── main.py                # Streamlit app entry point
├── prediction_helper.py   # Helper functions for predictions
├── requirements.txt       # Project dependencies
├── runtime.txt            # Python version specification
├── artifacts/             # Saved models and outputs
├── README.md              # Project documentation
└── .gitignore


---

## 📸 Dashboard Preview


<img width="1916" height="972" alt="image" src="https://github.com/user-attachments/assets/548bdec3-d5c9-4990-a395-9a7c6a45a669" />


---

## ⚡ How to Run Locally
1. Clone the repository:
   git clone https://github.com/manish-athith/Credit-Risk-Model.git
   cd Credit-Risk-Model
   
3. Create and activate a virtual environment (Python 3.11):
   py -3.11 -m venv .venv
   .venv\Scripts\activate
   
3.Install dependencies:
  pip install -r requirements.txt
  
4.Run the Streamlit app:
  streamlit run main.py

📈 Future Improvements
Add more advanced models (LightGBM, CatBoost).

Integrate SHAP/feature importance for explainability.

Enhance UI with more interactive charts.

Deploy with CI/CD pipeline for automated updates.

👨‍💻 Author
Manish Choudhary  
Machine Learning & Data Science Enthusiast





