The dataset contains 500 training and 500 testing samples to train and test a house prediction model following the equation: $$y = f(0) = c_0 + c_1 x_{1} + c_2 x_{2} + \epsilon$$
We have access to two features "living area" and "year built" to build our model predicting the "selling price" (i.e., "y").

Let's fit linear regression models to $x1, x2$, and $(x1, x2)$, and report the testing error for each model.

The test error is calculated as <img width=200 src="https://github.com/Aparnak12/ML-Fundamentals/assets/51270673/680bac85-ec1b-46f6-ad4b-e63a6c384bd3)https://github.com/Aparnak12/ML-Fundamentals/assets/51270673/680bac85-ec1b-46f6-ad4b-e63a6c384bd3"> for the test data, where $\hat{y}^{(i)}$ is the prediction.
