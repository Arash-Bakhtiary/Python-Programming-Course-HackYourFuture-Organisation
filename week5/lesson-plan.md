# Week 5 : Python Libraries

## Pre-requisites :

This course has no prerequisites. However, having familiarity with other programming languages can aid in your comprehension of Python.
## Lesson Plan :
### 1.	Math Library :
The math module in Python is a built-in module that provides various mathematical functions and constants. It allows you to perform complex mathematical operations and calculations. Here are some commonly used functions and constants from the math module:
Mathematical Constants: math.pi, math.e
/**Basic Mathematical Functions:**/ math.sqrt(x), math.pow(x, y), math.exp(x), math.log(x), math.log10(x), math.ceil(x), math.floor(x)
Trigonometric Functions: math.sin(x), math.cos(x), math.tan(x), math.degrees(x), math.radians(x)
Other Functions: math.factorial(x), math.gcd(a, b), math.isqrt(n), math.modf(x), math.trunc(x), math.degrees(x), math.radians(x)

### 2.	Random Library :
The random module in Python is a built-in module that provides functions for generating random numbers, selecting random items, and performing other random-related operations. It's commonly used in various applications, simulations, and games that require randomness. Here are some commonly used functions from the random module:
Generating Random Numbers: random.random(), random.uniform(a, b), random.randint(a, b), random.randrange(start, stop, step)
Selecting Random Items: random.choice(seq), random.shuffle(lst), random.sample(population, k)
Generating Random Sequences: random.seed(a=None, version=2), random.random()
Random Probability: random.choices(population, weights=None, k=1), random.gauss(mu, sigma), 
Random Integers: random.getrandbits(k)
Random Strings: random.choices(population, weights=None, cum_weights=None, k=1), random.random(), 

### 3.	Numpy Library :
The numpy (Numerical Python) library is a powerful package in Python that provides support for working with arrays and matrices of numerical data, along with a wide range of mathematical functions to operate on these arrays. It is a fundamental library for scientific computing and data analysis in Python. Here are some key features and commonly used functionalities of the numpy library:
Creating Arrays: numpy.array(iterable), numpy.zeros(shape), numpy.arange(start, stop, step)
Basic Array Operations: Arithmetic operations (+, -, *, /, etc.), numpy.dot(array1, array2), numpy.transpose(array) or array.T, numpy.sum(array) and numpy.mean(array)
Array Indexing and Slicing: Indexing (Access elements of arrays using indices), Slicing (Extract sub-arrays using slices)
Universal Functions (ufuncs): numpy.sin(array), numpy.cos(array), numpy.exp(array), numpy.log(array)
Array Shape and Reshaping: array.shape, array.reshape(new_shape), array.flatten()
Statistical Functions: numpy.min(array), numpy.max(array), numpy.median(array)
Random Number Generation: numpy.random.rand(shape) and numpy.random.randn(shape)
Array Broadcasting: numpy supports broadcasting, which allows arithmetic operations between arrays of different shapes.
Performance Optimization: numpy arrays are highly optimized and efficient for numerical computations, making it suitable for large-scale data processing and scientific computing.

### 4.	Pandas Library :
The pandas library is a popular open-source data manipulation and analysis library for Python. It provides powerful data structures and functions to make working with structured data, such as tabular data and time series, efficient and straightforward. Here are some key features and commonly used functionalities of the pandas library:
Data Structures: pandas.Series, pandas.DataFrame
Creating DataFrames: Creating a DataFrame from a dictionary or a list of dictionaries, Reading data from various file formats like CSV, Excel, SQL databases
Data Manipulation: Indexing and Slicing, Filtering and Selection, Joining and Merging
Data Cleaning: Handling Missing Data (fillna(), dropna(), and interpolate()), Removing Duplicates (drop_duplicates())
Data Aggregation and Grouping: groupby(), Aggregation Functions (sum(), mean(), count())
Time Series Handling: Resampling and Time Shifting
Data Visualization: plot()
Input/Output: Reading and Writing Data
Handling Categorical Data: Convert categorical data to numerical form using pd.Categorical()
Performance Optimization: pandas operations are designed to be highly efficient, making it suitable for large-scale data processing.
Integration with Other Libraries: Integration with libraries like matplotlib, seaborn, and machine learning frameworks.

### 5.	Matplotlib Library :
The matplotlib library is a widely used plotting and data visualization library for Python. It provides a variety of functions and tools for creating high-quality visualizations and graphs, making it an essential tool for data analysis, scientific research, and data communication. Here are some key features and commonly used functionalities of the matplotlib library:
Basic Plotting: matplotlib.pyplot.plot(x, y), matplotlib.pyplot.scatter(x, y)
Customization: matplotlib.pyplot.title(), matplotlib.pyplot.xlabel(), matplotlib.pyplot.ylabel(), matplotlib.pyplot.legend(), matplotlib.pyplot.grid(), matplotlib.pyplot.xlim(), matplotlib.pyplot.ylim()
Subplots: matplotlib.pyplot.subplot(rows, cols, index), matplotlib.pyplot.subplots(rows, cols)
Styles and Aesthetics: matplotlib.pyplot.style.use(), Customizing colors, markers, linestyles, etc.
Saving and Exporting: matplotlib.pyplot.savefig(filename)
Integration with pandas: Direct plotting from pandas DataFrames.
Interactive Visualizations: matplotlib can be used in combination with libraries like mplcursors for adding interactivity to plots.
