# Image Prediction Web App

## Overview
This project is a web application for predicting the content of uploaded images. It uses a pre-trained deep learning model to classify images into categories (e.g., dog, cat) and stores the results in an Azure SQL Database. Users can upload an image through the web interface, and the application will display the prediction result along with the uploaded image.

## Features
- Web interface for uploading images and displaying prediction results.
- Integration with an Azure SQL Database to store image data and prediction results.
- Usage of a pre-trained deep learning model for image classification.

## Setup
1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Download the pre-trained deep learning model (`model.h5`) and place it in the `static` directory.
4. Configure the Azure SQL Database connection settings in the Flask application (`app.py`).
5. Run the Flask application using `python app.py`.
6. Access the web interface in your browser at `http://localhost:5000`.

## File Structure
- `app.py`: Flask application containing routes for handling image uploads, predictions, and database interactions.
- `static/`: Directory containing static files such as CSS stylesheets and the pre-trained model.
- `templates/`: Directory containing HTML templates for the web interface.

## Dependencies
- Flask: Web framework for building the application.
- OpenCV (cv2): Library for image processing.
- Keras: Deep learning framework for loading and using the pre-trained model.
- pyodbc: Library for connecting to the Azure SQL Database.

## Usage
1. Access the web interface in your browser.
2. Upload an image using the provided form.
3. Wait for the prediction result to be displayed.
4. View the prediction result along with the uploaded image.

## Contributors
- [Your Name]

## License
[License information]

