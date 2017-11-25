<h1>Decision Trees</h1>
<h3>with some mention of Random Forest</h3>

<p>In this notebook I'm going to explain the basic notions behind the Decision Tree algorithm with some theory and an example on the Scikit moons dataset.</p>

<p>Decision Trees are, like SVMs, among the main algorithms in Machine Learning because of their versatility. Indeed, they can be used for both classification and regression and even multioutput tasks. Furthermore, they are the pillars of Random Forest, one of the most powerful Machine Learning algorithm.</p>

<h3>Notes about DTs:</h3>
- Computational complexity?
<b>O(n x mlog(m))</b>
<b>Nonparametric</b> model (pay attention to overfitting)
- Scikit uses the <b>CART algorithm</b> by default
- <b>Don't<b> require scaling
- Sensitive to training set <b>rotation</b>

Reference: 
- https://www.amazon.it/Hands-Machine-Learning-Scikit-Learn-TensorFlow-ebook/dp/B06XNKV5TS
- http://scikit-learn.org/stable/modules/tree.html
- https://en.wikipedia.org/wiki/Decision_tree_learning



