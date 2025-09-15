Music Genre Classification

An AI project to automatically classify the genre of a music track using machine learning.

Project Overview

This project implements a complete pipeline for classifying music into one of ten genres:

blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock

It was developed as part of the internship project phase at Elevate Labs.
The system uses machine learning and deep learning to analyze audio features and predict the correct genre.
A Convolutional Neural Network (CNN) was trained and achieved high accuracy on the test dataset.

Technologies Used

Python – Core programming language

Librosa – Audio analysis and feature extraction

Pandas – Data manipulation and analysis

Scikit-Learn – Data preprocessing (scaling, label encoding)

TensorFlow / Keras – Building, training, and evaluating the CNN model

Joblib – Saving trained models and preprocessing pipelines

Dataset

Dataset: GTZAN Music Genre Dataset

Contents: 1,000 music tracks, 30 seconds each

Genres: 10 (blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock)

Features: Uses features_3_sec.csv (pre-extracted features) for efficient training.

How to Get Started
Prerequisites

Install Python and the required libraries:

pip install pandas scikit-learn numpy librosa tensorflow

Download the Dataset

Get the GTZAN dataset (e.g., from Kaggle) and place
features_3_sec.csv in the same directory as your project files.

Run the Code

Navigate to your project folder and run:

python your_project_file.py


The script will:

Load and preprocess the dataset

Train the CNN model

Provide a prediction for a test audio file

Results & Conclusion

The CNN achieved high accuracy on the test set.

The project delivers a complete pipeline: from data preprocessing to real-time prediction.

Demonstrates skills in:

Audio feature engineering

Traditional machine learning

Deep learning with CNNs

Meets all deliverables required by the internship guidelines.
