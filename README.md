Mathematical optimization algorithms to predict time series.
======= 

Kalman filter
--------
The Kalman filter is a mathematical algorithm that uses a series of measurements observed over time, containing noise (random variations) and other inaccuracies, and produces estimates of unknown variables that tend to be more precise than those based on a single measurement alone. It is a type of recursive Bayesian filter that is widely used in control systems, navigation systems, and other applications where precise estimates of unknown variables are needed.

Expectation Maximization
--------
The Expectation-Maximization (EM) algorithm is an iterative optimization method that combines different unsupervised machine learning algorithms to find maximum likelihood or maximum posterior estimates of parameters in statistical models that involve unobserved latent variables. The EM algorithm is commonly used for latent variable models and can handle missing data. It consists of an estimation step (E-step) and a maximization step (M-step), forming an iterative process to improve model fit.

* In the E step, the algorithm computes the latent variables i.e. expectation of the log-likelihood using the current parameter estimates. 
* In the M step, the algorithm determines the parameters that maximize the expected log-likelihood obtained in the E step, and corresponding model parameters are updated based on the estimated latent variables. 
