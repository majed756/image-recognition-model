# image-recognition-model
image recognition model using Teachable Machine and Google Colab for cars and baiks

🚗 🏍️ Vehicle Classifier using Teachable Machine and Google Colab
This repository contains a simple, fast-prototyping Computer Vision project that classifies images into two categories: Cars and Bikes. The model was trained using Google's Teachable Machine and deployed using a Python script inside a Google Colab notebook.

📌 Project Overview
The core purpose of this project is to understand the workflow of transfer learning and deploying cloud-trained machine learning models locally or in a notebook environment.

The pipeline consists of:

Data Collection & Training: Training a Convolutional Neural Network (CNN) via a no-code interface.

Model Exporting: Exporting the trained weights as a Keras model.

Inference & Prediction: Running prediction scripts on test images inside Google Colab using TensorFlow and Pillow.

📊 Dataset & Training Specifications
Classes:

cars (Automobiles)

baiks (Motorcycles/Bikes)

Training Platform: Google Teachable Machine

Epochs / Batch Size: Default Teachable Machine hyperparameters.

📁 Repository Structure & Required Files
To run this project successfully in your Google Colab environment, ensure the following files are uploaded to your runtime workspace:

keras_model.h5: The exported TensorFlow/Keras model file containing the trained weights.

labels.txt: The text file containing the indexed class names.

image.jpg: Any target image you want the model to test and classify.
