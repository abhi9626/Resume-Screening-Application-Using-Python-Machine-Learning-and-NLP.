# Resume-Screening-Application-Using-Python-Machine-Learning-and-NLP.

# Project Overview

In this project, the objective was to develop a system that automatically categorizes resumes into specific job categories based on their content. Here's a detailed summary of the technical steps and outcomes:

# Data Preparation and Exploration
Dataset Loading and Exploration:
The dataset containing resumes and their corresponding job categories was loaded using Pandas. Initial exploration involved checking the shape of the dataset and visualizing the distribution of resume entries across different job roles using matplotlib and seaborn.

# Text Preprocessing
Cleaning Resumes:
Resumes underwent extensive cleaning to ensure standardized text inputs for analysis. This involved removing URLs, special characters, punctuation, and non-ASCII characters using regular expressions (regex).

# Feature Extraction
TF-IDF Vectorization:
TF-IDF (Term Frequency-Inverse Document Frequency) vectorization was employed to convert cleaned text resumes into numerical feature vectors. This technique assigns weights to words based on their importance in individual resumes relative to the entire dataset, capturing unique content characteristics.

# Model Training and Evaluation
Classifier Selection:
A K-Nearest Neighbors (KNN) classifier was chosen for multi-class classification to predict job categories from the TF-IDF transformed features.

# Model Evaluation:
The trained classifier was evaluated using accuracy metrics on a test set to assess its performance in accurately categorizing resumes into job roles.

# Model Deployment
Saving Model Artifacts:
The trained TF-IDF vectorizer and KNN classifier were serialized using pickle for deployment.

# Prediction System:
A prediction system was developed where new resumes can be inputted, cleaned, vectorized using the saved TF-IDF vectorizer, and classified into the appropriate job category using the deployed KNN classifier.

# Outcome
System Capabilities:
Successfully developed a scalable system capable of automating the categorization of new resumes into predefined job categories with high accuracy.
This project demonstrates the practical application of natural language processing (NLP) and machine learning (ML) techniques in the domain of resume analysis, facilitating more efficient and objective recruitment practices.
