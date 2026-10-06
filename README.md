# E-Commerce Fraud Detection using Machine Learning

## Overview
This project is a web-based machine learning application designed to detect fraudulent e-commerce transactions. It features a user-friendly interface where users can upload transaction data or manually input details to instantly predict whether a transaction is legitimate or fraudulent. 

## Key Features
* **Machine Learning Models:** Utilizes advanced classification models, including `XGBClassifier` and `StackingClassifier`, for high-accuracy predictions.
* **Batch Processing:** Allows users to upload CSV files containing multiple transactions for automated batch prediction.
* **Real-time Prediction:** Features a clean web form to input individual transaction details (amount, payment method, customer age, device used, etc.) for instant fraud evaluation.
* **Interactive UI:** Built with HTML/CSS and integrated with a Python backend for seamless navigation between Home, Upload, Prediction, and Performance metrics.

## Tech Stack
* **Backend:** Python, Flask
* **Machine Learning:** Scikit-Learn, XGBoost, Pandas
* **Frontend:** HTML, CSS, Bootstrap

## How to Run the Project
1. Clone the repository:
   `git clone https://github.com/sagar-rameshb/E-Commerce-Fraud-Detection-ML.git`
2. Navigate to the project directory:
   `cd "SOURCE CODE/E-Commerce Fraud"`
3. Install the required dependencies:
   `pip install -r requirements.txt`
4. Run the Flask application:
   `python app.py`
5. Open your web browser and go to `http://localhost:5000`.
