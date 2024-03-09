# Optimization-for-Analytics

Regression based project to predict volatility of stock data.
Utilizing the finite sum property of the least-squares objective, executing linear regression from sklearn (based on singular value decomposition) and using it to minimize the mean squared error.
Furthermore, conducting experiment with the parameters of Gradient Descent and Stochastic Gradient Descent, specifically the number of iterations, stopping tolerance, and step size rule with the objective of improving the MSE and the run time per epoch in each case.
Leveraging the use of sparsity of the matrix to reduce cost of computing the gradient with respect to the number of features.
Plotting histograms of the training and test target variables and depicting the scatter plot of the sparse matrix.
More experimentation for parameter fine-tuning to study the runtime and the accuracy of SGD.
