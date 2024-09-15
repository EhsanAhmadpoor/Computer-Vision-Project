# Anti-Spoofing Algorithm for Facial Recognition

This project implements an anti-spoofing algorithm for facial recognition systems to detect liveliness in video frames. The goal is to distinguish between live faces and spoofed faces, which can be either photographs or videos. The project uses a custom Convolutional Neural Network (CNN) architecture and advanced feature extraction methods.

## Features

- **Liveliness Detection:** Detects whether a face in a video frame is live or spoofed.
- **Custom CNN Architecture:** Utilizes a custom CNN model for feature extraction and classification.
- **Feature Extraction:** Includes frequency domain features and Local Binary Patterns (LBP).
- **Comprehensive Evaluation:** Evaluates model performance using accuracy, precision, recall, and F1-score.

## Dataset

- **CASIA-FASD Dataset:** Used for training and evaluation of the model. The dataset contains images labeled as 'live' or 'spoof'.
