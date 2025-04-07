# UC-Berkeley-AI-certificate-module-17
This is to compare performance of the classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines). I used the data related with direct marketing campaigns of a Portuguese banking institution. The datafile bank-additional-full.csv (https://archive.ics.uci.edu/dataset/222/bank+marketing) with all examples (41188). 

I put below as the business objective while comparising the 4 classifiers. 
Business objective of The task 
1. Build a model to train and predict the campaign results before make the telephone call. 
2. In the case we have only limited resource, or we want to provide better service for these who mostly accept the offer, high prediction accuracy is the goal.

My findings are as below.
1. All knn, decitiontree and logisticregression give high prediction accuracy (around 95%) with less CPU time.
2. DecisionTreeClassifier will be a better choice because it gives the highest recall, meaning less False Negative. We will miss less customers if we try to call the minmila customers.
3. SVC model take the most CPU time, and it gives little bit better prediction accuracy, but the recall score is not as good as decitiontree.
4. decisiontreeclassifier needs grid search to get optimal parameters, otherwise, it is very easy to get overfitting and give poor prediction for test data.
