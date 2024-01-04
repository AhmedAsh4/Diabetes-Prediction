# Diabetes-Prediction <br>
Made as a project for AI443 (Machine Learning) <br><br>

The diabetes prediction project focuses on utilizing machine learning to predict diabetes risk based on health-related data. The methodology involves: <br><br>

1)Data Cleaning: Identifying and rectifying inconsistencies, converting certain features into categorical variables, and eliminating duplicates.<br>

2)Data Preparation: Preprocessing data by scaling numerical variables and applying One Hot Encoding to categorical ones.<br>

3)Algorithm Selection: Using GridSearch to optimize parameters for multiple classifiers based on a sampled dataset.<br>

4)Model Evaluation: Assessing algorithm performance using metrics like Accuracy, F1 Score, Recall, Precision, Specificity, and NPV.<br>

5)Handling Imbalanced Data: Comparing techniques like SMOTE and RandomUnderSampler to address dataset imbalance.<br>

The best-performing model, XGBoost Classifier, achieved an accuracy of 0.916. Post-balancing techniques, the up-sampled data model improved performance significantly, reaching an accuracy of 0.956.
