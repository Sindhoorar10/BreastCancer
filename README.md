# Breast Cancer Research Project

## Description
This research project aims to explore different machine learning models for breast cancer classification. The [dataset](https://doi.org/10.24432/C5DW2B) used in this project contains features extracted from digitized images of fine needle aspirates (FNA) of breast masses. The target variable represents the diagnosis as either benign (B) or malignant (M).

## Dataset 
The dataset used for this project is loaded from the file 'wdbc.data', which contains the breast cancer data in CSV format. The features are extracted from columns 3 to the end, and the target variable is extracted from column 2. Categorical data for the target variable is encoded using label encoding.

## Models Used
The following machine learning models are utilized for breast cancer classification:
1. K-Nearest Neighbors (K-NN) Classifier
2. Naive Bayes Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM) with Linear Kernel
5. Support Vector Machine (SVM) with Radial Basis Function (RBF) Kernel

## Model Evaluation
The accuracy of each model is evaluated using the test set. The accuracy scores achieved by each model on the test set are as follows:
- K-NN Accuracy: 0.9225
- Naive Bayes Accuracy: 0.9366
- Random Forest Accuracy: 0.9577
- SVM (Linear) Accuracy: 0.9507
- SVM (RBF) Accuracy: 0.9014

## Results Visualization
### Accuracy Comparison
A bar plot is generated to compare the accuracies of different models on the test set.

### Confusion Matrices
The confusion matrices for each model are displayed to visualize the true positive, true negative, false positive, and false negative predictions.

### ROC Curves and AUC Scores
Receiver Operating Characteristic (ROC) curves are plotted for each model to show the trade-off between the true positive rate and the false positive rate. The Area Under the ROC Curve (AUC) is also calculated for each model, indicating the overall performance.

### Precision-Recall Curves and Average Precision Scores
Precision-Recall curves are plotted for each model, showing the relationship between precision and recall at different thresholds. The Average Precision (AP) score is calculated to assess the overall precision-recall performance of each model.

## Conclusion
The research project demonstrates the use of various machine learning models for breast cancer classification. The Random Forest model achieved the highest accuracy among the models tested. Further analysis of precision-recall trade-offs and ROC curves provides additional insights into the models' performance.
