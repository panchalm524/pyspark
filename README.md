# pyspark-tutorials
Code snippets and tutorials for working with social science data in PySpark. Note that each .ipynb file can be downloaded and the code blocks executed or experimented with directly using a Jupyter (formerly IPython) notebook, or each one can be displayed in your browser as markdown text just by clicking on it.

Spark Social Science Manual
The tutorials included in this repository are geared towards social scientists and policy researchers that want to undertake research using "big data" sets. A manual to accompany these tutorials is linked below. The objective of the manual is to provide social scientists with a brief overview of the distributed computing solution developed by The Urban Institute's Research Programming Team, and of the changes in how researchers manage and analyze data required by this computing environment.

Spark Social Science Manual

If you're new to Python entirely, consider trying an intro tutorial first. Python is a language that stresses readability of code, so it won't be too difficult to dive right in. This is one good interactive tutorial.

After that, or if you're already comfortable with Python basics, get started with pySpark with these two lessons. They will assume you are comfortable with what Python code looks like and in general how it works, and lay out some things you will need to know to understand the other lessons.

Basics 1

Reading and writing data on S3
Handling column data types
Basic data exploration and describing
Renaming columns
Basics 2

How pySpark processes commands - lazy computing
Persisting and unpersisting
Timing operations
Basic data tasks are covered in the following guides. Note that these are not intended to be comprehensive! They cover many of the things that are most common, but others may require you to look them up or experiment. Hopefully this framework gives you enough to get started.

Merging Data

Using unionAll to stack rows by matching columns
Using join to merge columns by matching specific row values
Missing Values

Handling null values on loading
Counting null values
Dropping null values
Replacing null values
Moving Average Imputation

Using pySpark window functions
Calculating a moving average
Imputing missing values
Pivoting/Reshaping

Using groupBy to organize data
Pivoting data with an aggregation
Reshaping from long to wide without aggregation
Resampling

Upsampling data based on a date column
Using datetime objects
Subsetting

Filtering data based on criteria
Taking a randomized sample
Summary Statistics

Using describe
Adding additional aggregations to describe output
Graphing

Aggregating to use Matplotlib and Pandas
The pySpark bootstrap used by the Urban Institute to start a cluster on Amazon Web Services only installs a handful of Python modules. If you need others for your work, or specfic versions, this tutorial explains how to get them. It uses only standard Python libraries, and is therefore not specific to the pySpark environment:

Installing Python Modules

Using the pip module for Python packages
And finally, now that Spark 2.0 is deployed to Amazon Web Services development has begun on OLS and GLM tutorials, which will be uploaded when complete. Introduction to GLM
