
Python for Social Scientists
==============================

Python is an increasingly popular tool for data analysis in the social scientists. Empowered by a number of libraries that have reached maturity, R and Stata users are increasingly moving to Python in order to take advantage of the beauty, flexibility, and performance of Python without sacrificing the functionality these older programs have accumulated over the years.

But while Python has much to offer, existing Python resources are not always well-suited to the needs of social scientists. With that in mind, I've recently created a new resource -- www.pythonforsocialscientists.org -- tailored specifically to the goals and desires of the social scientist python user. 

The site is **not** a new set of tutorials, however -- there are *more* than enough Python tutorials in the world. Rather, the aim of the site is to curate and annotate existing resources, and to provide users guidance on what topics to focus on and which to skip. 

Why A Site for Social Scientists?
-----------------------------------
The aim of Python for Social Scientists (PSS) is threefold. First, PSS is designed to point social scientists to appropriate tutorials, and instruct users on the skills they should prioritize. Most current Python resources are written for software developers. But social scientists have very different needs than software developers when it comes to skill development. Most software developers want to learn Python so they can write new tools and develop new functionalities. Social scientists, by contrast, are primarily interested in quickly learning how to use existing tools to do their science. As a result, lots of aspects of Python -- like defining new classes, dealing with inheritance, or building generators -- just aren't relevant for social scientists. Some social scientists may *eventually* choose to learn these skills, but there's not reason they should have to wrestle with this topics when getting started. 

Second, PSS is meant to be a guide to the sometimes bewildering array of libraries in the Python eco-system. Most Python libraries do a great job of documenting their own functionality, but *finding* the right library can often be much harder. This is especially true because social scientists want to minimize the amount of time they have to invest in learning new libraries, and so they want to make sure they pick the most appropriate library before they invest in getting to know it. Though it requires some subjectivity, PSS aims to provide honest, experience-driven advice on which libraries are most likely to be easiest to use and most generally applicable for different kinds of research. 

Finally, many social scientists are coming to Python from R or Stata, and so PSS provides resources tailored to making these transitions as easy as possible (`here for R <http://www.pythonforsocialscientists.org/python_for_r.html>`_ and `here for Stata <http://www.pythonforsocialscientists.org/python_for_stata.html>`_), with special attention to the kinds of subtle differences between these languages that might otherwise trip up new users. 

Given this mission, PSS is necessarily subjective. At the moment, it largely reflects the experiences of myself and my close colleagues, but if you see something you disagree with, **please** `let my know why <mailto:nickeubank+pss@gmail.com>`_, or contribute a `pull-request <https://github.com/nickeubank/python-for-social-scientists>`_ on github! The more input we get, the better the site will become.  


Recommended Python Topics
-----------------------------------

PSS is divided into three sections: a sequence of four pages that cover the core skills all social scientists need to work in Python; a set of pages that describe good resources for work in different research areas (network analysis, text analysis, etc.); and finally a set of resources on related skills (like using the command line or git). 

Core Skills
^^^^^^^^^^^^^^
The four core pages cover: 
* Setting up Python using the Anaconda distribution
* Learning basic Python
* Becoming familiar with the `pandas` library
* Managing packages with `pip` and `anaconda`

Of this, the most valuable page is likely the second page, which not only points users to well-targeted tutorials, but also emphasizes skills social scientists need. In particular, it emphasizes the importance of understanding data types, defining functions, writing loops, understanding mutable versus immutable data types and references, string methods, and library imports, while pointing users away from tutorials on things like defining classes or working with exceptions, which just aren't immediately relevant. 

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
