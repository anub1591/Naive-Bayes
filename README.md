# Naive-Bayes
Performed classification using Naive Bayes

The present assignment is also based on one of the important machine learning algorithms i.e. Naive Bayes. It is a collection of machine learning algorithms which can be understood with the help of Bayes Theorem. The Bayes Theorem defines the conditional probability of an event and is stated by the following formula:
 
The above formula defines the conditional probability of an event A when B is true. Here, P(A) reflects the probability of event A and P(B) reflects the probability of event B. P(B|A) is the conditional probability of event B when A is true.
Naive Bayes assumes that the presence of each feature in the class is independent and unrelated to the presence of others in the class. It basically classifies each feature to the class independent of other features of the class. The Naive Bayes model is very simple and easy to build. It is quick in making predictions and can be trained easily. Because of these advantages, it is widely used in Recommendation Systems and Real-Time Predictions. It is also used in spam filtering, sentiment analysis, and text classification too. Despite several advantages, this model has one major disadvantage which is that it assumes the feature to be independent even if they are not. Because of this reason, it is called naive as the features may not always be independent of each other, they may be dependent in reality. 

The present assignment contains two parts: Part A and Part B. Both the parts involve Naive Bayes Classification performed on two different datasets. Part A involves dataset relating to emails wherein Naive Bayes is used for spam identification. Part B involves the dataset relating to different wine types. In Python, a Naive Bayes model can be built in three different forms:
•	Gaussian: This model relies on the assumption that the features follow a normal distribution and is used in classification.
•	Multinomial: This model is used mainly for discrete counts
•	Bernoulli: This is used in case of binary feature vectors i.e. zeros and ones.
