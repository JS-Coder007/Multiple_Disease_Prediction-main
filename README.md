# 🩺 Multiple Disease Prediction

[![Made with Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-red?logo=streamlit)](https://streamlit.io/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Live App](https://img.shields.io/badge/Live%20App-Click%20Here-green)](https://mdiseaseprediction.streamlit.app/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Source%20Code-black?logo=github)](https://github.com/JS-Coder007/Multiple_Disease_Prediction-main)

## 🔗 Live Demo
Explore the app here: [mdiseaseprediction.streamlit.app](https://mdiseaseprediction.streamlit.app/)

## 📌 Project Description
This is a **Streamlit-powered web application** that predicts the likelihood of three major diseases using machine learning models. It provides an intuitive interface for users to input medical data and receive instant predictions.

### Diseases Covered:
- 🩸 Diabetes
- ❤️ Heart Disease
- 🧠 Parkinson's Disease

## 🚀 Features
- Interactive disease selection via sidebar
- Real-time predictions using trained ML models
- Clean and responsive UI with Streamlit
- Easy deployment and scalability

## 🛠️ Tech Stack
| Technology     | Purpose                        |
|----------------|--------------------------------|
| Python         | Core programming language      |
| Streamlit      | Web interface                  |
| Scikit-learn   | Machine learning models        |
| Pandas, NumPy  | Data manipulation              |
| Pickle         | Model serialization            |

## 📂 Project Structure
Multiple_Disease_Prediction-main/ 
├── app.py                # Streamlit app 
├── models/               # Saved ML models (.pkl) 
├── disease_prediction/   # Training scripts 
├── requirements.txt      # Dependencies


## 🧪 How to Run Locally
```bash
git clone https://github.com/JS-Coder007/Multiple_Disease_Prediction-main.git
cd Multiple_Disease_Prediction-main
pip install -r requirements.txt
streamlit run app.py
