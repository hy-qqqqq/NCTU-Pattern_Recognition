<h1> HW3: Decision Tree, AdaBoost and Random Forest </h1>

*Homework in Pattern Recognition lecture.*  
*Implemented with only numpy.*

<h2> Goals </h2>

implement the Decision Tree, AdaBoost and Random Forest algorithm by using only NumPy, then train your implemented model by the provided dataset and test the performance with testing data.

<h2> Implementation </h2>

<h3> Adaboost </h3>

- The AdaBoost algorithm is based on the concept of **boosting**. The idea behind boosting is that a set of **weak** classifiers can make up to a robust classifier using a voting mechanism
- Weight distrinution
    - updated in each iteration (train one weak classifier)

<h3> Random Forest </h3>

- A collection of multiple decision trees
- Randomness
    - dataset (subset)
        - for every bootstrap dataset, build one decision tree
    - best split
        - random in each decision node
- Majority voting

<h2> References </h2>

- Adaboost
    - [apply sample weight in Decision tree learning](https://stackoverflow.com/questions/41194035/how-to-implement-decision-trees-in-boosting)
    - [AdaBoost from Scratch](https://towardsdatascience.com/adaboost-from-scratch-37a936da3d50)
    - [Why is the error of my AdaBoost implementation not going down?](https://stackoverflow.com/questions/55318330/why-is-the-error-of-my-adaboost-implementation-not-going-down)
- Random Forest
- Supplement
    - [sklearn - ensemble method](https://github.com/scikit-learn/scikit-learn/tree/main/sklearn/ensemble)
    - [Feature Importance in Decision Trees](https://sefiks.com/2020/04/06/feature-importance-in-decision-trees/)
