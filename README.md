## Logistic Regression for Breast Cancer Prediction
This project demonstrates the implementation of Logistic Regression to classify breast cancer cases based on the dataset **_breast_cancer.csv_**.

1. **Data Preprocessing**:
The dataset is imported, and features (**X**) and the target variable (**y**) are extracted.
The data is split into training and test sets using an **80-20** split.

2. **Model Training**:
A Logistic Regression model is trained on the training dataset using the _**LogisticRegression**_ class from sklearn.
Prediction and Evaluation:

3. The model **predicts** outcomes for the test set.
A _Confusion Matrix_ is generated, showcasing the performance of the model. The accuracy achieved is **95.62%**.
Model Validation:

4. **k-Fold** Cross Validation is applied to evaluate the model's performance across **10** folds.
The model achieved an average accuracy of **96.70%** with a standard deviation of **1.97%**, indicating consistent performance.
