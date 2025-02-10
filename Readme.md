# Customer Churn Prediction App

This is a Streamlit application designed to predict customer churn using a pre-trained Artificial Neural Network (ANN) model. The app takes user inputs, preprocesses them, and provides the probability of a customer churning.

## Overview

The application uses a trained ANN model (`model.h5`) along with pre-trained encoders and scalers to make predictions on whether a customer is likely to churn based on their demographic and financial information.

### Key Features:
- **User Input**: Users can input various customer attributes such as Geography, Gender, Age, Balance, Credit Score, etc.
- **Preprocessing**: The app handles encoding of categorical variables (e.g., Gender and Geography) and scaling of numerical features.
- **Prediction**: The app predicts the probability of churn and displays whether the customer is likely to churn or not.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/customer-churn-prediction.git
   cd customer-churn-prediction

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt


3. **Usage**:
   ```bash
   streamlit run app.py