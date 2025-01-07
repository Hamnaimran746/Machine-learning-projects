# Real-Time Emotion Detection

This project implements a real-time emotion detection model developed on **Google Colab** using the **CK+ dataset** (Extended Cohn-Kanade dataset). The model classifies facial expressions into one of the following seven emotion categories: **Happy, Sad, Angry, Surprise, Neutral, Disgust, and Fear**.

### Dataset
The model is trained on the **CK+ dataset**, which contains a variety of labeled facial expression images captured under controlled conditions. The dataset provides high-quality images with multiple frames per subject to capture various facial expressions.

### Model Performance
The trained model achieves an accuracy of **90.22%** on the test data, making it highly effective for emotion recognition. The model uses Convolutional Neural Networks (CNN) to extract facial features and classify emotions.

### Features
- Real-time emotion detection using the webcam.
- Classifies seven different emotions: Happy, Sad, Angry, Surprise, Neutral, Disgust, and Fear.
- High accuracy of **90.22%** on the test set.
- Developed and trained on **Google Colab** for easy access and cloud-based execution.

### Requirements
To run the project, ensure the following dependencies are installed:
- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

### Installation
1. Clone the repository to your local machine or use it directly from Google Colab.
    ```
    git clone https://github.com/yourusername/emotion-detection.git
    ```
2. Install the required libraries by running the following command in Google Colab:
    ```python
    !pip install -r requirements.txt
    ```

### Usage
1. Open the **Google Colab** notebook and run the cells in sequence to train and test the emotion detection model.
2. Alternatively, download the trained model and use it to run real-time emotion detection on your webcam by running the provided Python script.

### Accuracy
The emotion detection model has been trained and tested on the CK+ dataset, achieving an impressive accuracy of **90.22%** on the test set.
