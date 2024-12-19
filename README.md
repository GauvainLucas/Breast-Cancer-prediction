# Predicting Breast Cancer Using AI

## Overview
This project aims to assist doctors in diagnosing breast cancer by developing machine learning models to classify tumors as malignant or benign. Early detection of breast cancer can significantly improve patient outcomes by enabling faster and more accurate diagnoses.

## Dataset
The project utilizes the **Breast Cancer Wisconsin (Diagnostic) dataset**, accessible through the `sklearn` library. This dataset contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.

- **Features**: 30 numeric features representing various characteristics of cell nuclei.
- **Target**: Binary classification - `0` for malignant and `1` for benign tumors.

## Methods Used
1. **Data Exploration**: Initial exploration, preprocessing of the dataset and understanding feature distributions.

2. **Feature Engineering**: Selected the most relevant features for model training.

3. **Machine Learning Models**:
   - Created and compared two machine learning models: **Logistic Regression** and **Random Forest Classifier**.
   - Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.
   - Researched the best settings to achieve the most accurate results.

4. **Visualization**: Visualized the decision tree, confusion matrix, ROC curves and the feature importance.

## Results
The models provided accurate classifications with promising results. Logistic Regression and Random Forest Classifier both excelled in predictive accuracy.

## Conclusion
This project demonstrates how machine learning can assist in medical diagnostics, providing a robust framework for early cancer detection. 

## Acknowledgments
The dataset is provided by the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). 

