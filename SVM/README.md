# SVM - Support Vector Machine

![svm](https://upload.wikimedia.org/wikipedia/commons/1/1b/Kernel_Machine.png)

Support Vector Machine is one of the most popular models in Machine Learning. Its popularity stems from the fact that it can be used for **linear or nonlinear classification** and **regression** as well. 

### When to use it? 
With complex but small or medium size datasets.

### How it works?
Sometimes, although our classes are linearly separable, methods like Linear Regression may not work properly.
SVM classifier not only separates the classes, but also stays as far away from the closest training instances as possible.
The space divided by the SVM's line is called **Large Margin Classifier**:
in general the larger the margin the lower the generalization error of the classifier.

The instances located on the edge of this space are called **Support Vectors**.

### Notes:
- 2 techniques: hard margin, soft margin (the last one is the most used, because more flexible)
- SVM is sensible to scaling

### References: 
- [Hands-On Machine Learning with Scikit-Learn & Tensorflow](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646)
- [Wikipedia](https://en.wikipedia.org/wiki/Support_vector_machine)
- [OpenCV tutorial](https://docs.opencv.org/2.4/doc/tutorials/ml/introduction_to_svm/introduction_to_svm.html)