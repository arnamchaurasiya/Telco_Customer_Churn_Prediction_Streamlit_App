# Telco Customer Churn Prediction Streamlit App

[![Live Application](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://telcocustomerchurnpredictionappapp.streamlit.app/)

## Overview
This Streamlit web application predicts whether a telecommunications customer is likely to churn (leave the service) based on their demographics, provided services, and account details. It allows users to dynamically select models like XGBoost, CatBoost, and LightGBM to provide real-time churn predictions.

### Features
- **Real-Time Predictions**: Use the sidebar to input a customer's specific data points and instantly see the prediction.
- **Multiple Classifiers**: Quickly compare predictions between XGBoost, CatBoost, and LightGBM.
- **Data Overview**: Review basic dataset metrics and feature correlations.

---

## Installation & Running Locally

1. **Clone the repository:**
```bash
git clone https://github.com/arnamchaurasiya/Telco_Customer_Churn_Prediction_Streamlit_App.git
cd Telco_Customer_Churn_Prediction_Streamlit_App
```

2. **Install requirements:**
```bash
pip install -r requirements.txt
```

3. **Run the application:**
```bash
streamlit run app.py
```

---

## Dataset
The application utilizes the **Telco Customer Churn** dataset. 
- [Kaggle Dataset URL](https://www.kaggle.com/blastchar/telco-customer-churn)
- [IBM GitHub Dataset URL](https://github.com/IBM/telco-customer-churn-on-icp4d/tree/master/data)
