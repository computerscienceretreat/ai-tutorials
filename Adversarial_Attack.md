# Creating Adversarial Examples

In this workshop we're going to use Keras and Clever Hans to generate adversarial attacks on ImageNet classifiers.


## Installation

If you don't already have your system set up to use Python, Tensorflow and Keras then follow the instructions [here](./setup.md)



## Exercise 1

Run the iterative fast gradient sign attack [example](https://github.com/computerscienceretreat/adversarial/blob/master/iter_fast_gradient.py).  Find an image and get it to be classified as a teapot (class 849).  



## Exercise 2

Now try another target class for the attack.  Check out the list for example [here](https://gist.github.com/ageitgey/4e1342c10a71981d0b491e1b8227328b). Check that your attack works with the new target class.
* what is the parameter eps?  Try changing it - what happens?



## Exercise 3

Change the attack in the example so that it is an *untargeted* attack.  Remember this is where you do not pick a particular class that you want the image to be classified as, rather you just want to cause the classifier to get its label wrong.

Check out the clever hans FastGradientSign method documentation [here](https://cleverhans.readthedocs.io/en/latest/source/attacks.html).

Run your untargeted attack on the image you used in exercise 2.  What class is it now classified as?  What is the confidence?