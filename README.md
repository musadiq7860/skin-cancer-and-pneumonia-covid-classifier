## Skin Cancer and Pneumonia/COVID Classifier

This repository contains Convolutional Neural Network (CNN) models for medical image classification. Two separate CNN pipelines are developed:

## Skin Cancer Detection – Binary classification of skin lesion images into benign or malignant.

Pneumonia & COVID Detection – Multi-class classification of chest X-ray images into COVID, Pneumonia, or Normal.

Both models are built using TensorFlow/Keras and trained with data augmentation for better generalization.

## Project Structure

Pneumonia and covid classifier.ipynb → CNN notebook for pneumonia & COVID detection

Skincancerdetection (5).ipynb → CNN notebook for skin cancer detection

Pneumonia and COVID Classifier – Report.docx

Skincancer_report.docx

README.md

.gitattributes

## Features

CNN Models trained from scratch with Conv2D, MaxPooling, Dense, and Dropout layers.

ImageDataGenerator used for preprocessing and augmentation.

Multi-class (3 classes): COVID, Pneumonia, Normal (Chest X-rays).

Binary classification (2 classes): Malignant, Benign (Skin cancer).

Achieved ~90% validation accuracy in pneumonia/covid classification.

## How to Run

Clone the repo.

Install dependencies (tensorflow, scikit-learn, matplotlib).

Prepare dataset folders:

For pneumonia/covid → dataset/ with subfolders (COVID, PNEUMONIA, NORMAL).

For skin cancer → data/train/ with benign/ and malignant/ subfolders.

Open and run the Jupyter notebooks:

Pneumonia and covid classifier.ipynb

Skincancerdetection (5).ipynb

📊 Results

Pneumonia/COVID Model: ~90% validation accuracy after 20 epochs.

Skin Cancer Model: Reliable binary classification with augmented data.

📌 Future Work

Add transfer learning with pre-trained models (ResNet, EfficientNet).

Deploy via Flask/Django for real-world usage.

Extend to mobile app for on-device predictions.

