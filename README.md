# Analyzing-sales-price-of-cars


The data that we are going to use in this example is about cars. Specifically containing various information datapoints about the used cars, like their price, color, etc. Here we need to understand that simply collecting data isn’t enough. Raw data isn’t useful. Here data analysis plays a vital role in unlocking the information that we require and to gain new insights into this raw data. Consider this scenario, our friend, Otis, wants to sell his car. But he doesn’t know how much should he sell his car for! He wants to maximize the profit but he also wants it to be sold for a reasonable price for someone who would want to own it. So here, us, being a data scientist, we can help our friend Otis. Let’s think like data scientists and clearly define some of his problems: For example, is there data on the prices of other cars and their characteristics? What features of cars affect their prices? Colour? Brand? Does horsepower also affect the selling price, or perhaps, something else? As a data analyst or data scientist, these are some of the questions we can start thinking about. To answer these questions, we’re going to need some data. But this data is in raw form. Hence we need to analyze it first..

Process to convert .data file to .csv:

1.open MS Excel

2.Go to DATA

3.Select From text

4.Check box tick on comas(only)

5.Save as .csv to your desired location on your pc!

6.Modules needed:


pandas: Pandas is an opensource library that allows you to perform data manipulation in Python. Pandas provide an easy way to create, manipulate and wrangle the data.

numpy: Numpy is the fundamental package for scientific computing with Python. numpy can be used as an efficient multi-dimensional container of generic data.

matplotlib: Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of formats.

seaborn: Seaborn is a Python data-visualization library that is based on matplotlib. Seaborn provides a high-level interface for drawing attractive and informative statistical graphics.

scipy: Scipy is a Python-based ecosystem of open-source software for mathematics, science, and engineering.

Steps for installing these packages:


If you are using anaconda- jupyter/ syder or any other third party softwares to write your python code, make sure to set the path to the “scripts folder” of that software in command prompt of your pc.
Then type – pip install package-name

Example:

pip install numpy
Then after the installation is done. (Make sure you are connected to the internet!!) Open your IDE, then import those packages. To import, type – import package name

Example:

import numpy
Steps that are used in the following code (Short description):

Import the packages
Set the path to the data file(.csv file)

Find if there are any null data or NaN data in our file. If any, remove them
Perform various data cleaning and data visualisation operations on your data. These steps are illustrated beside each line of code in the form of comments for better understanding, as it would be better to see the code side by side than explaining it entirely here, would be meaningless.
Obtain the result!
