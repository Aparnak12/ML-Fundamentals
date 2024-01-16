Our goal in this problem is to calculate bias and variance for different families of polynomials. We will be using
the training error as a proxy for bias, and the consistency of the train and test error as a proxy for
variance. 

1. Split the data in 50/50 ratio for training and testing, fit a polynomial of degree d for d $\in$
[1, ,,, ,15] to the training set, and calculate and store the training and testing MSE for each
model.
2. Repeat this calculation 1000 times, where each time you take a random 50/50 split.
3. Calculate the mean training error per degree of polynomial (Proxy for Bias).
4. Calculate the standard deviation of the absolute difference between train and test errors, i.e.,
|trainingerror - testingerror|, per degree of polynomial (Proxy for Variance).
5. Plot the logarithm of the values calculated in Parts (3) and (4) as a function of the degree of
polynomial. What degree polynomial do you think is the best model to use and why?
