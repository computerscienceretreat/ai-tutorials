### Setting up Python, Tensorflow and Keras

Install Python 3.5 or above.

I recommend using a version management system such as Anaconda, install instructions [here](https://conda.io/docs/user-guide/install/index.html) - if you already use something else skip to the next step.

Install Tensorflow - follow the instructions for your operating system and Anaconda (at the bottom of the page) [here](https://www.tensorflow.org/install/)

Install Keras - see [here](https://keras.io/)


Install cleverhans:
~~~
pip install -e git+https://github.com/tensorflow/cleverhans.git#egg=cleverhans
~~~

Install PIL:
~~~
pip install pillow
~~~