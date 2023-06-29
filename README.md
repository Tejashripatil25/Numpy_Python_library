# Numpy_Python_library

NumPy is a Python library.
NumPy is used for working with arrays. 
NumPy is short for "Numerical Python".
NumPy provides a key object, the ndarray. The ndarray is an n-dimensional array of homogenous data. 
It enables the creation of arrays of a single dimension, two dimensions (like a table or matrix), and multiple other dimensions.

### Applications of Numpy:

![image](https://github.com/Tejashripatil25/Numpy_Python_library/assets/124791646/4d831368-0ac0-4130-899e-ebd7cd8a2c17)


### Creating Python NumPy Arrays

NumPy ndarray objects are n-dimensional arrays. On the surface, they appear to be quite similar to Python lists, but they work quite differently. Let’s work on creating our first array:

### Creating your first array

import numpy as np

array = np.array([1,2,3,4,5])

Let’s see what the data type of the array you created above is. You can do this using the .dtype attribute:

### Checking the data type of an array

print(array.dtype)

### Returns: int64

### Multi-Dimensional NumPy Arrays

you can create a two-dimensional array by passing in a list of lists. Let’s take a look at a simple example:

### Creating a two-dimensional array

array = np.array([[1,2,3],[4,5,6]])

print(array)

### Returns:

### [[1 2 3]
###  [4 5 6]]

We can check the dimensions of the array by using the .ndim attribute, which returns a single value of dimensions:

### Checking the dimensions of an array

array = np.array([[1,2,3],[4,5,6]])

print(array.ndim)

### Returns: 2

### Indexing, Slicing, and Boolean Indexing NumPy Arrays

This works very similar to accessing list items. Indexing and slicing NumPy arrays works very similar to indexing and slicing Python lists:

Indices start at 0 and contineue through to the end of the list

Negative indices start at -1

Arrays can be sliced using a colon, using either positive or negative indices (or both)

An slice end will imply either the full left or right side of the array

### Indexing and Slicing a 1-D NumPy Array

import numpy as np

array = np.array([1,2,3,4,5])

print(array[0])     # Returns: 1

print(array[-1])    # Returns: 5

print(array[1:3])   # Returns [2 3]

