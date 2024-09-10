ICU Mortality Risk Prediction :

This repository contains the implementation of an RNN-based model for real-time ICU mortality risk assessment.
The model continuously monitors patient conditions and provides timely risk predictions to assist healthcare professionals in decision-making.

Project Structure :

*) app.py: Flask web application for the project, facilitating real-time prediction and visualization.
*) Notebook.ipynb: Jupyter Notebook with model training and evaluation details.
*) model.sav: Pre-trained RNN model saved for deployment.
*) processed.csv: Processed dataset used for training and testing.
*) scaler_data: Data scaler object for consistent feature scaling during prediction.
*) signup.db: SQLite database for user management (e.g., for web app signups).
*) flowchart: Visual flowchart outlining the model's workflow and prediction process.
*) static/ & templates/: Directories for front-end components of the web app (CSS, HTML).
*) archive/ & sample/: Additional data and code archives for reference.

Features :
*) Real-Time Predictions: Flask-based app for making live predictions using the trained model.
*) Pre-trained Model: Use the saved model.sav for inference.
*) Data Processing: Preprocessed dataset and scaling utilities provided.

Technologies Used : 
*) Python (Flask, TensorFlow, Scikit-learn)
*) SQLite (for user management)
*) Jupyter Notebook
