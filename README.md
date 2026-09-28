🩺 DermaFusion-ML
An Ensemble Intelligence Framework for Automated Skin Disease Classification
📌 Overview

DermaFusion-ML is an AI-powered web application designed to classify skin diseases from dermoscopic images. The system combines deep feature extraction using EfficientNetB0 with multiple machine learning classifiers and a Soft Voting Ensemble.

The project demonstrates the practical application of Artificial Intelligence, Deep Learning, Machine Learning, Computer Vision, and Django in healthcare image classification.

⚠️ This project is intended for academic and research purposes only and should not be considered a medical diagnostic system.

🎯 Objectives
Automate skin disease image classification.
Extract meaningful features using EfficientNetB0.
Handle class imbalance using SMOTE.
Apply multiple machine learning classifiers.
Combine predictions using Soft Voting.
Provide a simple Django-based web interface.
🔬 Methodology
Dermoscopic Image
       ↓
Image Preprocessing
       ↓
EfficientNetB0
       ↓
1280-D Feature Extraction
       ↓
SMOTE
       ↓
ML Classifiers
       ↓
Soft Voting Ensemble
       ↓
Disease Prediction
Machine Learning Models
Support Vector Machine (SVM)
Random Forest
Linear Discriminant Analysis (LDA)
Naive Bayes
📊 Dataset
Property	Details
Images	1,169
Categories	8
Feature Extractor	EfficientNetB0
Feature Dimension	1280
Class Balancing	SMOTE
📈 Results
Metric	Result
Training Accuracy	96.40%
Test Accuracy	82.00%
🛠️ Technologies
Python
Django
TensorFlow / Keras
Scikit-learn
EfficientNetB0
OpenCV
NumPy
Pandas
SQLite
HTML / CSS / JavaScript
📂 Project Structure
DermaFusion-ML/
│
├── classifier/
├── skin_disease_project/
├── ml_model/
├── training/
├── static/
├── media/
├── templates/
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
⚙️ Installation & Setup
1. Clone Repository
git clone https://github.com/chawanjaisingh1/DermaFusion-ML.git
cd DermaFusion-ML
2. Create Virtual Environment
python -m venv venv

Windows:

venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Run Database Migration
python manage.py migrate
5. Start Django Server
python manage.py runserver

Open:

http://127.0.0.1:8000/
🌐 Application Workflow
Open the DermaFusion-ML web application.
Upload a dermoscopic image.
The image is preprocessed.
EfficientNetB0 extracts deep features.
Machine learning classifiers process the features.
Soft Voting generates the final prediction.
The predicted class is displayed to the user.
🚀 Future Enhancements
Explainable AI using Grad-CAM
Larger and more diverse datasets
Additional deep learning models
Mobile application
Cloud deployment
Prediction history
REST API
Improved model validation
👨‍💻 Project Information

Project: DermaFusion-ML
Domain: Artificial Intelligence & Machine Learning
Application: Skin Disease Classification
Framework: Django
Degree: B.Tech Computer Science & Engineering

⚠️ Disclaimer

DermaFusion-ML is an academic/research project. Its predictions should not be used as a substitute for professional medical diagnosis or treatment.
