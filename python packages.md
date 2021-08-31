# Python Packages-
   A package is a directory of Python modules that contains an additional __init__.py file, which distinguishes a package from a directory that is supposed to contain multiple Python scripts. Packages can be nested to multiple depths if each corresponding directory contains its own __init__.py file.There are many types of packages.Lets have look over few common packages.


1 *pip*: is the standard way of installing and managing packages in Python. Pip comes standard with every Python distribution, allowing you to accomplish installs, uninstalls, updates, etc from the command line. For example, to install a specific package with pip from PyPI, run:

pip install “SomePackage”

2 *Requests*: The requests package is an HTTP library for Python.It also integrates a few other Python libraries in order to maximize functionality while still managing to minimize complexity. For example, here’s how to make a request to Spotify (no authentication required):

import requests
r = requests.get(‘https://api.spotify.com/’)
r.status_code

3 *Pytest*: Testing code fidelity is not only good practice as a programmer, but is also made easy with pytest. The pytest package provides a framework to easily find bugs at any scale. It allows for parallel testing, autodetection of test functions or modules, subset testing, and other customizable features. 

An example of a small test:

(content of test_sample.py)
def inc(x):
    return x + 1
def >test_answer():
    assert inc(3) == 5

4 *NumPy*: NumPy is the essential package for scientific and mathematical computing in Python. It introduces n-dimensional arrays and matrices, which are necessary when performing sophisticated mathematical operations. It contains functions that perform basic operations on arrays, such as sorting, shaping, and other mathematical matrix operations. 

For example, to create two 2×2 complex matrices and print the sum: 

import numpy as np

a = np.array([[1+2j, 2+1j], [3, 4]])
b = np.array([[5, 6+6j], [7, 8+4j]])
print(a+b)

5 *Pendulum* -While datetime is great for basic work along these lines, the Pendulum Python package makes it easier to do more complex coding involving dates and times. It’s more intuitive to work with, and it manages time zones automatically.

Best of all, Pendulum is designed to be a drop-in replacement for datetime. That means you can use it with code you’ve already written based on datetime. With only a few exceptions, Pendulum will work just as well, without the need to modify the code, while providing extra features not present in plain-old datetime.

 