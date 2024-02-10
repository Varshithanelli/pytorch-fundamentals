# pytorch-fundamentals
# Importing Libraries:

torch: PyTorch library for tensor computations.
pandas: Library for data manipulation and analysis.
numpy: Fundamental package for scientific computing with Python.
matplotlib.pyplot: Plotting library for Python.

# Printing Torch Version:

The version of PyTorch is being checked.

# Creating Scalars, Vectors, and Matrices:

Scalars are single numbers (0-dimensional tensors), vectors are arrays of numbers (1-dimensional tensors), and matrices are 2-dimensional arrays of numbers (2-dimensional tensors).
Scalars, vectors, and matrices are created using torch.tensor() with appropriate input arguments.

# Tensor Attributes and Operations:

ndim: This attribute returns the number of dimensions of a tensor.
item(): This method retrieves the value of a scalar tensor as a Python number.
shape: This attribute returns the shape of a tensor.
These attributes and methods are demonstrated on different tensors to show how to inspect and manipulate tensors.

# Random Tensors:

torch.rand(): This function generates random tensors with values uniformly sampled from the interval [0, 1).
Random tensors of different shapes are created to demonstrate its usage.
