# Human Emotion Detection Project

This project implements a basic human emotion detection system using a pre-trained deep learning model. It can analyze images (potentially from a webcam or provided files) and predict the emotion displayed.

## Overview

The goal of this project is to:

* Detect basic human emotions (e.g., happy, sad, angry, fear, surprise, neutral, disgust) from facial expressions in images.
* Provide a simple and understandable implementation of emotion recognition.

## Files Included

* `test/`: Contains test images for evaluating the model.
* `train/`: Contains the training data used to train the emotion detection model.
* `Camera_Setup.ipynb`: A Jupyter Notebook to set up and run emotion detection using a connected camera.
* `emotion_model.h5`: The pre-trained Keras/TensorFlow model file for emotion recognition.
* `HUMAN_EMOTION_REGOGNITION.ipynb`: The main Jupyter Notebook containing the code for loading the model and performing emotion recognition on images or video streams.
* `README.md`: This file, providing an overview and instructions for the project.

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/siddhant-2310/human-emotion-detection.git](https://github.com/siddhant-2310/human-emotion-detection.git)
    cd human-emotion-detection
    ```

2.  **Install Dependencies:**
    It is highly recommended to create a virtual environment to isolate the project dependencies.

    **On Linux/macOS:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

    **On Windows:**
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

    Once the virtual environment is activated, install the necessary libraries. Based on the project files, these are likely to include:
    ```bash
    pip install tensorflow keras numpy opencv-python matplotlib ipykernel
    ```
    This command will install TensorFlow and Keras (for the deep learning model), NumPy (for numerical operations), OpenCV (for image and video processing), Matplotlib (for plotting), and ipykernel (for running Jupyter Notebooks).

3.  **Emotion Model:**
    The pre-trained emotion detection model (`emotion_model.h5`) is included directly in the repository. No additional download is required.
