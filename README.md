# UC-Berkeley-AI-certificate-module-17
This is to compare performance of the classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines). I used the data related with direct marketing campaigns of a Portuguese banking institution. The datafile bank-additional-full.csv (https://archive.ics.uci.edu/dataset/222/bank+marketing) with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed. 

I put below as the business objective while comparising the 4 classifiers. My finding is that logistic regression model gives very high prediction accuracy (~ 94.9%) and low racall (6.5%) with not too much computation time. The bank can reduce human resource to call customers significantly (about 94.8% because acceptance rate is only 5.2%) by the prediction results. 

Business objective of The task 
1. Build a model to train and predict the campaign results before make the telephone call. 
2. Assume we have enough resource to make the phone call. We do not want to miss any succesful compaigns, meaning we need to minimize false negatives.  Recall measures the proportion of actual positives that were correctly identified.
Recall = TP / (TP + FN), we want a high Recall, i.e. less FN.

Please note if we have only limited resource to make the phone call, then the object will be maximize the TP, meamimng just call the customers who mostly accept the offer.
