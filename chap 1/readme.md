## Introduction of Machine Learning


The concept of ML is depicted with an example of predicting the price of a car. The ML model learns from data, represented as some features such as year, mileage, among others, and the target variable, in this case, the car's price, by extracting patterns from the data.

Then, the model is given new data (without the target) about cars and predicts their price (target).

In summary, ML is a process of extracting patterns from data, which is of two types:

        + features (information about the object) and
        + target (property to predict for unseen objects).
Therefore, new feature values are presented to the model, and it makes predictions from the learned patterns.

## ML vs Rule-Based Systems
 Traditional Rule-Based systems are based on a set of characteristics (keywords, email length, etc.) that identify an email as spam or not. As spam emails keep changing over time the system needs to be upgraded making the process untractable due to the complexity of code maintenance as the system grows.

ML can be used to solve this problem with the following steps:

Emails from the user's spam folder and inbox give examples of spam and non-spam.

Rules/characteristics from rule-based systems can be used as a starting point to define features for the ML model. The value of the target variable for each email can be defined based on where the email was obtained from (spam folder or inbox).

A machine learning algorithm can then be applied to the encoded emails to build a model that can predict whether a new email is spam or not spam. The predictions are probabilities, and to make a decision it is necessary to define a threshold to classify emails as spam or not spam.

## Supervised Machine Learning

In Supervised Machine Learning (SML) there are always labels associated with certain features. The model is trained, and then it can make predictions on new features. In this way, the model is taught by certain features and targets.

Feature matrix (X): made of observations or objects (rows) and features (columns).
Target variable (y): a vector with the target information we want to predict. For each row of X there's a value in y.

The model can be represented as a function g that takes the X matrix as a parameter and tries to predict values as close as possible to y targets. The obtention of the g function is what it is called training.

Types of SML problems
        Regression: the output is a number (car's price).
        Classification: the output is a category (spam example).
                Binary: there are two categories.
                Multiclass problems: there are more than two categories.
        Ranking: the output is the top scores associated with corresponding items. It is applied in recommender systems

## Cross-Industry Standard Process for Data Mining
It is the most widely-used analytics model. Conceived in 1996, it became a European Union project under the ESPRIT funding initiative in 1997. The project was led by five companies: Integral Solutions Ltd (ISL), Teradata, Daimler AG, NCR Corporation and OHRA, an insurance company:

Business understanding: An important question is do we need ML for the project. The goal of the project has to be measurable.
        Data understanding: Analyze available data sources, and decide if more data is required.
        Data preparation: Clean data, remove noise applying pipelines, and convert the data to a tabular format, so we can put it into ML.
        Modeling: Train different models and choose the best one. Considering the results of this step, it is proper to decide if it is required to add new features or fix data issues.
        Evaluation: Measure how well the model is performing and if it solves the business problem.
        Deployment: Roll out to production to all the users. The evaluation and deployment often happen together - online evaluation.
It is important to consider how well maintainable the project is.

In general, ML projects require many iterations.

## Model Selection Process

The validation dataset is not used in training. There are feature matrices and y vectors for both training and validation datasets. The model is fitted with training data, and it is used to predict the y values of the validation feature matrix. Then, the predicted y values (probabilities) are compared with the actual y values.

The test set can help to avoid the MCP. Obtaining the best model is done with the training and validation datasets, while the test dataset is used for assuring that the proposed best model is the best.

Split datasets in training, validation, and test. E.g. 60%, 20% and 20% respectively
Train the models
Evaluate the models
Select the best model
Apply the best model to the test dataset
Compare the performance metrics of validation and test

## Library Numpy

## Linear Algebra with Numpy

## Pandas
I have the knowledge of data engineering so i skip this part
