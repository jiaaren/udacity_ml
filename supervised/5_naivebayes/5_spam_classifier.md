## **Exercise: Building a spam classifier**
### Introduction
Spam detection is one of the major applications of Machine Learning in the interwebs today. Pretty much all of the major email service providers have spam detection systems built-in and automatically classify such mail as 'Junk Mail'.

**In this mission, we will be using the Naive Bayes algorithm to create a model that can classify dataset SMS messages as spam or not spam, based on the training we give to the model.** It is important to have some level of intuition as to what a spammy text message might look like.

### **What are spammy messages?**
Usually, they have words like 'free', 'win', 'winner', 'cash', 'prize', or similar words in them, as these texts are designed to catch your eye and tempt you to open them. Also, spam messages tend to have words written in all capitals and also tend to use a lot of exclamation marks. To the recipient, it is usually pretty straightforward to identify a spam text and our objective here is to train a model to do that for us!

**Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. Also, this is a supervised learning problem, as we know what is trying to predict. We will be feeding a labeled dataset into the model, that it can learn from, to make future predictions.**

## Exercise: Spam Classifier - Workspace
The following exercise dives deep into the Naive Bayes algorithm with extended learning information as well as an opportunity for hands-on learning.

Once you get into the workspace Jupyter file, you will see the project has been broken down into the following steps:

* Step 0: Introduction to the Naive Bayes Theorem
* Step 1.1: Understanding our dataset
* Step 1.2: Data Preprocessing
* Step 2.1: Bag of Words (BoW)
* Step 2.2: Implementing BoW from scratch
* Step 2.3: Implementing Bag of Words in scikit-learn
* Step 3.1: Training and testing sets
* Step 3.2: Applying Bag of Words processing to our dataset.
* Step 4.1: Bayes Theorem implementation from scratch
* Step 4.2: Naive Bayes implementation from scratch
* Step 5: Naive Bayes implementation using scikit-learn
* Step 6: Evaluating our model
* Step 7: Conclusion

Refer to folder `5_spamclassifier` for files