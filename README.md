**UCI_credit_card_default**

I analyse the UCI credit card default dataset available at: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#.
In this project, I perform the following:

Exploratory Data Analysis (EDA): I explore the dataset, handling missing values, identifying outliers, and analyzing the distribution of features and the target variable.
Feature Engineering: I use various data visualization techniques, such as heatmaps, count plots, and density plots, to gain insights into the relationships between the features and the target variable.
Model Development: I implement a Logistic Regression model to predict the likelihood of default payment. The model's performance is evaluated using accuracy, classification report, and confusion matrix.
Model Comparison: I utilize the LazyClassifier library to quickly evaluate and compare the performance of multiple machine learning models, including Logistic Regression, Decision Tree, Random Forest, and others.
Model Persistence: I save the trained Logistic Regression model to a file using the pickle library, allowing for easy reuse and deployment.
