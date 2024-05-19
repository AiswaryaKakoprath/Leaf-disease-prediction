# Cotton Leaf Disease Prediction

## Overview
This project aims to predict cotton leaf diseases using deep learning techniques, specifically leveraging the InceptionV3 architecture. The trained model can distinguish between healthy and diseased cotton leaves, aiding farmers in early detection and management of plant diseases.

## Features
- **Deep Learning Model**: Utilizes the InceptionV3 architecture trained on a dataset of cotton leaf images.
- **Web Application**: A Flask-based web application allows users to upload images of cotton leaves and receive predictions about their health status.
- **Easy Deployment**: The application can be deployed on a server or cloud platform, making it accessible to farmers and agricultural professionals.

## Dataset
The dataset consists of images of healthy cotton leaves as well as leaves affected by various diseases. It was collected from diverse sources and preprocessed to ensure consistency and quality.

## Model Training
The InceptionV3 model was fine-tuned on the preprocessed dataset using transfer learning techniques. The trained model achieved high accuracy in distinguishing between healthy and diseased cotton leaves.

## Web Application
The web application was developed using Flask, a lightweight Python web framework. It provides a simple and intuitive interface for users to upload images and receive predictions in real-time.

## Usage
To use the application locally, follow these steps:
1. Clone this repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Flask application using `python app.py`.
4. Access the application through your web browser at `http://localhost:5000`.

## Deployment
The application can be deployed on a server or cloud platform to make it accessible over the internet. Follow the deployment instructions provided in the `deployment` directory.

## Contributing
Contributions to the project are welcome! If you'd like to contribute, please follow these guidelines:
- Fork the repository and create your branch from `main`.
- Make your changes and ensure the codebase follows the project's style and standards.
- Submit a pull request detailing the changes you've made and any relevant information.


## Credits
- The InceptionV3 architecture is implemented using TensorFlow, an open-source deep learning framework.
- Flask is used for developing the web application frontend and backend.
