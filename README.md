# SoundScape: ML-Based Audio Genre Recognition 🎵🎧

## 📌 Overview
SoundScape is a machine learning-based audio genre recognition system that classifies music into different genres based on extracted audio features. This project leverages multiple ML models (SVM, Random Forest, KNN) combined using an ensemble approach (Voting Classifier) to improve accuracy. Users can upload an audio file through a Flask web interface, and the system predicts its genre using pre-trained models.

## 🌟 Features
- Multi-Model Approach – Uses multiple ML models and combines their predictions for better accuracy.
- Audio Feature Extraction – Utilizes Librosa to extract features like MFCCs, Spectral Features, and Chroma.
- Voting Classifier – Uses ensemble learning to enhance prediction reliability.
- Pre-trained Model Deployment – Saves the trained model using Joblib for fast predictions.
- Web Interface – A Flask-based user-friendly web app where users can upload songs for classification.

## 🛠️ Technologies Used
- Python 
- Flask (for the web interface) 
- Librosa (for audio processing) 
- Scikit-Learn (ML models: SVM, KNN, Random Forest) 
- Pandas & NumPy (data handling) 
- Matplotlib & Seaborn (for visualization) 
- Joblib (for saving and loading trained models)

## ⚙️ Installation
- Clone the repository

- Create and activate a virtual environment (optional but recommended)
   
- Install dependencies
   
- Run the Flask App

## 🚀 How It Works
**Dataset Collection & Preprocessing**
- Used the GTZAN dataset, containing 10 music genres.
  
- Extracted features using Librosa and stored them in a CSV file.
  
**Model Training & Ensemble Learning**
- Trained SVM, Random Forest, and KNN on extracted features.
  
- Combined models using a Voting Classifier to improve accuracy.
  
- Saved the final model using Joblib.
  
**Web Interface & Prediction**
- Built a Flask-based web app where users can upload an audio file.
  
- Extracted features from the uploaded file and passed them to the trained model.
  
- Displayed the predicted genre on the webpage.

## 🎯 Use Cases
🎵 Music Recommendation Systems – Can be used for personalized song recommendations.

📻 Radio & Streaming Services – Helps in auto-categorizing music libraries.

📊 Data Science Projects – A great project for understanding ML-based classification.

🎧 Audio Content Management – Useful for automatic tagging and playlist generation.


     


