Music Genre Classification
An AI project to automatically classify the genre of a music track using machine learning.

1. Project Overview
This project implements a complete pipeline for classifying music into one of ten genres (blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, and rock). Developed as part of an internship, the system analyzes audio features to predict a song's genre. It uses a Convolutional Neural Network (CNN) for classification, which is a powerful deep learning model well-suited for this task.

2. Technologies Used
Python: The core programming language for the entire project.

Librosa: A crucial library for audio analysis and feature extraction.

Pandas: Used for data manipulation and analysis of the pre-extracted features.

Scikit-Learn: Utilized for data preprocessing, including scaling and label encoding.

TensorFlow/Keras: The deep learning framework used to build and train the CNN model.

Joblib: Used to save the trained model and preprocessing pipelines for future use.

3. Dataset
The project uses the GTZAN Music Genre Dataset, a standard collection of audio files. The dataset contains 1,000 music tracks, each 30 seconds in length, distributed evenly across 10 genres. The provided features_3_sec.csv file, which contains pre-extracted features, is used for efficient model training.

4. How to Get Started
To run this project, follow these steps on your local machine.

Prerequisites
Install the necessary Python libraries using pip:

Bash

pip install pandas scikit-learn numpy librosa tensorflow
Running the Code
Download the GTZAN dataset. Ensure the features_3_sec.csv file is in the same directory as your project code.

Execute the main Python script from your terminal.

The script will handle all steps from data loading to model training and will provide a final genre prediction for a test audio file.

5. Conclusion
This project successfully demonstrates a complete pipeline for music genre classification. The trained model, along with the real-time detection script, meets all the project's deliverables. The system showcases skills in both traditional machine learning and deep learning applications.







