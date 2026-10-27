# Lung-disease-prediction-using-deep-learning-
A deep learning-based web application that predicts six lung diseases by analyzing respiratory sounds using audio preprocessing, DFT-based noise removal, Mel spectrograms, and a CNN-LSTM model. Built with Python, Flask, TensorFlow, and Librosa to support preliminary respiratory disease screening.
# 🫁 Lung Disease Prediction Using Deep Learning

## Overview
Lung Disease Prediction is a deep learning-based web application that analyzes respiratory sound recordings to predict potential lung diseases. It uses audio signal processing and a hybrid CNN-LSTM model to classify respiratory conditions and support preliminary screening.

## Objectives
- Analyze respiratory sounds using deep learning.
- Extract meaningful audio features using Mel spectrograms.
- Predict possible respiratory diseases.
- Provide a simple, user-friendly web interface for uploading or recording lung sounds.

## Features
- Upload or record respiratory sounds.
- Audio preprocessing and noise removal using DFT-based techniques.
- Mel spectrogram feature extraction.
- CNN-LSTM-based respiratory sound classification.
- Display prediction results through a web interface.
- Provide precautionary information for respiratory health.

##  Diseases Classified
The model is designed to classify six respiratory conditions:
- Bronchiolitis
- Bronchitis
- Pneumonia
- Lower Respiratory Tract Infection (LRTI)
- Asthma
- Chronic Obstructive Pulmonary Disease (COPD)

## Technologies Used
- **Programming Language: Python
- **Frontend:HTML, CSS, JavaScript
- **Backend: Flask
- **Deep Learning:TensorFlow, CNN-LSTM
- **Audio Processing: Librosa, DFT
- **Feature Extraction: Mel Spectrograms

##  How It Works
1. Upload or record a respiratory sound.
2. Preprocess the audio by resampling, removing noise, and normalizing the signal.
3. Extract relevant time-frequency features using Mel spectrograms.
4. Pass the processed audio features to the trained CNN-LSTM model.
5. Display the predicted respiratory condition on the website.

##  Future Enhancements
- Improve model performance using larger and more diverse datasets.
- Add support for more respiratory conditions.
- Enhance the user interface and accessibility.
- Explore real-time respiratory sound monitoring.
- Evaluate model performance across different patient groups.

##  Disclaimer
This project is developed for educational and research purposes. Predictions are preliminary and may be inaccurate. The application is not a substitute for professional medical advice, diagnosis, or treatment. Consult a qualified healthcare professional for medical concerns.

##  Author
**Lalitha Aripaka**

B.Tech — Computer Science and Engineering (AI & ML)

GitHub: [lalitha-1606](https://github.com/lalitha-1606)
