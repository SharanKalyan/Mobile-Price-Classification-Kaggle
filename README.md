# Mobile-Price-Classification-Kaggle

Data Source : https:www.kaggle.com

The data is about a mobile company owner who is not sure how to price his phones strategically. Hence decided to collect the data of the smartphones that have launched recently. The Analysis.ipynb contains the codes from cleanisng to analysing and visualizing and the machine learning models that help classify between the classes. 
The data was 100% balanced between the classes and hence took the accuracy as the metric. 


Here are the metrics :


accuracy : 0.95

confusion matrix :

      [[75  2  0  0]
       [ 1 74  1  0]
       [ 0  3 73  4]
       [ 0  0  4 63]]

classification report :

               precision    recall  f1-score   support

              0       0.99      0.97      0.98        77
              1       0.94      0.97      0.95        76
              2       0.94      0.91      0.92        80
              3       0.94      0.94      0.94        67

    accuracy                              0.95       300
    macro avg         0.95      0.95      0.95       300
    weighted avg      0.95      0.95      0.95       300

