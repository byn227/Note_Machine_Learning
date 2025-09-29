# Logistic Regression

Logistic regression is used for classification problems. It models the probability that a given input belongs to a particular class using the logistic (sigmoid) function.

![Logistic Regression Curve](assets/image-12.png)
(./lab/Logistic Regression_sigmoid.ipynb)

# Decision Boundary

A decision boundary separates different classes in the feature space. In logistic regression, the boundary is determined by the model's parameters and the sigmoid function.

![Boundary Example 1](assets/image-13.png)
![Boundary Example 2](assets/image-14.png)

(./lab/Decision Boundary for Logistic Regression.ipynb)
# Logistic Loss Function

The logistic loss function (also called log-loss or cross-entropy loss) measures the performance of a classification model whose output is a probability value between 0 and 1.

![Logistic Loss Formula](assets/image-1.png)
![Logistic Loss Graph](assets/image.png)
(./lab/Logistic Regression and Logistic loss.ipynb)

# Simplified Loss Function

A simplified loss function can be used for binary classification, making calculations and optimization more efficient.

![Simplified Loss Formula 1](assets/image-2.png)
![Simplified Loss Formula 2](assets/image-3.png)
(./lab/Cost Function for Logistic Regression.ipynb)
# Gradient Descent for Logistic Regression

Gradient descent is also used to optimize the parameters in logistic regression by minimizing the logistic loss function.

![Gradient Descent for Logistic Regression](assets/image-4.png)
(./lab/Gradient descent for Logistic Regression.ipynb)


## Logistic Function with Scikit-Learn

Scikit-Learn provides a simple and efficient implementation of logistic regression. Here's how to use it:
(./lab/Logistic by Scikit-Learn.ipynb)
# Addressing Overfitting

Overfitting occurs when a model learns the noise in the training data rather than the actual pattern. To address overfitting:
1. Collect more data
2. Select relevant features
3. Reduce the size of parameters (regularization)
(./lab/Overfitting.ipynb)
# Regularized Linear Regression

Regularization adds a penalty to the loss function to discourage complex models and reduce overfitting. Common techniques include L1 (Lasso) and L2 (Ridge) regularization.

![Regularization Example 1](assets/image-15.png)
![Regularization Example 2](assets/image-16.png)

(./lab/Regularized Cost and Gradient.ipynb)



## High Variance and High Bias
High variance (overfitting)


![alt text](assets/image-17.png)

![alt text](assets/image-18.png)
![alt text](assets/image-19.png)
![alt text](assets/image-20.png)
![alt text](assets/image-21.png)

## Lab
(./lab/Logistic_Regression.ipynb)
## Regularized neuron network
![alt text](assets/image-22.png)