# MNIST-Digit-Recognizer
A simple web application built with Python, Scikit-learn, and Gradio that recognizes handwritten digits (0–9) from either an uploaded image or drawing canvas.
Features
Real-time Prediction – Draw a digit and get an instant result.
Image Upload – Upload a handwritten digit image for classification.
Preprocessing Pipeline – Automatically resizes, inverts, normalizes input.
Robust Model – Uses RandomForestClassifier trained on the MNIST dataset for 95%+ accuracy.
Technologies Used
Tool	Purpose
Python	Main programming language
Scikit-learn	Training and using ML models
Gradio	Web interface for predictions
NumPy	Matrix & array operations
OpenCV	Image processing
Joblib	Saving/loading model file
gdown	Downloads model from Google Drive
