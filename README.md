# Twitter-sentiment-analysis
This is a self-project.The aim is to identify sexist/racist tweets in a given dataset.This was done by first preprocessing the dataset.Then we
did removed unwanted symbols,performed stemming and removed words of length<3.<br>
Following which,4 techniques for feature extraction are  used:<br>
1)BOW<br>
2)TI-IDF<br>
3)WORDS TO VECTOR<br>
3)DOC TO VECTOR<br>
We then performed logistic regression,random forest,SVM,XGboost.<br>
The Xgboost with WORDS TO VECTOR features performed the best and gave a accuracy of 60.2%.<br>
We could try Naive bayes classifier,KNN,and other algorithms.Also,We can give pretrained word-embeddings models a try.<br>
