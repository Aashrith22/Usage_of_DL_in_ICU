ICU Mortality Risk Prediction :

This repository contains the implementation of an RNN-based model for real-time ICU mortality risk assessment.
The model continuously monitors patient conditions and provides timely risk predictions to assist healthcare professionals in decision-making.

Project Structure :

1) app.py: Flask web application for the project, facilitating real-time prediction and visualization.
2) Notebook.ipynb: Jupyter Notebook with model training and evaluation details.
3) model.sav: Pre-trained RNN model saved for deployment.
4) processed.csv: Processed dataset used for training and testing.
5) *) scaler_data: Data scaler object for consistent feature scaling during prediction.
6) signup.db: SQLite database for user management (e.g., for web app signups).
7) flowchart: Visual flowchart outlining the model's workflow and prediction process.
8) static/ & templates/: Directories for front-end components of the web app (CSS, HTML).
9) archive/ & sample/: Additional data and code archives for reference.

Features :
1) Real-Time Predictions: Flask-based app for making live predictions using the trained model.
2) Pre-trained Model: Use the saved model.sav for inference.
3) Data Processing: Preprocessed dataset and scaling utilities provided.

Technologies Used : 
1) Python (Flask, TensorFlow, Scikit-learn)
2) SQLite (for user management)
3) Jupyter Notebook
