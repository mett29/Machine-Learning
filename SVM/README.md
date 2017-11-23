<h1>SVM - Support Vector Machine</h1>

Support Vector Machine is one of the most popular models in Machine Learning. Its popularity stems from the fact that it can be used for <i>linear or nonlinear classification</i> and <i>regression</i> as well. 

<h3>When to use it?</h3> With complex but small or medium size datasets.

<h3>How it works?</h3>
Sometimes, although our classes are linearly separable, methods like Linear Regression may not work properly.
SVM classifier not only separates the classes, but also stays as far away from the closest training instances as possible.<br><br>
The space divided by the SVM's line is called <b>Large Margin Classifier</b>:
in general the larger the margin the lower the generalization error of the classifier.

The instances located on the edge of this space are called <b>Support Vectors</b>.

Notes:
- 2 techniques: hard margin, soft margin (the last one is the most used, because more flexible)
- SVM is sensible to scaling