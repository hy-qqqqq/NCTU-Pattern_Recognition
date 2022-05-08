<h1> HW1: Linear Regression using Gradient Descent </h1>

*Homework in Pattern Recognition lecture.*  
*Implemented with only numpy.*

<h2> Goal </h2>

implement linear regression by using only NumPy, then train your implemented model using Gradient Descent by the provided dataset and test the performance with testing data. 

<h2> Implementation & References </h2>

- [Linear Regression using Gradient Descent](https://towardsdatascience.com/linear-regression-using-gradient-descent-97a6c8700931)
    - mean square error
    - calculate gradients
- [gradient descent intuition](https://www.coursera.org/lecture/machine-learning/gradient-descent-intuition-GFFPB)
    - [Batch, Mini Batch & Stochastic Gradient Descent](https://towardsdatascience.com/batch-mini-batch-stochastic-gradient-descent-7a62ecba642a)
        - (batch) GD - entire dataset (x = m)
        - mini-batch GD - a subset of dataset (1 < x < m)
        - SGD - an observation of dataset (x = 1)
    - [gradient descent optimization algorithms](https://chih-sheng-huang821.medium.com/%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92-%E5%9F%BA%E7%A4%8E%E6%95%B8%E5%AD%B8-%E4%B8%89-%E6%A2%AF%E5%BA%A6%E6%9C%80%E4%BD%B3%E8%A7%A3%E7%9B%B8%E9%97%9C%E7%AE%97%E6%B3%95-gradient-descent-optimization-algorithms-b61ed1478bd7)