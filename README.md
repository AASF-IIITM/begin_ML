# begin_ML
   # Toxic Comment Classifier
              # -- Siddhant Srivastava Sir
   
This is a basic NLP (Natural Language Processing) problem .... solved by applying some Machine Learning Models .

Problem Description:
Here provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

1. toxic
2. severe_toxic
3. obscene
4. threat
5. insult
6. identity_hate

You must create a model which predicts a probability of each type of toxicity for each comment.

Solution Code on Online Kernel : 
https://www.kaggle.com/bcs013/simple-stepwise-solution


Applied Models :

Since this is a multi-classification problem so here applied classifications models.
Following are the five underlying applied models with their training accuracy -----

1) Multinomial Naive Bayes  ---  0.8980026678842246
2) Bernoulli Naive Bayes    ---  0.8892022309958012
3) Ridge Classifier         ---  0.9357469628197208
4) Logistic Regression      ---  0.9205812048451643
5) SVM Classifier           ---  0.9967949578778682

Conclusion :

So as we can see that SVM Classifier gives the highest accuracy rate on training dataset ,
that's why I pick up this classifier and then tuning the parameters of this on cross-validation data 
I get my best parameter as C = 0.3 .
At last I predict the labels for the test dataset and store in the container.
