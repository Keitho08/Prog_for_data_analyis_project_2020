
# Programing for Data Analysis - Project 2020

## Galway Mayo Intitute of Technology - HDip Data Analytics 2020-2021
***
### Keith Brazill - G00387845
***

**Project Brief:**

*Problem statement*

For this project you must create a data set by simulating a real-world phenomenon of your choosing. You may pick any phenomenon you wish – you might pick one that is of interest to you in your personal or professional life. Then, rather than collect data related to the phenomenon, you should model and synthesise such data using Python. We suggest you use the numpy.random package for this purpose.

*Specifically, in this project you should:*

Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.
Investigate the types of variables involved, their likely distributions, and their relationships with each other.
Synthesise/simulate a data set as closely matching their properties as possible.
Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.
Note that this project is about simulation – you must synthesise a data set. Some students may already have some real-world data sets in their own files. It is okay to base your synthesised data set on these should you wish (please reference it if you do), but the main task in this project is to create a synthesised data set. The next section gives an example project idea.

*Example project idea*

As a lecturer I might pick the real-world phenomenon of the performance of students studying a ten-credit module. After some research, I decide that the most interesting variable related to this is the mark a student receives in the module - this is going to be one of my variables (grade). Upon investigation of the problem, I find that the number of hours on average a student studies per week (hours), the number of times they log onto Moodle in the first three weeks of term (logins), and their previous level of degree qualification (qual) are closely related to grade. The hours and grade variables will be non-negative real number with two decimal places, logins will be a non-zero integer and qual will be a categorical variable with four possible values: none, bachelors, masters, or phd. After some online research, I find that full-time post-graduate students study on average four hours per week with a standard deviation of a quarter of an hour and that a normal distribution is an acceptable model of such a variable. Likewise, I investigate the other four variables, and I also look at the relationships between the variables. I devise an algorithm (or method) to generate such a data set, simulating values of the four variables for two-hundred students. I detail all this work in my notebook, and then I add some code in to generate a data set with those properties.

**Getting started**

In order to run the jupyter notebook in this repository the following is recommended to download and install Python using Anaconda. Anaconda is available at:
https://docs.anaconda.com/anaconda/install/

**Packages used in this project**

The following packages were used in this assignment to carry out the required tasks in the project brief:

* Python https://www.python.org/downloads/
* Numpy http://www.numpy.org/ - The fundamental package for scientific computing with Python.
* Jupyter Notebook https://jupyter.org/ - Project Jupyter exists to develop open-source software, open-standards, and services for interactive computing across dozens of programming languages.
* matplotlib.pyplot https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.html - matplotlib.pyplot is a state-based interface to matplotlib. It provides a MATLAB-like way of plotting. pyplot is mainly intended for interactive plots and simple cases of programmatic plot generation.
* seaborn https://seaborn.pydata.org/ - Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
* pandas https://pandas.pydata.org/ - pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.

**Importing Packages**

The above packages can be imported into Python. Use Import function in the notebook or in ipython to import:

* import numpy as np
* import seaborn as sns
* import matplotlib.pyplot as plt
* import pandas as pd

Jupyter notebook is already imported as standard in python when installed via Anaconda. It can be accessed by typing "jupyter notebook" in the command line which will open up the notebook in your browser.

**Summary of Repository**

The notebook Programming_for_Data_Analysis_Project_2020.ipynb contained within this repository,  is prepared in response to the brief assigned for the project 2020 in the module of Programming for Data Analytic's 2020 as part of the postgraduate diploma in Computer Science with Data Analytics at Galway Mayo Institute of Technology.

This notebook is structured as follow's:

1. Introduction
2. The Project Brief
3. Our Real World Phenomenon  
4. The Synthesised Data
5. Analysis of the Synthesised Data
6. Conclusion
7. References

The approach to the project will be to examine real world data sets that are of particular interest (real world phenomenon) and then we will create synthesised random data to replicate the real world data. Once we are satisfied this data is similar to our real life data we will carry out some further analysis on our synthesised data to examine relationships and patterns in the data set.

Throughout the notebook each of the above sections is cleary explained using a combination of code and markdown cells.

**References** 

*A complete list of all references used in this repository is included below:*

1. McLoughlin, I., 2020. Ianmcloughlin/Jupyter-Teaching-Notebooks. [online] GitHub. Available at: <https://github.com/ianmcloughlin/jupyter-teaching-notebooks/blob/master/fitting-lines.ipynb> [Accessed 21 December 2020].
2. Docs.python.org. 2020. Datetime — Basic Date And Time Types — Python 3.9.1 Documentation. [online] Available at: <https://docs.python.org/3/library/datetime.html> [Accessed 21 December 2020].
3. Met.ie. 2020. Historical Data - Met Éireann - The Irish Meteorological Service. [online] Available at: <https://www.met.ie/climate/available-data/historical-data> [Accessed 21 December 2020].
4. data.gov.ie. 2020. Covidstatisticsprofilehpscireland. [online] Available at: <https://data.gov.ie/dataset/covidstatisticsprofilehpscirelandopendata1/resource/2bf52086-d76c-42b2-91f6-b99ec5952173> [Accessed 21 December 2020].
5. Docs.scipy.org. 2020. Numpy.Random.Randint — Numpy V1.15 Manual. [online] Available at: <https://docs.scipy.org/doc/numpy-1.15.0/reference/generated/numpy.random.randint.html> [Accessed 21 December 2020].
6. En.wikipedia.org. 2020. Sine. [online] Available at: <https://en.wikipedia.org/wiki/Sine> [Accessed 21 December 2020].
7. How To Get Numpy Random Generated Numbers In A Certain Pattern. [online] Stack Overflow. Available at: <https://stackoverflow.com/questions/65236116/how-to-get-numpy-random-generated-numbers-in-a-certain-pattern-to-simulate-for-e> [Accessed 21 December 2020].
8. Seaborn.pydata.org. 2020. Timeseries Plot With Error Bands — Seaborn 0.11.1 Documentation. [online] Available at: <https://seaborn.pydata.org/examples/errorband_lineplots.html> [Accessed 21 December 2020].
9. Regplot, U., 2020. Using Datetimes With Seaborn's Regplot. [online] Stack Overflow. Available at: <https://stackoverflow.com/questions/40558128/using-datetimes-with-seaborns-regplot/40559557> [Accessed 21 December 2020].
10. Medium. 2020. Combo Charts With Seaborn And Python. [online] Available at: <https://towardsdatascience.com/combo-charts-with-seaborn-and-python-2bc911a08950> [Accessed 21 December 2020].
11. Gov.ie. 2020. Latest Updates On COVID-19 (Coronavirus). [online] Available at: <https://www.gov.ie/en/news/7e0924-latest-updates-on-covid-19-coronavirus/> [Accessed 21 December 2020].
12. Seaborn.pydata.org. 2020. Seaborn.Kdeplot — Seaborn 0.11.1 Documentation. [online] Available at: <https://seaborn.pydata.org/generated/seaborn.kdeplot.html> [Accessed 21 December 2020].
13. S3.amazonaws.com. 2020. [online] Available at: <https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf> [Accessed 21 December 2020].
14. docs.python.org. 2020. Datetime. [online] Available at: <https://docs.python.org/3/library/datetime.html> [Accessed 21 December 2020].
15. GitHub. 2020. Adam-P/Markdown-Here. [online] Available at: <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images> [Accessed 21 December 2020].
16. Data36. 2020. Linear Regression In Python Using Numpy + Polyfit (With Code Base). [online] Available at: <https://data36.com/linear-regression-in-python-numpy-polyfit/> [Accessed 21 December 2020].
17. Google Docs. 2020. Modeling Temperature With Sine Waves. [online] Available at: <https://docs.google.com/document/preview?hgd=1&id=1MdxsHHplRsjeKWHcjrdYw8vDrHNAR7yJQvq9salYGmU> [Accessed 21 December 2020].
18. Numpy.org. 2020. Numpy.Sin — Numpy V1.19 Manual. [online] Available at: <https://numpy.org/doc/stable/reference/generated/numpy.sin.html> [Accessed 21 December 2020].
19. Seaborn.pydata.org. 2020. Seaborn.Lmplot — Seaborn 0.11.1 Documentation. [online] Available at: <https://seaborn.pydata.org/generated/seaborn.lmplot.html> [Accessed 21 December 2020].
20. Brazill, K., 2020. Keitho08/Fundamentals_2020. [online] GitHub. Available at: <https://github.com/Keitho08/Fundamentals_2020/blob/main/KeithBrazill_FundamentalsTasks_2020.ipynb> [Accessed 21 December 2020].
21. VanderPlas, J., 2020. Visualization With Seaborn | Python Data Science Handbook. [online] Jakevdp.github.io. Available at: <https://jakevdp.github.io/PythonDataScienceHandbook/04.14-visualization-with-seaborn.html> [Accessed 21 December 2020].

***
# End