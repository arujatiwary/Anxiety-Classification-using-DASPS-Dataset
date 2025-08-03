# EEG-Based Anxiety Classification

This project explores the use of machine learning techniques to classify anxiety levels based on EEG features. Using the DASPS dataset, EEG recordings from 23 participants were analyzed and labeled as either "Normal" or "Ansiedade Severa."

Features such as mean, median, standard deviation, variance, energy, and power spectral density were extracted from the signals. Two models were implemented: a Random Forest classifier and a Multi-Layer Perceptron (MLP). The dataset was balanced using SMOTE to address class imbalance before training.

The Random Forest model achieved the highest accuracy of 96.5%, followed closely by the MLP at 95.5%. All code and results are contained in the Jupyter Notebook 'Anxiety_Classification.ipynb'.

