In this study, SVM for classification and Ridge and Lasso regression models for prediction were applied to optimize predictive performance.
While Lasso regression (L1 regularization) chooses important characteristics by setting
certain coefficients to zero, Ridge regression (L2 regularization) lowers coefficient magnitudes without
removing features.
Dataset details:
Dataset: UCI HAR Dataset (561 features, 10,299 instances).
The dataset is split into:
Training Set - 70% of the data
Testing Set - 30% of the data
The main files in the dataset are:
• X_train.txt and X_test.txt → Features for training and testing
• y_train.txt and y_test.txt → Activity labels for training and testing
• features.txt → Names of all 561 feature columns
• activity_labels.txt → Mapping of numerical activity labels to activity names
