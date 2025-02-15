# SoundScape: ML-Based Audio Genre Recognition 🎵🎧

## 📌 Overview
SoundScape is a machine learning-based audio genre recognition system that classifies music into different genres based on extracted audio features. This project leverages multiple ML models (SVM, Random Forest, KNN) combined using an ensemble approach (Voting Classifier) to improve accuracy. Users can upload an audio file through a Flask web interface, and the system predicts its genre using pre-trained models.

## 🌟 Features
✅ Multi-Model Approach – Uses multiple ML models and combines their predictions for better accuracy.
✅ Audio Feature Extraction – Utilizes Librosa to extract features like MFCCs, Spectral Features, and Chroma.
✅ Voting Classifier – Uses ensemble learning to enhance prediction reliability.
✅ Pre-trained Model Deployment – Saves the trained model using Joblib for fast predictions.
✅ Web Interface – A Flask-based user-friendly web app where users can upload songs for classification.

## 🛠️ Technologies Used
Python 🐍
Flask (for the web interface) 🌍
Librosa (for audio processing) 🎼
Scikit-Learn (ML models: SVM, KNN, Random Forest) 📊
Pandas & NumPy (data handling) 📑
Matplotlib & Seaborn (for visualization) 📉
Joblib (for saving and loading trained models) 🔄
