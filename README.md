# Insurance-Cross-Sell-Prediction

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimize its business model and revenue. 


## Steps Performed

1. Downloading and Setting up PySpark in Colab
2. Loading Data
3. Short visualization on data
4. Preparing dataset for training
5. Building Machine Learning Models
6. Validation for comparison of different models using AUC

## Models Used

**RANDOM FOREST:**  Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that operate by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes or mean/average prediction of the individual trees

**LOGISTIC REGRESSION:** Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression (or logit regression) is estimating the parameters of a logistic model 

**DECISION TREE:** A decision tree is a flowchart-like structure in which each internal node represents a "test" on an attribute (e.g. whether a coin flip comes up heads or tails), each branch represents the outcome of the test, and each leaf node represents a class label (decision taken after computing all attributes).


**GRADIENT BOOSTING :** Gradient boosting is a machine learning technique for regression and classification problems, which produces a prediction model in the form of an ensemble of weak prediction models, typically decision trees.

## Conclusion
As we can see that ROC Score for Boosting Algorithm is slight higher than the other As it converts weak learner to strong learners.
Therefore we can Move ahead with the Gradient Boosting with the Best Params which we have found using Grid Search and validated using CrossValidation.




