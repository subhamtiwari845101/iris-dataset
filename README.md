Task 1 — Iris Flower Classification

CodeAlpha · Data Science Internship

📌 Project Overview

This project performs classification of Iris flowers into three species:

Iris-setosa

Iris-versicolor

Iris-virginica

The model uses machine learning to classify flower species based on sepal and petal measurements.
Your dataset (Iris.csv) contains 150 samples with 5 input features.

This is one of the required tasks for the CodeAlpha Data Science Internship.

📂 Dataset Description

Dataset: Iris.csv

Column Name	Description
SepalLengthCm	Sepal length (cm)
SepalWidthCm	Sepal width (cm)
PetalLengthCm	Petal length (cm)
PetalWidthCm	Petal width (cm)
Species	Target class
Id	Unique identifier (removed during preprocessing)

There are 3 classes in the Species column:

Iris-setosa

Iris-versicolor

Iris-virginica

🎯 Objective

To build a machine learning model that:

Reads the Iris dataset

Preprocesses the data

Trains a classifier

Predicts flower species

Evaluates accuracy and classification performance

🧠 Machine Learning Approach
✔ Step 1 — Data Loading

Imported Iris.csv and removed the unnecessary Id column.

✔ Step 2 — Label Encoding

Converted species names into numeric labels using LabelEncoder.

✔ Step 3 — Feature Scaling

Used StandardScaler to normalize numeric features.

✔ Step 4 — Model Used

Random Forest Classifier

Fast

High accuracy

Handles non-linearity

Works well for small/medium datasets

✔ Step 5 — Evaluation

Used:

Accuracy Score

Classification Report

Confusion Matrix

Feature Importance

📊 Model Performance
Metric	Score
Accuracy	~0.8947 (89.47%)

The model performs well and distinguishes Iris species with high reliability
