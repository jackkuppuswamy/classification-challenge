# Spam Detection Model

## Overview
This project explores two different machine learning models, `Logistic Regression` and `Random Forest Classifier`, to classify emails as spam or not spam and evaluates which model perfoms better in detecting spam emails.

## The model development and evaluation is performed using the following steps:

### Data Loading and Exploration
- The spam dataset available in UCI Machine Learning Library is loaded, and initial data exploration is performed to understand the features and target (spam classification).

### Model Training
- The dataset is split into training and testing sets using train_test_split.
- Features are scaled using StandardScaler.
- Two models are trained:
    - Logistic Regression: A common baseline model for classification.
    - Random Forest Classifier: An ensemble-based classifier known for its robustness in various tasks.

### Model Evaluation
- Both models are evaluated on the test dataset.
- The accuracy of the Logistic Regression model is 92.3%.
- The accuracy of the Random Forest model is 95.8%, outperforming Logistic Regression.

### Conclusion
The Random Forest model is deemed more suitable for this task due to its higher accuracy in detecting spam.

### References:
Hopkins, M., Reeber, E., Forman, G., & Suermondt, J. (1999). Spambase [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C53G6X.
