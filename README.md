P1-Image_Classification_By_Machine_Learning-AICTE-INTERNSHIP

This project implements a Streamlit web application for real-time image classification using two deep learning models: MobileNetV2 and CIFAR-10. Users can upload images and get predictions from either model, with confidence scores displayed in real-time. The app provides an intuitive interface to explore image classification tasks and experiment with powerful machine learning models.

Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Setup and Run](#setup-and-run)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

Overview

This project features a Streamlit app that allows users to upload images for classification. It integrates two powerful models:
- MobileNetV2: A lightweight, pre-trained model on ImageNet capable of classifying over 1,000 categories.
- CIFAR-10: A custom model trained on the CIFAR-10 dataset, designed to classify 10 specific categories, such as airplanes, automobiles, and birds.

The app allows users to easily switch between the two models, making it suitable for both educational and practical uses.
Features
- Dual Model Support:
  - MobileNetV2: Pre-trained on ImageNet for general object classification.
  - CIFAR-10: Trained on a specific set of 10 classes from the CIFAR-10 dataset.
- Real-Time Image Classification: Upload an image and receive instant predictions with confidence scores.
- Interactive Interface: A user-friendly navigation bar to switch models effortlessly.
- Educational Value: A great tool for learning about machine learning and deep learning models.

Installation

Prerequisites

- Python 3.7 or later
- A web browser (for viewing the Streamlit app)

Setup and Run

1. Clone the repository:
   ```bash
   git clone https://github.com/JayRathod341997/DeepLensX.git
   cd Implementation-of-ML-model-for-image-classification
   ```

2. Create and activate a virtual environment:
   - For macOS/Linux:
     ```bash
     python -m venv venv
     source venv/bin/activate
     ```
   - For Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

5. Access the app: After running the above command, the app should automatically open in your default web browser. If not, manually visit [http://localhost:8501](http://localhost:8501).

Usage

Once the app is running:
- Upload an Image: Click on the file upload button to select an image.
- Select Model: Use the navigation bar to choose between the **MobileNetV2** or **CIFAR-10** model.
- View Prediction: The app will display the predicted label and the confidence score for the classification.

Contributing

We welcome contributions! If you'd like to help improve this project, feel free to:
- Fork the repository.
- Open issues to report bugs or suggest features.
- Submit pull requests with improvements or fixes.

Acknowledgements

- Streamlit: For providing an easy-to-use framework for building interactive web apps.
- TensorFlow: For powering the deep learning models used in this project.
- CIFAR-10: For providing a great dataset for image classification.
