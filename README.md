# numpy_series
numpy course from basic to intermediate

## 01 - Introduction to numpy - Introduction
In this course we'll learn how to use Python for scientific computations using the numpy Module, which is the basic module used in scientific Python. This is a beginner level course as far as scientific Python is concerned, but it's not a beginner level course as far as the Python language itself is concerned. I assume you have at least some basic knowledge of the language.

## 02 - Introduction to numpy - The IPython Console
The IPython console is used to run code interactively. It's an enhanced command-line REPL environment for Python. Some of its features include command history browsing, available even between sessions, input and output caching, autocompletion and more.

![image](https://github.com/user-attachments/assets/6706e194-18df-4a85-9e94-4b3d2868f3b3)

## 03 - Introduction to numpy - Magic Functions
In IPython we can use extension commands, known as magic functions. One-line commands are preceded by a single % sign, and commands working on a whole cell are preceded by a double % sign.

![image](https://github.com/user-attachments/assets/fe04c541-9b7e-40ba-bba0-6f4957b797d2)

## 04 - Introduction to numpy - The Spyder IDE
The Spyder Integrated Development Environment is used to write Python modules and packages as well as run Python code interactively. Through its integration with the IPython console Spyder is especially suitable for working with the scientific libraries.

## 05 - Introduction to numpy - Introduction to Jupyter Notebook
The Jupyter Notebook is a web application in which Python code can be written and executed through a web browser. It's used to run your code, collect the output produced by your code and embed text, graphics, videos, figures and equations, all in one document.

![image](https://github.com/user-attachments/assets/32cebbe6-156c-49a5-a879-f6142bcdc3b7)

## 06 - Introduction to numpy - The numpy Module
If we want to use Python in science, there is one module all other scientific module make use of, numpy. numpy lets us work on arrays, which in turn lets us repeat computations for a set of values in one go without using the slow for loops that work on each element one by one.

![image](https://github.com/user-attachments/assets/fc7d9037-ac71-4705-9183-e8f85f618c9f)

## 07 - Introduction to numpy - The Attributes of a numpy Array
The class that numpy uses for the arrays is the ndarray. An ndarray object contains the data stored in the array but also some other attributes that characterize the array. 

![image](https://github.com/user-attachments/assets/d29206f0-74b7-42b9-a4c7-3752b7b6b872)

## 08 - Introduction to numpy - Data Types
In the previous lecture we were using the dtype attribute of the ndarray class to check the data type of the elements in the array. We know that all elements of a numpy array are of the same type, unlike in a regular Python list, where the elements may but don't have to be of the same type.

![image](https://github.com/user-attachments/assets/049b8363-f988-4eea-bd4f-9672bc27e424)

## 09 - Introduction to numpy - Creating numpy Arrays with Constant Values
Sometimes we need arrays containing specific data, like constant values, increasing or decreasing values, uniformly spaced numbers, random numbers and so on. To this end we can use quite a lot of functions besides the basic np.array function we've been using so far.

![image](https://github.com/user-attachments/assets/8e455b09-c5cc-4f15-a708-36bdc4c3d55d)

## 10 - Introduction to numpy - Creating numpy Arrays with Spaced Values
If we want to create an array with incremental or decremental values, we can use the np.arange function, which works very much like the built-in range function in Python, or the np.linspace function.

![image](https://github.com/user-attachments/assets/0816044e-b11f-475a-a2d6-bdb3eb266497)

## 11 - Introduction to numpy - Creating numpy Arrays with Set Diagonals
In the previous lecture we learned to create numpy arrays filled with constant values, incrementing or decrementing values, as well as uniformly or logarithmically spaced values. But there are even more ways of creating arrays. Let's have a look at some of them.

![image](https://github.com/user-attachments/assets/87d4d624-52e7-4fec-980c-ee345bdbf006)

## 12 - Introduction to numpy - Creating numpy Arrays from Functions
There is another useful way of creating numpy arrays. We can create arrays from functions. To this end we use the np.fromfunction function.

![image](https://github.com/user-attachments/assets/dc7ea0b9-439c-451b-a403-9252c55f11c8)

## 13 - Introduction to numpy - Indexing and Slicing numpy Arrays - the Basics
Indexing and slicing 1-dimensional arrays is pretty straightforward. It works just like with Python lists.

![image](https://github.com/user-attachments/assets/6d59ea87-22ea-4afb-a9ab-0f481239b0ce)

## 14 - Introduction to numpy - Views and Copies
When slicing numpy arrays we create views on the original arrays. So, we are working on the same original data, which means that if we change some data in a view, it will also be changed in the original array.

![image](https://github.com/user-attachments/assets/a5450d6a-d5a7-4bc1-8805-6bbd84c8415e)

## 15 - Introduction to numpy - Fancy Indexing
Numpy arrays may be indexed by other numpy arrays or Python lists. We call this fancy indexing. The sequence that is passed as an index in square brackets contains the indices which should be selected.

![image](https://github.com/user-attachments/assets/9045a5e9-b3ec-47d8-8e3f-352c7f140eca)

## 16 - Introduction to numpy - Boolean Indexing
numpy arrays may be indexed with boolean expression. All elements are selected for which the value of the boolean expression evaluates to True.

![image](https://github.com/user-attachments/assets/e3af10b4-a08b-4597-a666-b8d22ba90d78)

## 17 - Introduction to numpy - Reshaping numpy Arrays
Sometimes you may want to reshape or resize your array, like for example make a matrix array out of several vectors or the other way around, turn a vector to a matrix. numpy offers quite a bunch of functions that will let you do just that. 

![image](https://github.com/user-attachments/assets/c2426f1f-61c1-4897-88f0-475d18a1c442)

## 18 - Introduction to numpy - Merging numpy Arrays
Sometimes you may want to merge arrays into bigger arrays, like for example merge a couple of vectors into a matrix. To this end we can use the np.vstack and np.hstack functions, which stack the arrays vertically and horizontally respectively.

![image](https://github.com/user-attachments/assets/ecd7ee48-aaba-4d1a-a021-72b0f709ff2f)

## 19 - Introduction to numpy - Arithmetic Operations
You can perform all the basic arithmetic operations on numpy arrays. The operations are performed elementwise, so it is important that the arrays have the same sizes and shapes. If they don't, it's still sometimes possible, but this will be discussed in the next lecture. Now let's concentrate on equal-sized arrays.

![image](https://github.com/user-attachments/assets/030ac81e-5d40-4c33-90f4-36334d1d1604)

## 20 - Introduction to numpy - Broadcasting
Binary operations like addition, subtraction, multiplication and so on between two arrays are only possible if the arrays can be broadcasted into the same size and shape.

![image](https://github.com/user-attachments/assets/d2abbeb1-e3c7-4b8e-8b79-8680c265d2e4)

## 21 - Introduction to numpy - Mathematical Functions
numpy provides lots of mathematical functions which are vectorized, just like the arithmetic operations, which means they operate elementwise. They return new arrays of the same size and shape with elements of the same type or another type if necessary.

![image](https://github.com/user-attachments/assets/c358926a-358e-4a74-b165-22e17fc5f474)

## 22 - Introduction to numpy - Aggregation
numpy provides functions for aggregation. They take an array as an argument and return either another array or a scalar. We can also use their counterparts implemented as methods in the ndarray class.

![image](https://github.com/user-attachments/assets/ec8d2ffc-5688-49b4-b1fb-6c22bab3e219)

## 23 - Introduction to numpy - Comparing Arrays
Given two numpy arrays, we can compare them elementwise. What we get is a new array with boolean values. We can use all the standard comparison operators like ==, !=, >, <, >=, <=. If the shapes of the arrays are different, all the broadcasting rules apply.

![image](https://github.com/user-attachments/assets/493f1524-7cd0-415e-82c7-b19e2b06ebb1)

## 24 - Introduction to numpy - Conditional Functions
We can pick values from arrays based on a condition. To this end we can use the functions np.where, np.select and np.choose. Let's have a look at them now one by one.

![image](https://github.com/user-attachments/assets/3eab78b7-5237-49cc-9b23-2afda07884fa)

## 25 - Introduction to numpy - Logical Functions
numpy offers us a couple of logical functions, in particular np.logical_and, np.logical_or, np.logical_xor and np.logical_not. Let's start with the last one. We use the np.logical_not function to elementwise invert an array. Zero is interpreted as False, any nonzero value as True.

![image](https://github.com/user-attachments/assets/32ba826c-9fb4-4749-aad9-f09fc007e7ad)

## 26 - Introduction to numpy - Random Numbers
numpy provides a vast functionality for random numbers. The function we're going to need are in the np.random module. There are lots of them, let's just have a look at some.

![image](https://github.com/user-attachments/assets/c4fbcce9-d01f-43d1-bbf7-81c9eb4429f2)

## 27 - Introduction to numpy - Set Operations
In Python if we need a collection where all elements are unique, we use sets. In numpy we can also make all the elements in an array unique and then we can work on it like on a set. In order to make an array unique, we use the np.unique function. It also sorts the array.

![image](https://github.com/user-attachments/assets/37bac240-b2a2-4171-a198-2a8689d1e8f2)

## 28 - Introduction to numpy - Non-Elementwise Operations on Arrays
Most of the functions we have been talking about up to now work on an element by element basis. Some, like the aggregation functions, either reduce arrays to scalars or flatten them to arrays of fewer dimensions. But there are also functions in numpy that operate on arrays as a whole rather than elementwise and return transformed arrays of the same size, although not necessarily of the same shape.

![image](https://github.com/user-attachments/assets/d2497e3e-663e-438f-bdd9-0254d62fe22f)

## 29 - Introduction to numpy - The Dot Product
If we multiply two matrix arrays, the multiplication is performed elementwise, which is not what real matrix multiplication is.

![image](https://github.com/user-attachments/assets/58f5f847-ea88-4177-83c7-91e911a7aafc)

## 30 - Introduction to numpy - Course Wrap-Up

