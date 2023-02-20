# Divorce Predictors Dataset

When we talk about relationships
between men and women, we usually refer to
marriage. However, how can we identify a good
relationship? Predicting divorce has been an area
of interest for researchers and practitioners for
many years, as it has significant social and
economic implications. One of the main reasons
for predicting divorce is to identify couples who
may be at risk of divorce so that interventions can
be put in place to help them address any issues and improve their relationship. There are
several potential benefits to using machine learning to predict divorce. For example,
machine learning algorithms can identify risk factors for divorce that may not be
immediately obvious to human analysts.

 The Divorce Predictors Dataset is a publicly available UCI Machine Learning Repository dataset. A total of 170 couples are included in this dataset, along with the Divorce Predictor Scale variables (DPS), a questionnaire of 54 questions, based on the Gottman couples therapy. Records were collected from face-to-face interviews with couples who were already divorced (49%) or happily married (51%) in various regions of Turkey. A five-point scale was used to measure all responses (0=Never, 1=Seldom, 2=Average, 3=Frequently, 4=Always).

# Requirements:

1. Formulate the machine learning problem by identifying the task (classification or
regression), data, and challenges.

2. Perform Exploratory Data Analysis. This includes:

* Plot relationship between variables
* Identify correlated features or the ones that highly correlated with the
label/outcome, if any
* Perform data imputation for missing variables
* Encode your outcome to a one-hot vector, if needed
* Remove redundant variables by dimensionality reduction techniques

3. Consider splitting the data into Training, Validation, and Testing sets. The suggested
split is 70%, 10%, and 20% held-out testing set, respectively. (same split for all tasks)

4. Build and develop the following models (tasks):
* Task#: Logistic/Linear Regression according to your formulation in step 1

5. For each task, run the model with and without processing the data, e.g., without
normalization or dimensionality reduction, and compare the model’s performance
after you normalize and/or reduce the dimensionality of the data.

6. For each task, show how you performed the model selection. For example,
demonstrate the performance of variants of your model with different
hyper-parameters, e.g., number of clusters and initialization when it comes to
clustering methods.

7. For each task, perform a 5-fold Cross Validation.

8. For each task, run the corresponding evaluation metrics on each fold to demonstrate
the performance of your model on the held-out testing set