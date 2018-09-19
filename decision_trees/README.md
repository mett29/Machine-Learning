# Decision Trees
## (with some mention of Random Forest)

In this notebook I'm going to explain the basic notions behind the Decision Tree algorithm with some theory and an example on the Scikit moons dataset.

Decision Trees are, like SVMs, among the main algorithms in Machine Learning because of their versatility. Indeed, they can be used for both classification and regression and even multioutput tasks. Furthermore, they are the pillars of Random Forest, one of the most powerful Machine Learning algorithm.

![random_forest](https://upload.wikimedia.org/wikipedia/commons/7/76/Random_forest_diagram_complete.png)

### Notes about DTs:
- Computational complexity? **O(n x mlog(m))**
- **Nonparametric** model (pay attention to overfitting)
- Scikit uses the **CART algorithm** by default
- **Don't** require scaling
- Sensitive to training set **rotation**

### Reference: 
- [Hands-On Machine Learning with Scikit-Learn & Tensorflow](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646)
- [Scikit Learn webpage](http://scikit-learn.org/stable/modules/tree.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Decision_tree_learning)