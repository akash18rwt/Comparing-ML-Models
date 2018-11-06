# Comparing-ML-Models
While working on a machine learning project, we often end up with multiple good models to choose from. Each model will have different performance characteristics.

Using resampling methods like cross validation, we can get an estimate for how accurate each model may be on unseen data. You need to be able to use these estimates to choose one or two best models from the suite of models that you have created.

It is a good idea to visualize the data using different techniques in order to look at the data from different perspectives.

The same idea applies to model selection.A way to do this is to use different visualization methods to show the average accuracy, variance and other properties of the distribution of model accuracies.

Here I have applied 6 different algorithms and compared their accuracies:

1. Logistic Regression
2. Linear Discriminant Analysis
3. K-Nearest Neighbors
4. Classification and Regression Trees
5. Naive Bayes
6. Support Vector Machines

The problem is a standard binary classification dataset from the UCI machine learning repository called the Pima Indians onset of diabetes.

The 10-fold cross validation procedure is used to evaluate each algorithm configured with the same random seed to ensure that the same splits to the training data are performed and that each algorithms is evaluated in precisely the same way.
