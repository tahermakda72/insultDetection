# insultDetection
Here,we can see 6 file from which 3 are dataset files and another 3 are jupyter notebook file.
train.csv and test_with_solution.csv are the dataset file taken from the kaggle dataset and it is used for creating standard models like SVM,Naive-Bayes,Logistic Regression,K-means,AdaBoost,Decision Tree and Random Forest in insult_Detection.ipynb file and another insult_detection_bert.ipynb is for creating the BERT model.<br>
The Result of the standard Models in insult_detection.ipynb have highest AUC score is 0.7358 which is achieved by Linear SVC which can seen in the results of insult_Detection.ipynb program.<br>
To increase the AUC score,We have implemented the BERT which uses Fine-tuning unsupervised pre-trained model that gives better classification than another models. insult_detection_bert.ipynb is the implemented code of BERT model.<br>
At Last,insultDetection_kmeans.ipynb is the implementation of kmeans clustering from the scratch.For this,we used another dataset kmeans_data.csv because the kaggle dataset after performing the TF-IDF operation on the comment-statement,it was giving the metrix which have different dimension for every row,So that metrix can not apply on the kmeans method.<br>
That's why we use kmeans_data.csv for Kmeans clustering and it is giving the AUC score 0.5.  

