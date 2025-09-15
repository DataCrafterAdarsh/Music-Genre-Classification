Music Genre Classification
An AI project to automatically classify the genre of a music track using machine learning.

1. Project Overview
This project presents a complete implementation for classifying music into one of ten genres (blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, and rock). It was built as a part of the internship project phase at Elevate Labs. The system utilizes machine learning to analyze audio features and predict the correct genre. The primary model used is a Convolutional Neural Network (CNN), which demonstrated a high level of accuracy on the test dataset.

2. Technologies Used
Python: The core programming language for the entire project.

Librosa: A crucial library for audio analysis and feature extraction from the raw audio files.

Pandas: Used for data manipulation and analysis of the pre-extracted features.

Scikit-Learn: Utilized for data preprocessing, including scaling and label encoding.

TensorFlow/Keras: The deep learning framework used to build, train, and evaluate the CNN model.

Joblib: Used to save the trained model and preprocessing pipelines for future use.

3. Dataset
This project uses the GTZAN Music Genre Dataset, a standard collection of audio files specifically for this task. The dataset contains 1,000 music tracks, each 30 seconds in length, distributed equally across 10 genres. The project uses the pre-extracted features provided in the features_3_sec.csv file for efficient model training.

4. How to Get Started
To run this project on your local machine, follow these steps:

Prerequisites
You'll need to have Python and the following libraries installed. You can install them using pip:

Bash

pip install pandas scikit-learn numpy librosa tensorflow
Running the Code
Download the Dataset: Download the GTZAN dataset from a source like Kaggle. Ensure the features_3_sec.csv file is placed in the same directory as the project code.

Execute the Script: Open your terminal and navigate to the project directory. Run the main Python script:

Bash

python your_project_file.py
The script will handle the data loading, model training, and will provide a final prediction for a test audio file.

5. Results and Conclusion
The CNN model achieved a high test accuracy, demonstrating its effectiveness in classifying music genres. The project successfully delivers a complete and functional pipeline, from data preprocessing to real-time prediction, showcasing skills in both traditional machine learning and deep learning. This project meets all the deliverables as required by the internship guidelines.
