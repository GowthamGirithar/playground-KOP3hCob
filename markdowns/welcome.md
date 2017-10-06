# Machine Learning with Java - Part 5 (Random Forest)

In my previous articles we have discussed about <>  .In this article, we are going to discuss about most important classification algorithm which is Random Forest Algorithm.

# Random Forest 

Random forest is a trademark term for an ensemble classifier that consists of many decision trees and outputs the class that is the mode of the classes output by individual trees. Random forests are collections of trees, all slightly different.
It belongs to supervised learning.
Random Forest algorithm can be used for both the classification and regression kind of problems.You might be wondered to know how an single algorithm can be used for both classification and regression kind of problems. We will discuss in detail below.

# Difference with Decision Tree

In Random Forest , we are creating more number of decision trees but the construction of decision is not with information gain and gini index approach.The process of finding the root node and splitting the features node will happen randomly.

Let us consider you are planning to go for a trip and asking suggestions from friend .Your friend will ask some deatils from you to decide which places you will like and which are all places you may not like based on the deatils he got from you. In this case , decision tree will be used to predict.

The above case is a decision tree , your friend used the answers given by you to predict your likes and moreover final decision is taken by single person using the only one decision tree.

But you dont want to ask suggestions only from your close friend .so you decided to ask all your friends. Your friends will  ask random questions to predict your likes. In this case random forest will be used to decide the place based on the ratings which have most.In this scenario, there are many friends involved and everyone has asked different questions. Many trees are involved and final decision is based on number of votes.so it is random forest.

Hope difference between decision tree withy random forest is understood from the above example.

# Why Random Forest

The advantages of randome forest algorithm are,

1. It can be used for both classification and regression kind of problems.

2. It will be easier to handle missing values.

3. Overfitting (noice of the model) will be avoided by having many trees and so therefore more accurate.

4. It run efficiently on large databases

# Random Forest Demo

@[Naive Bayes Demo]({"stubs": ["src/main/java/com/gg/ml/RandomForestDemo.java"], "command": "com.gg.ml.RandomForestDemoTest#test"})


# Code Explanation

In this above sample code, we have used RandomForest classifier of weka . We can set the number of trees it have to breakup for the features we have given as traing set.


