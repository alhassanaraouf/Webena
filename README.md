# Image Prediction Web App

## Overview

The Image Prediction Web App is a sophisticated web application designed to predict the content of uploaded images. Leveraging a pre-trained deep learning model, it classifies images into various categories (e.g., dog, cat) and stores the results in an Azure SQL Database. Users can upload images through the web interface, and the application will display the prediction results alongside the uploaded images.

## Features

- **User-Friendly Web Interface:** Enables users to upload images and view prediction results effortlessly.
- **Azure SQL Database Integration:** Stores image data and prediction results securely and efficiently.
- **Pre-Trained Deep Learning Model:** Utilizes a powerful model for accurate image classification.

## Usage

1. **Access the Web Interface:**
   - Navigate to the web application in your browser.
2. **Upload an Image:**
   - Use the provided form to upload an image.
3. **View Prediction Results:**
   - Wait for the application to process the image and display the prediction result along with the uploaded image.

## File Structure

- **app.py:** Core Flask application handling routes for image uploads, predictions, and database interactions.
- **static/**: Directory for static files such as CSS stylesheets and the pre-trained model.
- **templates/**: Directory for HTML templates used in the web interface.

## Dependencies

- **Flask:** Web framework for developing the application.
- **OpenCV (cv2):** Library for advanced image processing.
- **Keras:** Deep learning framework for loading and utilizing the pre-trained model.
- **pyodbc:** Library for connecting to the Azure SQL Database.
