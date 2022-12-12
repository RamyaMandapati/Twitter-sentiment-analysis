# Twitter-Sentimental-Analysis

Twitter Real-Time Sentimental Analysis:
* 1. Twitter Data has been collected from Twitter API and Tweepy Module
* 2.  Pre Processing Steps have been applied to clean the data and make the data more readable by the model.
* 3. Below machine learning are used :
   a) LogisticRegression
   b) DecisionTreeClassifier
   c) RandomForestClassifier
   d) Bernoulli Naive Bayes
   e) BERT model
* 4. The model is exported as a pickle file.
* 5. Used StreamLit for the deployment of the model and hosted it on GitHub.

![image](https://github.com/rajuptvs/Twitter-Sentimental-Analysis-with-StreamLit/blob/main/images/streamlit_home.png)
![image](https://github.com/rajuptvs/Twitter-Sentimental-Analysis-with-StreamLit/blob/main/images/streamlit_results.png)

## Best model, that we were able to get from the above models were LogisticRegression and the BERT Model but BERT model had a very high validation loss and lower accuracy probably because of the smaller dataset hence proceeded with the deployment of LogisticRegression.
![image](https://github.com/rajuptvs/Twitter-Sentimental-Analysis-with-StreamLit/blob/main/images/confusionmatrix.jpg)
![image](https://github.com/rajuptvs/Twitter-Sentimental-Analysis-with-StreamLit/blob/main/images/Eval.jpg)




