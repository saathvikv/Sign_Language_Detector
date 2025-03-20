# Sign_Language_Detector

Overview
This project implements an Artificial Neural Network (ANN) to classify American Sign Language (ASL) hand gestures from images. The dataset is preprocessed, resized, and vectorized before training.

Model Architecture

Flatten and dense layers for feature extraction
ReLU activation for non-linearity
Softmax activation for multi-class classification
Training
The model is trained using the Adam optimizer with categorical cross-entropy loss. Training images are augmented to improve model robustness.
