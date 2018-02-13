## Regression

Write Python code to complete the following tasks.  You will be using sklearn, pandas, numpy, scipy.optimize, matplotlib and pydataset.

Get the 'JohnsonJohnson' dataset:
from pydataset import data
dataset = data('JohnsonJohnson')

Plot the data - what is it showing?

Make a linear fit to the data and plot it overlaid on the data.

Now make a polynomial fit to the data.  What is the lowest order that gives a reasonable fit?

Notice the annual structure to the data, what could be going on?

Optional: Now make a fit that will include the annual variations as well (tips - what kind of function could you use?  To fit arbitrary functions use leastsq from scipy.optimize and make sure to give sensible input parameters)

Optional: Make a fit using a neural network.