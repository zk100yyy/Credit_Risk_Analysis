# Credit_Risk_Analysis
The written analysis has the following:

The purpose of this analysis is well defined
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


Results:

The BalancedRandomForestClassifier algorithm does the following:

          An accuracy score for the model is calculated
          
          A confusion matrix has been generated
          
          An imbalanced classification report has been generated
          
          The features are sorted in descending order by feature importance
          
          The EasyEnsembleClassifier algorithm does the following:

An accuracy score of the model is calculated



      A confusion matrix has been generated
      An imbalanced classification report has been generated



## various techniques used to predictive model for High-Risk loans.

![image](https://user-images.githubusercontent.com/93456209/158084658-66e8173c-139a-43d5-8040-265221833b99.png)


![image](https://user-images.githubusercontent.com/93456209/158084677-c35b4534-deb5-4bd4-84f2-e9a56efe7d90.png)


![image](https://user-images.githubusercontent.com/93456209/158084706-1ae97a0d-6135-4cc9-93b1-fd1ccf2a33b5.png)


SMOTEENN


![image](https://user-images.githubusercontent.com/93456209/158084727-250f2423-25d9-48da-af22-872d8fa35f70.png)




Summary:


In the high-risk loan class, all the machine learning models had low precision scores as a function of accurately predicting positives. In the balanced accuracy score, the undersampling model had the lowest score and the AdaBoost classifier had a high score.AdaBoost Classifier would be the best model to use to predict credit risk due to the high recall scores for both high and low risk loans.
