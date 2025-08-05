Physics Motion Classifier

This project classifies uniform, accelerated, and oscillatory motion using physics-based features: displacement, velocity, acceleration, and time.

Overview
The notebook demonstrates how different types of classical motion can be simulated, visualized, and classified using Python. The project includes data generation, feature extraction, visualization, and classification using a Decision Tree model.

Features Used

Time

Displacement

Velocity

Acceleration

Model

Algorithm: Decision Tree Classifier

Accuracy: 100% on the test set (after train-test split)

Evaluation: All predictions were correct

Confusion Matrix: No misclassifications

Precision / Recall / F1-score: 1.00 for all classes

Feature Importance: Acceleration contributed most to the model's predictions

Key Findings

Acceleration is the strongest predictor of motion type

Motion classes are clearly separable using simple physics features

Oscillatory motion is more scattered and harder to model visually, but still classified correctly by the model

PCA confirmed the structure and separability of the dataset

Purpose
This project connects machine learning with classical physics, showing how motion patterns can be understood and classified using basic data science tools. It serves as a demonstration of how physics concepts can be explored computationally.
