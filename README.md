# Customer churn prediction using ML
* The aim of this project to analyze the bank customer's demographics and financial information which inculdes customer's age, gender. country, credit score, balance and many others to predict whether the customer will leave the bank or not.

* The dataset is taken from [Kaggle](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers?datasetId=797699&sortBy=voteCount). It contains 10000 rows and 14 columns. The objective of the dataset is to predict whether the customer will leave the bank or not, based on the customer's demographics and financial information included in the dataset.

* Implemented Random forest and decision tree classifiers
  
### Conclusions:

* From the exploratory data analysis, I have concluded that the churn count of the customers depends upon the following factors:

      Age
      Geography
      Tenure
      Balance
      Number of Products
      Has Credit Card
      Is Active Member
  
* Coming to the classification models, I have used the following models:

      Decision Tree Classifier
      Random Forest Classifier
  
* Both the models were hyperparameter tuned using _GridSearchCV_. Both the models have nearly equal accuracy score. But, the _Random Forest Classifier_ has a better accuracy and precision score than the Decision Tree Classifier.




