# Task 4 - Classification with Logistic Regression

## Objective
Build a binary classification model using Logistic Regression.

## Dataset
Breast Cancer Wisconsin Dataset from Scikit-learn.

## Methodology
1. Loaded the Breast Cancer dataset.
2. Split the dataset into training and testing sets.
3. Applied StandardScaler for feature scaling.
4. Trained a Logistic Regression model.
5. Generated predictions and probability scores.
6. Evaluated the model using Accuracy, Precision, Recall and F1-score.
7. Created a Confusion Matrix.
8. Calculated ROC-AUC and plotted the ROC Curve.
9. Performed threshold tuning using different probability thresholds.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## Sigmoid Function
Logistic Regression uses the sigmoid function to convert the model output into a probability between 0 and 1.

sigmoid(z) = 1 / (1 + e^(-z))

A threshold is then used to convert the probability into a binary class prediction.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Files
- `Task_4_Logistic_Regression.ipynb` - Complete Python implementation of the Logistic Regression classification task.
- `README.md` - Project description and methodology.

## Conclusion
The Logistic Regression model was successfully trained on the Breast Cancer Wisconsin dataset. The model was evaluated using multiple classification metrics, ROC-AUC, Confusion Matrix and threshold tuning.
