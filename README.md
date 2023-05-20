# Linear-SVM-Implementation-Baseed-on-Kaggle-Competition
This repository contains the implementation of a linear Support Vector Machine (SVM) for a binary classification task in the DDA4210 Advanced machine learning mini project. The goal of the project is to train a machine learning model to separate two classes based on the given features.
Implementation Steps:
1. Library Import: The required libraries, including pandas, scikit-learn (sklearn), and matplotlib, are imported for data manipulation, machine learning algorithms, and visualization.
2. Exploratory Data Analysis: The relationships between the features are plotted to understand their dependencies.
3. Feature Significance: The distribution of the binary label across different features is analyzed to identify the most significant features.
4. Outlier Detection: The training data is examined for outliers, and specifically, the distinction between the maximum values of feature 3 and feature 4 is observed compared to the test data.
5. Outlier Removal: The identified outliers are removed from the training data.
6. Data Normalization: The training and test data are normalized based on the maximum value of each feature.
7. Feature Selection: Unnecessary features, such as the label and example ID, are dropped from the training data, while the label column is selected as the target.
8. Model Selection: The linear SVM algorithm is chosen as the machine learning model due to its ability to find the best boundary for separating two classes.
9. Prediction: A new data frame is created for the X values to be predicted by the trained model.
10. Result Presentation: The predicted data is attached to the data frame with the column name "example_id".

The project report includes additional information, such as the plotted training and test data, the relationship plot between feature 2 and 4, and the distribution of the binary label.

Feel free to explore the repository and review the code and report for further insights into the implementation process.

If you have any questions or suggestions, please feel free to reach out.
