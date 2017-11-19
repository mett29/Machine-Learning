<h1>Gradient Descent</h1>

Gradient descent is a first-order iterative optimization algorithm for finding the minimum of a function. To find a local minimum of a function using gradient descent, one takes steps proportional to the negative of the gradient (or of the approximate gradient) of the function at the current point.

<h4>How it works?</h4>
To understand how it works: suppose you're at the top of a mountain and you want to go down. The problem is that it's foggy and you don't see anything below your feet. What would you do? Well, you can feel where the slope is steepest and follow that direction, step by step.

There are different techniques that use Gradient Descent:

- Batch Gradient Descent: it uses the whole batch of training data at every step. Of course it is very slow with huge dataset; however it scales very well with the number of features.

- Stochastic Gradient Descent: it picks a random instance in the training set at every step and compute the gradients only on that instance. It is much faster, but obviously it is much less regular than Batch GD.

- Mini-batch Gradient Descent: it computes the gradients on small random sets of instances called mini-batches. This method is the mostly used when you have huge and redundant dataset.

There is much more to say, like momentum and other strategies to make this algorithm faster, but it is not this day ;)
