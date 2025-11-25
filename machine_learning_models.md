Machine learning models are divided into three major types, supervised, unsupervised and reinforcement models.
And few SPECIAL categories like deep learning, ensemble learning etc.



1.SUPERVISED LEARNING MODELS 

-learn from labeled data 

-suitable for a).classification (spam or not spam, safe or malicious site)
              b).regression (predict price, temperature)


1.a>Classification Models 
when output is of binary category(0/1,yes/no,typeA/B)

i)Logistic Regression: It predicts probability of a class( e.g. probability of yes or no) and the final output is a class label not a continuous value.

ii)Decision tree classifier: It is a tree atructured model where each internal node represents a question about a feature, each branch represents a decision and each leaf node represents class prediction.


iii)Random forest classifier: It is a colection(a forest) of decision trees. Each tree make a prediction and forest predicts the class by taking majority vote of all trees. Many tree--> More accurate

iv)Support vector machine: It draws best separating lines between classes.Good for high-dimensional data, text classification, small medium datasets.
It's pros are it works well in high dimensions effective for non-linear data with kernels and robust to overlifting (with proper C,kernel) but selecting kernel and parameters can be tricky.

v)K Nearest Neighbours: It classifies a point on its k closest neighbours and predicts based on nearest data points.Good for simple problems, small datasets and non-linear boundaries. Pros are very simple, no training needed and works well with well-separated classes but cons are it is very slow at prediction time and sensitive to irrelevant features and need feature scaling. 

vi)Naive Bayes: Use Bayes' theorem assuming features are independent. Based on probability great for text and spam.

vii)Gradient Boosting: Powerful boosting trees used in competitions.


1.b)Regression Models
When output is a number.

i)Linear Regression:
