# AI-Powered Insider Threat Detection

## Overview
  The AI-Powered Insider Threat Detection system is a machine-learning-based cybersecurity application designed to identify potential insider threats by analyzing user behavior within an enterprise environment.

The system analyzes activities such as login behavior, USB usage, and sensitive file access to identify patterns that may indicate security risks.

It uses machine learning models such as Random Forest and XGBoost to analyze the available behavioral data and generate risk predictions. An interactive Streamlit dashboard provides a user-friendly interface for viewing security insights, risk scores, and data visualizations.

The project also includes an AI-powered security assistant/chatbot to help users understand detected risks and security-related information.

## Key Features
🛡️ Insider Threat Detection
Analyzes user behavior to identify potential security risks.
🤖 Machine Learning-Based Detection
Uses Random Forest and XGBoost models for threat classification and risk analysis.
📊 Behavioral Analysis
Processes user activity such as login times, USB usage, and sensitive file access.
📈 Interactive Dashboard
Provides an interactive Streamlit dashboard for displaying security analytics and risk information.
📉 Data Visualization
Uses Plotly to visualize behavioral patterns and security-related metrics.
🤖 AI Security Assistant
Provides an interactive chatbot/assistant to help explain security insights and detected risks.
📋 Model Evaluation
Evaluates model performance using metrics such as precision, recall, and confusion matrices.

## Technologies Used
Programming Language
Python
Machine Learning
Scikit-learn
Random Forest
XGBoost
Data Processing
Pandas
Visualization
Plotly
Web Application
Streamlit
Development Tools
Git
GitHub

## Machine Learning Models
The project uses two machine learning approaches for insider-threat detection:

Random Forest

Random Forest is used to analyze behavioral features and classify potential security risks. It combines multiple decision trees to produce a prediction.

XGBoost

XGBoost is another machine learning model used for threat detection and performance comparison.

Model Comparison

The project compares the performance of Random Forest and XGBoost using evaluation metrics such as:

Accuracy
Precision
Recall
Confusion Matrix

This comparison helps evaluate how effectively the models identify potential insider threats.

## Project Architecture
AI-Powered-Insider-Threat-Detection/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│   └── trained models
│
├── src/
│   ├── preprocess.py
│   ├── train_model.py
│   └── evaluate.py
│
├── dashboard/
│   └── app.py
│
├── requirements.txt
│
└── README.md
Directory Description
data/ – Contains the project datasets and processed data.
models/ – Contains trained machine learning models.
src/ – Contains preprocessing, training, and evaluation scripts.
dashboard/ – Contains the Streamlit dashboard application.
requirements.txt – Contains the Python dependencies required to run the project.
README.md – Project documentation.

## How It Works
The system follows a machine-learning-based workflow:

1. Data Collection

The system uses user activity data containing behavioral information such as login activity, USB usage, and sensitive file access.

2. Data Preprocessing

The raw data is cleaned and prepared for machine learning. Relevant features are processed so that they can be used by the detection models.

3. Model Training

The processed data is used to train the Random Forest and XGBoost models.

4. Threat Prediction

The selected model analyzes user behavior and generates a prediction/risk score.

5. Risk Analysis

The system identifies potentially risky behavior based on the model's output.

6. Dashboard Visualization

The Streamlit dashboard presents the results through interactive visualizations and security metrics.

7. Security Assistant

The integrated AI security assistant helps users understand the detected security risks and related information.

## Installation
1. Clone the repository
   git clone https://github.com/KongaraUday/AI-Powered-Insider-Threat-Detection.git
2. Navigate to the project directory
   cd AI-Powered-Insider-Threat-Detection
3. Create a virtual environment
   python -m venv venv
4. Activate the virtual environment windows:
   venv\Scripts\activate
Linux/macOS:
source venv/bin/activate
5. Install dependencies
   pip install -r requirements.txt


## How to Run
Step 1: Preprocess the data
 python src/preprocess.py
Step 2: Train the machine learning models
python src/train_model.py
Step 3: Evaluate the models
python src/evaluate.py
Step 4: Launch the Streamlit dashboard
streamlit run dashboard/app.py

## Dashboard
The project includes an interactive Streamlit dashboard for viewing the results of the insider-threat detection system.

The dashboard provides:

User behavioral analysis
Risk scoring
Security-related visualizations
Model results
Threat-related insights
Interaction with the AI security assistant

Dashboard screenshots can be added here to demonstrate the application's interface.
For example:
## Dashboard

![Dashboard](images/dashboard.png)


## Project Contributions
My contribution included working with the Python-based development and machine-learning workflow, along with project implementation, testing, debugging, and documentation.

Important: If there are specific parts you personally developed—such as data preprocessing, model training, dashboard development, or chatbot integration—we can make this section much more specific.


## Future Improvements
The project can be further enhanced with:

Real-time monitoring of user activities
Additional behavioral features for threat detection
More machine learning models for comparison
Improved model accuracy and evaluation
Enhanced dashboard visualizations
Improved security-alert mechanisms
Integration with enterprise security monitoring systems
Deployment as a scalable web application
