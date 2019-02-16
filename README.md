# Python4DataAnalytics
Machine learning algorithms implemented using sci-kit learn.

This tutorial helps in understanding the Python programming from basics. 
Later you can learn the basics of Numpy, Pandas and matplotlib before jumping into the machine learning part.

We use Sci-kit learn package to implement the basic machine learning algorithms like linear regression, logistic regression and k-means clustering on various
datasets.


# Python for Data Analytics


Why Python for Data Analysis
Python has gathered a lot of interest recently as a choice of language for data and statistical analysis. Below are some reasons which go in favour of learning Python:
Open Source 
Python Has a Healthy, Active and Supportive Community
Easy to learn
Python Has Big Data
Python Has Amazing Libraries
Needless to say, it has some drawbacks too:
It is an interpreted language rather than compiled language – hence might take up more CPU time.
Weak in Mobile Computing: Python has made its presence on many desktop and server platforms, but it is seen as a weak language for mobile computing. This is the reason very few mobile applications are built in it like Carbonnelle.

## Languages for Data analysis
Python
Java
Matlab
R
Julia
Scala etc.

## How to Install Python
Download python from https://www.python.org/downloads/ and install.
Pip installer will come with python installation. It will be available in Python installation folder/scripts.
Navigate to that path in the command prompt and execute the command pip install numpy
To install matplotlib execute command pip install matplotlib.
To install using a single command: python -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose
To install on ubuntu sudo apt-get install python-numpy python-scipy python-matplotlib ipython ipython-notebook python-pandas python-sympy python-nose

Installing using Anaconda (Best installation method - single shot)

https://www.anaconda.com/distribution/


## Python notebooks

https://notebooks.azure.com/
https://cocalc.com/
https://colab.research.google.com/
https://paiza.cloud/en/jupyter-notebook-online
https://jupyter.org/try

### Python Prerequisites before jumping into Data Analytics

List
Tuple
Dictionary
Strings
Importing libraries
Iterations and conditional statements
Working with matrices
Statistical functions
Importing and plotting data

# Python Libraries

## NUMPY

NumPy is the fundamental package for scientific computing with Python:
a powerful N-dimensional array object
sophisticated (broadcasting) functions
tools for integrating C/C++ and Fortran code
useful linear algebra, Fourier transform, and random number capabilities
NumPy enriches the programming language Python with powerful data structures, implementing multi-dimensional arrays and matrices. These data structures guarantee efficient calculations with matrices and arrays. The implementation is even aiming at huge matrices and arrays, better know under the heading of "big data". Besides that the module supplies a large library of high-level mathematical functions to operate on these matrices and arrays.


### Numpy containers:

Lists
Tuples
Sets
Dictionaries

Other Features:

Arithmetic operations on matrices
Matrix Library
Linear Algebra
Fourier transforms


## PANDAS

pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with structured (tabular, multidimensional, potentially heterogeneous) and time series data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language.

Pandas is well suited for many different kinds of data:
Tabular data with heterogeneously-typed columns, as in an SQL table or Excel spreadsheet
Ordered and unordered (not necessarily fixed-frequency) time series data.
Arbitrary matrix data (homogeneously typed or heterogeneous) with row and column labels
Any other form of observational / statistical data sets. The data actually need not be labeled at all to be placed into a pandas data structure

The two primary data structures of pandas, Series (1-dimensional) and DataFrame (2-dimensional), handle the vast majority of typical use cases in finance, statistics, social science, and many areas of engineering. 

Here are just a few of the things that pandas does well:
Easy handling of missing data (represented as NaN) in floating point as well as non-floating point data
Size mutability: columns can be inserted and deleted from DataFrame and higher dimensional objects
Automatic and explicit data alignment: objects can be explicitly aligned to a set of labels, or the user can simply ignore the labels and let Series, DataFrame, etc. automatically align the data for you in computations
Powerful, flexible group by functionality to perform split-apply-combine operations on data sets, for both aggregating and transforming data
Make it easy to convert ragged, differently-indexed data in other Python and NumPy data structures into DataFrame objects
Intelligent label-based slicing, fancy indexing, and subsetting of large data sets
Intuitive merging and joining data sets
Flexible reshaping and pivoting of data sets
Hierarchical labeling of axes (possible to have multiple labels per tick)
Robust IO tools for loading data from flat files (CSV and delimited), Excel files, databases, and saving / loading data from the ultrafast HDF5 format
Time series-specific functionality: date range generation and frequency conversion, moving window statistics, moving window linear regressions, date shifting and lagging, etc.


## SCIPY
SciPy (Scientific Python) is often mentioned in the same breath with NumPy. SciPy needs Numpy, as it is based on the data structures of Numpy and furthermore its basic creation and manipulation functions. It extends the capabilities of NumPy with further useful functions for minimization, regression, Fourier-transformation and many others.
SciPy uses NumPy arrays as the basic data structure, and comes with modules for various commonly used tasks in scientific programming, including linear algebra, integration (calculus), ordinary differential equation solving, and signal processing.


## MATPLOTLIB

Matplotlib is a python library used to create 2D graphs and plots by using python scripts. It has a module named pyplot which makes things easy for plotting by providing feature to control line styles, font properties, formatting axes etc. It supports a very wide variety of graphs and plots namely - histogram, bar charts, power spectra, error charts etc. It is used along with NumPy to provide an environment that is an effective open source alternative for MatLab.

## SCIKIT-LEARN
Scikit-learn is a free machine learning library for Python. It features various algorithms like support vector machine, random forests, and k-neighbours, and it also supports Python numerical and scientific libraries like NumPy and SciPy.


## PANDAS

### Series 
Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, python objects, etc.). The axis labels are collectively called index. Pandas Series is nothing but a column in an excel sheet.
Labels need not be unique but must be a hashable type. The object supports both integer and label-based indexing and provides a host of methods for performing operations involving the index.
pandas.Series( data, index, dtype, copy)

### Data Frames
A Data frame is a two-dimensional data structure, i.e., data is aligned in a tabular fashion in rows and columns.
This is something like a SQL table with rows and columns or you can imagine like a excel spreadsheet.

A pandas DataFrame can be created using various inputs like −
Lists
dict
Series
Numpy ndarrays
Another DataFrame

# Building Machine learning Models

(Refer to the Jupyter Notebooks for sample implementations)

## Conclusion
In this tutorial we have discussed the Python Basics and also the importance of different python packages like Numpy, Scipy, Matplotlib and Pandas. We understood that Numpy and Scipy will allow us to do some complex mathematical functions on the data including matrices. Matplotlib is a plotting tool to visualize the data and results. Pandas package will allow us to play with data and most importantly used for preprocessing the data i.e. making the data ready to apply it on a machine learning algorithm. Scikit-learn provides whole set of machine learning models that we can use readily on the preprocessed datasets. All these packages comes along with the installation of Anaconda in a single shot. As python is open-source and supports vast varieties of packages like the above mentioned ones, it is gaining a lot of support in industry as well as academecia. 


Hope you have enjoyed and learned something from this session. Thank you…!

