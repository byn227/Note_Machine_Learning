# Logistic Regression

Logistic regression is used for classification problems. It models the probability that a given input belongs to a particular class using the logistic (sigmoid) function.

![Logistic Regression Curve](assets/image-12.png)

[📓 Logistic Regression Sigmoid Lab](./lab/Logistic%20Regression_sigmoid.ipynb)

# Decision Boundary

A decision boundary separates different classes in the feature space. In logistic regression, the boundary is determined by the model's parameters and the sigmoid function.

![Boundary Example 1](assets/image-13.png)
![Boundary Example 2](assets/image-14.png)

[📓 Decision Boundary for Logistic Regression Lab](./lab/Decision%20Boundary%20for%20Logistic%20Regression.ipynb)
# Logistic Loss Function

The logistic loss function (also called log-loss or cross-entropy loss) measures the performance of a classification model whose output is a probability value between 0 and 1.

![Logistic Loss Formula](assets/image-1.png)
![Logistic Loss Graph](assets/image.png)

[📓 Logistic Regression and Logistic Loss Lab](./lab/Logistic%20Regression%20and%20Logistic%20loss.ipynb)

# Simplified Loss Function

A simplified loss function can be used for binary classification, making calculations and optimization more efficient.

![Simplified Loss Formula 1](assets/image-2.png)
![Simplified Loss Formula 2](assets/image-3.png)

[📓 Cost Function for Logistic Regression Lab](./lab/Cost%20Function%20for%20Logistic%20Regression.ipynb)
# Gradient Descent for Logistic Regression

Gradient descent is also used to optimize the parameters in logistic regression by minimizing the logistic loss function.

![Gradient Descent for Logistic Regression](assets/image-4.png)

[📓 Gradient Descent for Logistic Regression Lab](./lab/Gradient%20descent%20for%20Logistic%20Regression.ipynb)


## Logistic Function with Scikit-Learn

Scikit-Learn provides a simple and efficient implementation of logistic regression. Here's how to use it:

[📓 Logistic Regression with Scikit-Learn Lab](./lab/Logistic%20by%20Scikit-Learn.ipynb)
# Addressing Overfitting

Overfitting occurs when a model learns the noise in the training data rather than the actual pattern. To address overfitting:
1. Collect more data
2. Select relevant features
3. Reduce the size of parameters (regularization)

[📓 Overfitting Lab](./lab/Overfitting.ipynb)
# Regularized Linear Regression

Regularization adds a penalty to the loss function to discourage complex models and reduce overfitting. Common techniques include L1 (Lasso) and L2 (Ridge) regularization.

![Regularization Example 1](assets/image-15.png)
![Regularization Example 2](assets/image-16.png)

[📓 Regularized Cost and Gradient Lab](./lab/Regularized%20Cost%20and%20Gradient.ipynb)



## High Variance and High Bias
High variance (overfitting)


![alt text](assets/image-17.png)

![alt text](assets/image-18.png)
![alt text](assets/image-19.png)
![alt text](assets/image-20.png)
![alt text](assets/image-21.png)

## Lab

[📓 Logistic Regression Main Lab](./lab/Logistic_Regression.ipynb)
## Regularized neuron network
![alt text](assets/image-22.png)