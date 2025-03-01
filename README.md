# Diet Recommendation System

This project is a Diet Recommendation System built using Streamlit, Scikit-Learn, and Google Gemini AI. The system predicts personalized diet recommendations based on user inputs such as age, gender, weight, height, disease type, severity, physical activity level, and other health-related parameters.

## Features

- Machine Learning Model: Utilizes a Random Forest Classifier trained on health-related data to predict diet recommendations.

- Google Gemini AI Integration: Provides diet suggestions using Google Generative AI (Gemini 1.5 Pro).

- Data Preprocessing: Uses Label Encoding, One-Hot Encoding, and Standardization for efficient model training.

- Interactive Web UI: Built with Streamlit for a user-friendly interface.

- Model Persistence: Saves the trained model and scaler using Joblib for future use.

## Installation

## Prerequisites

Ensure you have Python 3.8+ installed. You also need a Google API Key for Gemini AI.

## Clone the Repository
```python
git clone https://github.com/your-username/diet-recommendation-system.git
cd diet-recommendation-system
```

## Install Dependencies
```python
pip install -r requirements.txt
```
## Set Up Environment Variables

- Create a .env file in the project directory and add your Google API Key:
```python
GOOGLE_API_KEY=your_google_api_key_here
```
## Usage

- Run the Streamlit App
```python
streamlit run app.py
```
