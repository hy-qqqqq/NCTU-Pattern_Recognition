<h1> HW2: Linear Discriminant Analysis </h1>

*Homework in Pattern Recognition lecture.*  
*Implemented with only numpy.*

<h2> Goal </h2>

implement [Fisher’s linear discriminant](https://en.wikipedia.org/wiki/Linear_discriminant_analysis) by using only numpy, then train your implemented model by the provided dataset and test the performance with testing data

<h2> Fisher's linear discriminant concept (2-class) </h2>

> *projecting data with what kind of transformation?*

> *We can view linear classification models in terms of dimensionality reduction.*

* A large variance among the dataset classes.
* A small variance within each of the dataset classes.

<h2> Math </h2>

* the objective function  
![](https://sthalles.github.io/assets/fisher-ld/lda_function_explained.png)
*image from (ref. 1)*

* the objective function can be solved with eigenvalues & eigenvectors, see [rayleigh quotient](https://en.wikipedia.org/wiki/Rayleigh_quotient).  
![](https://sthalles.github.io/assets/fisher-ld/equations.png)
*image from (ref. 1)*

* need to compute between-class variance & within-class variance  

* alternative solution (eq. 4)
    * no need to compute eigenvalues & eigenvectors

<h2> Reference </h2>

1. [An illustrative introduction to Fisher's Linear Discriminant](https://sthalles.github.io/fisher-linear-discriminant/)