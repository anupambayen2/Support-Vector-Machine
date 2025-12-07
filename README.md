Project Summary: Customer Purchase Prediction Using Support Vector Machine (SVM)

This project applies Support Vector Machine (SVM) classification to predict whether a user will purchase a product based on social network advertisement data. It is part of my daily machine learning practice uploads on GitHub.

📌 Objective

To build a classification model using SVM that finds the optimal decision boundary (hyperplane) separating buyers and non-buyers.

📊 Dataset

Dataset used: Social_Network_Ads.csv

Features used:

Age

Estimated Salary

Target:

Purchased (0 or 1)

SVM is ideal for datasets where classes are not linearly separable.

🛠️ Steps Performed

Loaded and cleaned the dataset

Selected relevant features

Split into training and testing sets

Applied feature scaling (critical for SVM)

Trained an SVM classifier (usually with an RBF kernel)

Predicted the target on test data

Evaluated performance using:

Confusion Matrix

Accuracy Score

Visualized classification decision boundaries

📈 Key Insight

The RBF kernel captures complex, non-linear patterns in the dataset.

SVM creates a decision boundary that maximizes the margin between classes.

Performs better than KNN and Logistic Regression when the data is not linearly separable.

Scaling greatly improves SVM performance.

🧪 Outputs

Confusion matrix

Accuracy score

Predicted results

Decision boundary plot

🚀 Conclusion

Support Vector Machine is a powerful and flexible classification algorithm capable of modeling non-linear boundaries. On this dataset, SVM demonstrates strong performance and cleanly separates buyers from non-buyers.
