## Regression

Write Python code to complete the following tasks.  You will be using `sklearn`, `pandas`, `numpy`, `scipy.optimize`, `matplotlib` and `pydataset`.

1.  Get the 'JohnsonJohnson' dataset:
```python
from pydataset import data
dataset = data('JohnsonJohnson')
```
2.  Plot the data - what is it showing?

3.  Make a linear fit to the data and plot it overlaid on the data.

4.  Now make a polynomial fit to the data.  What is the lowest order that gives a reasonable fit?

5.  Notice the annual structure to the data, what could be going on?

6.  Optional: Now make a fit that will include the annual variations as well (tips - what kind of function could you use?  To fit arbitrary functions use `leastsq` from `scipy.optimize` and make sure to give sensible input parameters)

7.  Optional: Make a fit using a neural network.