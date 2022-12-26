# Medicare-Fraud-Detection-PySpark-

I did the healthcare provider fraud detection analysis. Healthcare fraud is an organized crime which involves peers of providers, physicians, beneficiaries acting together to make fraud claims. Fraud detection is really important for companies because fraud attacks take on many forms and affect business differently. As the datasets for fraud detections are generally imbalanced, it is very important to balance the classes before training the model, or the accuracy of the model will be high as it will be able to correctly classify the majority class but will not be able to perform in case of the minor class. And this is the same reason that the F1 score which is highly correlated with the precision and recall as well as the auc values are the better metrics to check the performance of the model. We also believe that by tuning the hyperparameters we can enhance the model performance. And randomized search is a good tool to achieve that.

Dataset- https://www.kaggle.com/rohitrox/healthcare-provider-fraud-detection-analysis

I have used pyspark to classify fradulant records and applied concepts of data balancing, hyperparameter tuning for Random Forest Model and using Random Search to optimize the performance of the model.
