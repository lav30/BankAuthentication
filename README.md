## How to find out which machine learning algorithm out of many, performs better than the rest?

The above can be resolved using hypothesis testing which can be used to determine the statistical significance of the results obtained. In this project, several classifiers have been trained on the bank note authentication dataset to determine which model performs better over the others, considering that the metrics alone cannot be used to determine a model's generalization capabilities. 

- **Dataset** : [Link](https://archive.ics.uci.edu/ml/datasets/banknote+authentication) to the dataset that consists of quantitative features extracted from images of authentic and forged/fraudulent bank notes. 

- **Algorithms Used** : Logistic Regression, KNN and Random Forest Classifier

- **Data Preprocessing** : Features have been normalized and no missing values are present.

- **Initial Results**

**Algorithm** | **Mean Accuracy (%)** |
------------ | ------------- |
Logistic Regression | 98.3
Random Forest Classifier| 99.27
K-Nearest Neighbors | 99.72

![Alt Text](Files/Accmean.png)

- **Hypothesis Testing** : Comparing 2 models at a time, hypothesis testing has been performed to determine the statistical significance of the results obtained. 

