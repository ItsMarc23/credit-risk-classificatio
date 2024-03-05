This study aims to evaluate the predictive capabilities of two computer models in determining the risk associated with loans based on financial data. Factors such as loan size, interest rates, and borrower income are considered to categorize loans as safe (0) or risky (1).

The dataset is split into two segments for training and testing purposes. Initially, a model is developed using the original dataset, and its accuracy, precision, and recall are assessed. To address data imbalances, additional instances are generated using RandomOverSampler. Subsequently, a second model is built using the augmented, balanced data, and its performance is evaluated using the same metrics. Both LogisticRegression and RandomOverSampler methods are employed in this study.

Results:

Machine Learning Model 1 with Original Data:

Precision: 100% accuracy in predicting healthy loans, 87% accuracy in predicting high-risk loans
Accuracy: 94% balanced accuracy score
Recall: 100% recall for healthy loans, 89% recall for high-risk loans
Machine Learning Model 2 with Resampled Data:

Precision: 100% accuracy in predicting healthy loans, 87% accuracy in predicting high-risk loans
Accuracy: 99% balanced accuracy score
Recall: 100% recall for healthy loans, 100% recall for high-risk loans
Summary:
Model 2, trained with balanced resampled data, demonstrates superior performance over Model 1, particularly in identifying high-risk loans. Therefore, Model 2 is recommended for adoption. This recommendation holds significance for financial institutions seeking to mitigate risks and losses during loan approval processesThis study aims to evaluate the predictive capabilities of two computer models in determining the risk associated with loans based on financial data. Factors such as loan size, interest rates, and borrower income are considered to categorize loans as safe (0) or risky (1).

The dataset is split into two segments for training and testing purposes. Initially, a model is developed using the original dataset, and its accuracy, precision, and recall are assessed. To address data imbalances, additional instances are generated using RandomOverSampler. Subsequently, a second model is built using the augmented, balanced data, and its performance is evaluated using the same metrics. Both LogisticRegression and RandomOverSampler methods are employed in this study.

Results:

Machine Learning Model 1 with Original Data:

Precision: 100% accuracy in predicting healthy loans, 87% accuracy in predicting high-risk loans
Accuracy: 94% balanced accuracy score
Recall: 100% recall for healthy loans, 89% recall for high-risk loans
Machine Learning Model 2 with Resampled Data:

Precision: 100% accuracy in predicting healthy loans, 87% accuracy in predicting high-risk loans
Accuracy: 99% balanced accuracy score
Recall: 100% recall for healthy loans, 100% recall for high-risk loans
Summary:
Model 2, trained with balanced resampled data, demonstrates superior performance over Model 1, particularly in identifying high-risk loans. Therefore, Model 2 is recommended for adoption. This recommendation holds significance for financial institutions seeking to mitigate risks and losses during loan approval processes
