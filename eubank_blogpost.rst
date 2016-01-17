
Python for Social Scientists
==============================

Python is an increasingly popular tool for data analysis in the social scientists. Empowered by a number of libraries that have reached maturity, R and Stata users are increasingly moving to Python in order to take advantage of the beauty, flexibility, and performance of Python without sacrificing the functionality these older programs have accumulated over the years.

But while Python has much to offer, existing Python resources are not always well-suited to the needs of social scientists. With that in mind, I've recently created a new resource -- www.pythonforsocialscientists.org -- tailored specifically to the goals and desires of the social scientist python user. 

The site is **not** a new set of tutorials, however -- there are *more* than enough Python tutorials in the world. Rather, the aim of the site is to curate and annotate existing resources, and to provide users guidance on what topics to focus on and which to skip. 

Why A Site for Social Scientists?
-----------------------------------

Social scientists – and indeed, most data scientists – spend most of their time trying to wrestle individual, idiosyncratic datasets into the shape needed to run statistical analyses.This makes the way most social scientists use Python fundamentally different from how it is used by most software developers. Social scientists are primarily interested in writing relatively simple programs (scripts) that execute a series of commands (recoding variables, merging datasets, parsing text documents, etc.) to wrange their data into a form they can analyze. And because they are usually writing their scripts for a specific, idiosyncratic application and set of data, they are generally not focused on writing generalizable code. 

Social scientists, in other words, tend to be primarily interested in learning to *use existing tools* effectively, not develop new ones. 

Because of this, social scientists learning Python tend to have different priorities in terms of skill development than software developers. Yet most tutorials online were written for developers or computer science students, so one of the aims of PSS is to provide social scientists with some guidance on the skills they should prioritize in their early training. In particular, PSS suggests:

**Need immediately:**

* Data types: integers, floats, strings, booleans, lists, dictionaries, and sets (tuples are kinda optional)
* Defining functions
* Writing loops
* Understanding mutable versus immutable data types
* Methods for manipulating strings
* Importing third party modules

**Things you'll want to know at some point, but not necessary immediately:**

* Debugging
* File input / output (most libraries you'll use have tools to simplify this for you)

**Don't need:**

* Defining or writing classes
* Understanding Exceptions


pandas
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Today, most empirical social science remains organized around tabular data, meaning data that is presented with a different variable in each column and a different observation in each row. As a result, many social scientists using Python are a little confused when they don't find a tabular data structure covered in their intro to Python tutorial. To address this confusion, PSS does its best to introduce users to the `pandas` library as fast as possible. 

The `pandas` library replicates much of the functionality that social scientists are used to finding in Stata or R -- data can be represented in a tabular format, column variables can be easily labeled, and columns of different types (like floats and strings) can be combined in the same dataset. 

`pandas` is also the gateway to many other tools social scientists are likely to use, like graphing libraries (`seaborn` and `ggplot2`) and the `statsmodels` econometrics library. 


Libraries by Research Area
^^^^^^^^^^^^^^^^^^^^^^^^^^^

The aim of the second section is to allow social scientists with a research interest to quickly zero-in on the most useful library for what the want to accomplish. In particular, the site provides the following recommendations for different topics, along with links to materials on optimal use, and guidance on relevant considerations:

* `Network Analysis <http://www.pythonforsocialscientists.org/t_igraph.html>`_: iGraph
* `Text Analysis <http://www.pythonforsocialscientists.org/t_text_analysis.html>`_: NLTK, and if needed coreNLP
* `Econometrics <http://www.pythonforsocialscientists.org/t_statsmodels.html>`_: statsmodels
* `Graphing <http://www.pythonforsocialscientists.org/t_seaborn.html>`_: ggplot and seaborn
* `Big Data <http://www.pythonforsocialscientists.org/t_big_data.html>`_: dask and pyspark
* `Geo-Spatial Analysis <http://www.pythonforsocialscientists.org/t_gis.html>`_: arcpy or geopandas
* `Making code faster <http://www.pythonforsocialscientists.org/t_super_fast.html>`_: %prun in iPython (for profiling) and numba (for JIT compilation)


Want to Get Involved?
-----------------------------------

This site is young, so we are anxious for as much input as possible on content and design. If you have experience in this area you want to share *please* drop me an email or comment on github. 






-----------------------------------
