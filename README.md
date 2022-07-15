# Regression_and_Classification_with_ML
## Understanding the difference between Regression and Classification and which method to use in one or the other case

### Literature suggested:
#### Regression vs. Classification in Machine Learning for Beginners
https://www.simplilearn.com/regression-vs-classification-in-machine-learning-article

#### Regression in Machine Learning Explained

Regression finds correlations between dependent and independent variables. Therefore, regression algorithms help predict continuous variables such as house prices, market trends, weather patterns, oil and gas prices (a critical task these days!), etc.
The Regression algorithm’s task is finding the mapping function so we can map the input variable of “x” to the continuous output variable of “y.”

#### Classification in Machine Learning Explained

On the other hand, Classification is an algorithm that finds functions that help divide the dataset into classes based on various parameters. When using a 
Classification algorithm, a computer program gets taught on the training dataset and categorizes the data into various categories depending on what it learned.

Classification algorithms find the mapping function to map the “x” input to “y” discrete output. The algorithms estimate discrete values (in other words, binary values such as 0 and 1, yes and no, true or false, based on a particular set of independent variables. To put it another, more straightforward way, classification algorithms predict an event occurrence probability by fitting data to a logit function.
Classification algorithms are used for things like email and spam classification, predicting the willingness of bank customers to pay their loans, and identifying cancer tumor cells.

#### Types of Regression

Here are the types of Regression algorithms commonly found in the Machine Learning field:

•	Decision Tree Regression: The primary purpose of this regression is to divide the dataset into smaller subsets. These subsets are created to plot the value of any data point connecting to the problem statement.

•	Principal Components Regression: This regression technique is widely used. There are many independent variables, or multicollinearity exists in your data.

•	Polynomial Regression: This type fits a non-linear equation by using the polynomial functions of an independent variable.

•	Random Forest Regression: Random Forest regression is heavily used in Machine Learning. It uses multiple decision trees to predict the output. Random data points are chosen from the given dataset and used to build a decision tree via this algorithm.

•	Simple Linear Regression: This type is the least complicated form of regression, where the dependent variable is continuous.

•	Support Vector Regression: This regression type solves both linear and non-linear models. It uses non-linear kernel functions, like polynomials, to find an optimal solution for non-linear models.

#### Types of Classification

And here are the types of Classification algorithms typically used in Machine Learning:

•	Decision Tree Classification: This type divides a dataset into segments based on particular feature variables. The divisions’ threshold values are typically the mean or mode of the feature variable in question if they happen to be numerical.

•	K-Nearest Neighbors: This Classification type identifies the K nearest neighbors to a given observation point. It then uses K points to evaluate the proportions of each type of target variable and predicts the target variable that has the highest ratio.

•	Logistic Regression: This classification type isn't complex so it can be easily adopted with minimal training. It predicts the probability of Y being associated with the X input variable.

•	Naïve Bayes: This classifier is one of the most effective yet simplest algorithms. It’s based on Bayes’ theorem, which describes how event probability is evaluated based on the previous knowledge of conditions that could be related to the event.

•	Random Forest Classification: Random forest processes many decision trees, each one predicting a value for target variable probability. You then arrive at the final output by averaging the probabilities. 

•	Support Vector Machines: This algorithm employs support vector classifiers with an exciting change, making it ideal for evaluating non-linear decision boundaries. This process is possible by enlarging feature variable space by employing special functions known as kernels.






### Additional reading:
#### Decision Trees

A decision tree is a graphical representation of specific decision situations that are used when complex branching occurs in a structured decision process. It breaks down a data set into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed. The final result is a tree with decision nodes and leaf nodes. A decision node has two or more branches and a leaf node represents a classification or decision. The topmost decision node in a tree which corresponds to the best predictor called root node. Decision trees can handle both categorical and numerical data.

#### Logistic Regression

https://towardsdatascience.com/introduction-to-logistic-regression-66248243c148

Logistic regression is a classification algorithm used to assign observations to a discrete set of classes.

What are the types of logistic regression
1.	Binary (eg. Tumor Malignant or Benign)
2.	Multi-linear functions failsClass (eg. Cats, dogs or Sheep's)

#### Linear Regression and Polynomial Regression

https://medium.com/p/c12a072bedf0
https://medium.com/p/d4d5bf9f0f56
https://towardsdatascience.com/introduction-to-linear-regression-and-polynomial-regression-f8adc96f31cb

#### Support Vector Machine (SVM)

https://medium.com/towards-artificial-intelligence/support-vector-machine-svm-introduction-machine-learning-8c56b7da63f1

Logistic Regression (Predictive Learning Model) :
Logistic regression is a technique in statistical analysis that attempts to predict a data value based on prior observation. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes). The goal of logistic regression is to find the best fitting model to describe the relationship between the dichotomous characteristic of interest (dependent variable = response or outcome variable) and a set of independent (predictor or explanatory) variables.

#### K Nearest Neighbor(KNN)

https://towardsdatascience.com/a-simple-introduction-to-k-nearest-neighbors-algorithm-b3519ed98e
The k-nearest-neighbors algorithm is a classification algorithm, and it is supervised: it takes a bunch of labelled points and uses them to learn how to label other points. To label a new point, it looks at the labelled points closest to that new point (those are its nearest neighbors), and has those neighbors vote, so whichever label the most of the neighbors have is the label for the new point (the “k” is the number of neighbors it checks).
