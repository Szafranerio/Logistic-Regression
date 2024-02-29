Logistic Regression is a variation of Linear Regression, used when the observed dependent variable, y, is categorical. 
It produces a formula that predicts the probability of the class label as a function of the independent variables. It is good for:

1. Binary Classification: Predicting outcomes with two possible classes.
2. Probabilistic Interpretation: Providing probability estimates for class membership.
3. Interpretability: Easy to interpret and understand the relationship between input features and the predicted outcome.
4. Scalability: Can handle large datasets efficiently.
5. Regularization: Easily incorporate regularization techniques to prevent overfitting.
6. Feature Importance: Identifying important features for classification.

*Things to remember:*
- Regularization parameters (e.g., C) can be adjusted to control overfitting.
- Logistic regression assumes a linear relationship between the features and the log-odds of the outcome.

This project is divided into three separate files for logistic regression analysis based on:
1. Advertising (Add clicking patter).
2. Chrun Data (Are you done with subscription?).
3. Titanic (Survive patter).

*Methodology:*
1. Download required libraries (Pandas, NumPy, Scikit-learn, Matplotlib).
2. Load and explore the interesting data.
3. Understand the data and perform basic visualization and data wrangling.
4. Define the features (X) and target (y) variables for analysis.
5. Split the data into training and testing sets.
6. Build logistic regression models.
7. Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
8. Analyze feature importance and model coefficients to interpret the results.

**IMPORTANT**

1. **Accuracy**: It's the ratio of correctly predicted instances to the total number of instances.
In simpler terms, accuracy tells us how often the classifier is correct.
It's calculated as: (TP + TN) / (TP + TN + FP + FN), where TP is True Positives, TN is True Negatives, FP is False Positives, and FN is False Negatives.

2. **Precision**: Precision tells us what proportion of positive identifications was actually correct.
In other words, it's the ratio of correctly predicted positive observations to the total predicted positives. It's calculated as: TP / (TP + FP).

3. **Recall**: Recall, also known as sensitivity or true positive rate, tells us what proportion of actual positives was correctly identified.
It's the ratio of correctly predicted positive observations to all actual positives. It's calculated as: TP / (TP + FN).

4. **F1-score**: The F1-score is the harmonic mean of precision and recall. It's a single metric that combines both precision and recall into one score.
It provides a balance between precision and recall. F1-score is calculated as: 2 * ((Precision * Recall) / (Precision + Recall)).

