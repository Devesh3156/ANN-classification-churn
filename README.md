### ANN-classification-churn
# Overview

This project predicts whether a bank customer is likely to churn using an Artificial Neural Network (ANN) built with TensorFlow and Keras. The model is trained on customer demographic and banking information and deployed as an interactive Streamlit web application, allowing users to input customer details and receive real-time churn predictions.

The project demonstrates a complete end-to-end machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and deployment.

#Features
Predicts customer churn probability in real time.
Interactive web interface built with Streamlit.
Data preprocessing using Label Encoding, One-Hot Encoding, and Standard Scaling.
ANN model implemented using TensorFlow/Keras.
Early Stopping to prevent overfitting.
TensorBoard integration for monitoring training performance.
Model and preprocessing objects saved using Pickle for deployment.
Technologies Used
Python
TensorFlow & Keras
Streamlit
Scikit-learn
Pandas
NumPy
Matplotlib
TensorBoard
Pickle
Dataset

# The project uses the Churn Modelling Dataset, which contains customer information such as:

Credit Score
Geography
Gender
Age
Tenure
Balance
Number of Products
Has Credit Card
Is Active Member
Estimated Salary

The target variable is:

Exited (0 = Customer Stays, 1 = Customer Churns)
Machine Learning Workflow
Data Cleaning and Exploration
Feature Encoding
Label Encoding (Gender)
One-Hot Encoding (Geography)
Feature Scaling using StandardScaler
Train-Test Split
ANN Model Development
Model Training with Early Stopping
Model Evaluation
Model Deployment using Streamlit
# Project Structure
├── app.py
├── model.h5
├── scalar.pkl
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── Churn_Modelling.csv
├── requirements.txt
├── prediction.ipynb
├── experiments.ipynb
└── README.md
Installation

# Clone the repository:

git clone <repository-url>
cd <repository-folder>

# Create a virtual environment:

python -m venv venv

# 
Activate the environment:

Windows

venv\Scripts\activate

# Install dependencies:

pip install -r requirements.txt

# Run the Streamlit application:

python -m streamlit run app.py
Model Output

# The application returns:

Customer churn probability (in percentage)
Final prediction indicating whether the customer is likely to churn
Future Improvements
Hyperparameter tuning
Cross-validation
Explainable AI using SHAP or LIME
Docker deployment
Cloud deployment (AWS, Azure, or Render)
REST API using FastAPI

# Author

Devesh 

If you found this project useful, consider giving it a ⭐ on GitHub.
