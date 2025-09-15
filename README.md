# Breast-Cancer-Prediction
Overview
This project focuses on predicting breast cancer diagnosis (malignant or benign) using machine learning. The primary algorithm employed is the Random Forest Classifier, which was trained and evaluated on a breast cancer dataset.
Dataset
•	Source: Breast Cancer dataset (loaded from scikit-learn).
•	Features: Tumor characteristics such as mean radius, mean texture, mean perimeter, mean area,  mean smoothness, mean compactness, mean concavity,  mean concave points, mean symmetry, mean fractal dimension,  radius error, texture error, perimeter error, area error, smoothness error, compactness error, concavity error,  concave points error, symmetry error, fractal dimension error, worst radius, worst texture,  worst perimeter, worst area, worst smoothness,  worst compactness, worst concavity, worst concave points, worst symmetry, worst fractal dimension
•	Target: Binary classification — Malignant (1) or Benign (0).
Methodology
1.	Data Loading & Exploration
o	Dataset imported (breast cancer features and labels).
o	Basic exploration and inspection of features.
2.	Data Preprocessing
o	Split into training and test sets.
o	Features and labels prepared for modeling.
3.	Model Training
o	Random Forest Classifier implemented.
o	Model trained on the training set.
4.	Evaluation
o	Predictions made on the test set.
o	Performance measured with:
	Accuracy Score
	Confusion Matrix
Results
•	The Random Forest model achieved a strong performance of 0.98.
•	Detailed classification metrics and a confusion matrix are included in the notebook.
How to Run
1.	Clone or download this repository.
2.	Open the notebook:
3.	Jupyter Notebook FlexiSaf_Deliverable_Task1.ipynb
4.	Run all cells to reproduce the results.
Dependencies
•	Python 3.x
•	Jupyter Notebook
•	scikit-learn
•	pandas
•	numpy
•	matplotlib / seaborn

