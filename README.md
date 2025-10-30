# Multiple Disease Prediction

## Link: [Live App](https://mdiseaseprediction.streamlit.app/)

## Overview
This project is a **web-based application** built using **Streamlit** that predicts the likelihood of multiple diseases based on user-inputted symptoms and health metrics. It leverages **machine learning models** trained on medical datasets to provide fast, accessible, and reliable predictions for four major diseases:
- Diabetes
- Heart Disease
- Parkinson's Disease
- Breast Cancer

## Features
- 🧠 **Multiple Disease Prediction**: Users can select the disease they want to test for and input relevant health data.
- 📊 **Interactive UI**: Built with Streamlit for a clean, responsive interface.
- 🔍 **Real-time Results**: Predictions are generated instantly using pre-trained models.
- 🧪 **Model Accuracy**: Models are trained using scikit-learn and evaluated for performance using metrics like accuracy and confusion matrix.

## Technologies Used
- **Python**
- **Streamlit** for frontend
- **Scikit-learn** for machine learning
- **Pandas & NumPy** for data manipulation
- **Pickle** for model serialization

## How It Works
1. The user selects a disease from the sidebar.
2. Inputs relevant health parameters (e.g., glucose level, blood pressure).
3. The app loads the corresponding trained model.
4. Prediction is displayed instantly based on the input.

## Installation
To run locally:
```bash
git clone https://github.com/JS-Coder007/Multiple_Disease_Prediction-main.git
cd Multiple_Disease_Prediction-main
pip install -r requirements.txt
streamlit run app.py
