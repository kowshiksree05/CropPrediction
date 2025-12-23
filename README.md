# CropPrediction – Crop Recommendation Using Machine Learning 🌾

CropPrediction is a machine learning–based system designed to recommend the most suitable crop to grow based on soil nutrients and environmental conditions.  
The system uses supervised learning techniques and feature scaling to provide accurate crop recommendations and is deployed using a Flask web application.

---

## 📁 Project Structure

CropPrediction/
│
├── app.py                                   # Main Flask application file
│
├── Crop Recommendation Using Machine Learning.ipynb
│                                            # Jupyter Notebook for data preprocessing,
│                                            # feature scaling, model training & evaluation
│
├── Crop_recommendation.csv                  # Dataset used for training the model
│
├── model.pkl                                # Trained machine learning model
│
├── minmaxscaler.pkl                         # MinMaxScaler used during preprocessing
│
├── standscaler.pkl                          # StandardScaler used during preprocessing
│
├── README.md                                # Project documentation

---

## 🚀 Features

- Recommends the most suitable crop based on soil and climate data
- Uses machine learning for data-driven agricultural decisions
- Applies feature scaling for consistent and accurate predictions
- Flask-based API for easy deployment and integration
- Lightweight and easy to extend for web or mobile applications

---

## 🛠️ Tech Stack

Languages:
- Python

Libraries / Frameworks:
- Flask
- scikit-learn
- pandas
- numpy

Machine Learning Techniques:
- Supervised learning
- Feature scaling (StandardScaler, MinMaxScaler)
- Model serialization using pickle

---

## 📂 Dataset Description

The dataset (Crop_recommendation.csv) contains the following features:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH value
- Rainfall

Target Variable:
- Recommended crop name

---

## 🔄 Project Workflow

Soil & Climate Input Data
        │
        ▼
Data Preprocessing (Cleaning & Validation)
        │
        ▼
Feature Scaling (StandardScaler / MinMaxScaler)
        │
        ▼
Trained Machine Learning Model
        │
        ▼
Crop Recommendation Output

---

## ▶️ Running the Application

Install required dependencies:
pip install flask pandas numpy scikit-learn

Run the application:
python app.py

Open your browser and navigate to:
http://127.0.0.1:5000

---

## 🎯 Applications

- Smart agriculture and crop planning
- Decision support for farmers
- Educational and academic projects

---

## 📌 Notes

- The model and scalers are pre-trained and loaded directly.
- No retraining is required to run the application.
- Flask development server is used; suitable for demos and academic use.

---

## 📄 License

This project is intended for educational and research purposes only.
