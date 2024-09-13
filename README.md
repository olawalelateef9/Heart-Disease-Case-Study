# Heart-Disease-Case-Study
This repository contains a machine learning project for Peterside Hospital aimed at predicting the likelihood of heart disease based on various medical features. The goal is to build predictive models that can assist healthcare professionals in identifying individuals at risk of heart disease, enabling timely intervention and treatment.

This heart disease prediction analysis evaluates the performance of various machine learning models on predicting the likelihood of heart disease. Early and accurate prediction of heart disease is crucial for preventive healthcare and improving patient outcomes. The analysis used key performance metrics such as accuracy, precision, recall, F1-score, and the Area Under the Receiver Operating Characteristic curve (AUC-ROC) to assess the models' effectiveness.

Below is a summary of the results for the Logistic Regression and Random Forest Classifier:

1. Logistic Regression
Accuracy: 85.25%
Precision: 0.8710
Recall: 0.8438
F1-Score: 0.8571
AUC-ROC: 0.8529
Logistic Regression performed well with an accuracy of 85.25%, showing that the model correctly identified 85% of the heart disease cases. A precision score of 0.8710 indicates that 87% of the patients predicted to have heart disease were correctly identified. The recall value of 0.8438 shows that the model captured a high proportion of actual heart disease cases. The F1-score of 0.8571 demonstrates a good balance between precision and recall, and the AUC-ROC score of 0.8529 suggests the model effectively discriminates between positive (heart disease) and negative cases.

2. Random Forest Classifier
Accuracy: 85.25%
Precision: 0.8485
Recall: 0.8750
F1-Score: 0.8615
AUC-ROC: 0.8513
The Random Forest Classifier also achieved an accuracy of 85.25%, similar to Logistic Regression. It had slightly lower precision (0.8485), but outperformed Logistic Regression in recall (0.8750), meaning it was more successful in identifying actual heart disease cases. The F1-score of 0.8615 indicates strong overall performance, balancing precision and recall. The AUC-ROC score of 0.8513 is comparable to that of Logistic Regression, demonstrating the model's ability to differentiate between heart disease and non-heart disease cases.

Conclusion
Both models performed equally well in terms of accuracy, with scores of 85.25%. Logistic Regression had a slight edge in precision, while the Random Forest model had a higher recall, meaning it identified more actual cases of heart disease. Both models offer strong performance, and the choice between them may depend on the specific needs of the application—Logistic Regression for fewer false positives (higher precision) or Random Forest for capturing more true positives (higher recall).
