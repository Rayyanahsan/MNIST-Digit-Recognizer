# MNIST-Digit-Recognizer
A simple web application built with Python, Scikit-learn, and Gradio that recognizes handwritten digits (0–9) from either an uploaded image or drawing canvas.


Feature 

🎨 Real-time Prediction – Draw a digit directly on the canvas and see the model's prediction instantly.

📤 Image Upload – Upload an image of a handwritten digit to classify it.

⚙️ Automatic Preprocessing – Input is resized, inverted, and normalized for consistent model input.

🔍 High Accuracy – Powered by a RandomForestClassifier trained on the MNIST dataset with over 95% accuracy.


How to Run
Clone this repo:


git clone 
Go to the project folder:



cd MNIST-Digit-Recognizer
Install the required libraries:


pip install -r requirements.txt
Run the app:


python app.py
The app will open in your browser. You can draw a digit or upload an image to test it.
