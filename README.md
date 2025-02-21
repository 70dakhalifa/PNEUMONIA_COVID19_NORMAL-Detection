# PNEUMONIA_COVID19_NORMAL-Detection
Chest X-ray Classification Using SVM and HOG Features
Project Overview
This project aims to classify chest X-ray images into three categories—NORMAL, PNEUMONIA, and COVID-19—using a Support Vector Machine (SVM) classifier. The model leverages Histogram of Oriented Gradients (HOG) features to extract meaningful patterns from X-ray images, enabling efficient classification. The goal is to provide an accurate and computationally efficient solution for early diagnosis and detection of respiratory diseases.

Key Features & Methodology
Dataset Preparation

Chest X-ray images are organized into training and testing datasets.
Three classes are considered: NORMAL, PNEUMONIA, and COVID-19.
Images are resized and preprocessed before feature extraction.
Feature Extraction using HOG

Converts images to grayscale and extracts HOG features, capturing texture and structural details.
HOG descriptors are used as input features for classification instead of raw pixel values.
Training the SVM Classifier

A Support Vector Machine (SVM) model with different kernels (linear, RBF) is trained using GridSearchCV for hyperparameter tuning.
The best performing model is saved for future use.
Model Evaluation

The model is evaluated using accuracy, confusion matrix, and classification report.
Randomly selected test images are displayed with their actual and predicted labels.
Performance Visualization

A confusion matrix is plotted using Seaborn to analyze misclassifications.
The classification report provides precision, recall, and F1-score metrics for each class.
Technologies Used
Python (for implementation)
NumPy, Pandas (for data handling)
Matplotlib, Seaborn (for visualization)
Scikit-learn (for SVM, GridSearchCV, model evaluation)
PIL, Scikit-Image (for image processing and HOG feature extraction)
Applications & Impact
Medical Diagnosis Support: Assists radiologists by automating the detection of pneumonia and COVID-19.
Early Detection: Helps in identifying respiratory diseases at an early stage, improving treatment outcomes.
Lightweight & Efficient: Unlike deep learning-based solutions, this SVM-based approach is computationally efficient and suitable for low-resource environments.
