# steel-property-classification
Objective: Engineered a classical machine learning pipeline to evaluate and compare the algorithmic performance of multiple classification models on a mechanical steel heat treatment dataset.

Technical Stack:
  Language: Python
  Libraries: Scikit-learn, Pandas, NumPy, Matplotlib

Pipeline Overview:

1.Data Preprocessing: Cleaned mechanical property features and encoded categorical heat treatment labels.

2.Model Evaluation: Trained and compared Support Vector Machines (SVM), Decision Trees, K-Nearest Neighbors (KNN), and Logistic Regression to classify metallurgical outcomes.

3.Performance Metrics: Evaluated models using accuracy, precision, recall, and confusion matrices to determine the optimal classifier for physical material data.

Results:
  Identified Support Vector Machines (SVM) and K-Nearest Neighbors (KNN) as the top-performing algorithms for this dataset, with both models achieving an overall test accuracy of 89.09%.

While overall accuracy was identical, the models showed varied strengths across specific microstructures: KNN achieved a higher F1-score (0.77) for "Quenched and tempered" classifications, whereas SVM proved highly accurate (F1-score 0.95) for general "heat treated" classifications.
