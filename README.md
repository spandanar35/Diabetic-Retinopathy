# Diabetic Retinopathy Detection

Diabetic Retinopathy Detection is a deep learning-based web application designed to identify the severity of diabetic eye disease from retinal images. The system uses a Convolutional Neural Network (CNN) model trained on retinal datasets to classify images into different stages of Diabetic Retinopathy such as Normal, Mild, Moderate, Severe, and Proliferative. It helps in early detection of the disease, reducing the risk of vision loss. The Flask-based web interface allows users to easily upload images and instantly view prediction results with accuracy and performance metrics like the confusion matrix and classification report.

# Table of Contents

1.Features

2.Tech Stack

3.Installation

4.Usage

5.example output

# Features

1.Upload retinal images for disease prediction

2.Deep learning model trained with CNN for DR detection

3.Shows prediction accuracy, confusion matrix, and classification report

4.User-friendly web interface using Flask

5.Displays result as: Normal, Mild, Moderate, Severe, or Proliferative DR

6.Secure model integration with TensorFlow/Keras

# Tech Stack

1.Frontend: HTML, CSS, JavaScript, Bootstrap

2.Backend: Flask (Python)

3.Machine Learning Model: CNN (TensorFlow/Keras)

4.Database: (If used — e.g., Mysql or Xampp)

# Installation

1.Clone the repository: git clone https://github.com/your-username/diabetic-retinopathy-detection.git

2.Navigate to the project folder: cd diabetic-retinopathy-detection

3.Install dependencies: pip install -r requirements.txt

4.Run the application: python app.py

5.Open in your browser: http://127.0.0.1:5000/

# Usage

1.Upload a retinal image.

2.Wait for the model to predict.

3.View the disease stage and confidence score.

# Example Output

Prediction: Mild Diabetic Retinopathy

Accuracy: 92%
