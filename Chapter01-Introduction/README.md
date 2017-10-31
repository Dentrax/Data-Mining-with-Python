<h1 align="center">Data Mining with Python [Chapter 01 - Introduction]</h1>

[Chapter 01 - Introduction]
--------------------------

* ["Data Mining Processes"](#data-mining-processes)
* [Important Libraries](#important-libraries)
    - [Pandas](#pandas)
    - [NumPy](#numpy)
    - [SciPy](#scipy)
    - [Matplotlib](#matplotlib)
    - [IPython](#ipython)
    - [Scikit-Learn](#scikit-learn)
    - [Statsmodels](#statsmodels)
* [First Example](#first-example)
* [Data Types](#data-types)
* [Histogram](#histogram)
* [Question](#question)

## Data Mining Processes
--------------------------

**CRISP-DM Methodology**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining)**

![Preview Thumbnail](https://raw.githubusercontent.com/Dentrax/Data-Mining-with-Python/master/Chapter01-Introduction/images/figure_crisp-dm.png)

**Major Phases**

* Business Understanding

This initial phase focuses on understanding the project objectives and requirements from a business perspective, and then converting this knowledge into a data mining problem definition, and a preliminary plan designed to achieve the objectives.

* Data Understanding

    - Classification : Data is divided into classes according to specific categories.

    - Clustering : It performs clustering according to specific tags.

    - Assocation Rules : Like "Customers who bought this item also bought" as the relationship between the datas.

* Data Preparation

The data preparation phase covers all activities to construct the final dataset from the initial raw data. The data to be valued is prepared. It should not be empty. Empty fields are filled with a median or arithmetic mean.

* Modeling

In this phase, various modeling techniques are selected and applied, and their parameters are calibrated to optimal values. Statistical machine-learning and artificial intelligence methods are used.

* Evaluation

The received datas from Model is evaluated. A key objective is to determine if there is some important business issue that has not been sufficiently considered. At the end of this phase, a decision on the use of the data mining results should be reached.

* Deployment

Depending on the requirements, the deployment phase can be as simple as generating a report or as complex as implementing a repeatable data scoring or data mining process. It is called phasing in the display of data.

![Preview Thumbnail](https://raw.githubusercontent.com/Dentrax/Data-Mining-with-Python/master/Chapter01-Introduction/images/figure_olap_vs_oltp.jpg)

**OLTP**

`On-line Transaction Processing` is characterized by a large number of short on-line transactions (INSERT, UPDATE, DELETE). The main emphasis for OLTP systems is put on very fast query processing, maintaining data integrity in multi-access environments and an effectiveness measured by number of transactions per second. In OLTP database there is detailed and current data, and schema used to store transactional databases is the entity model.

**OLAP**

`On-line Analytical Processing` is characterized by relatively low volume of transactions. Queries are often very complex and involve aggregations. For OLAP systems a response time is an effectiveness measure. OLAP applications are widely used by Data Mining techniques. In OLAP database there is aggregated, historical data, stored in multi-dimensional schemas.

**Data Warehouse (DWH)**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/Data_warehouse)**

`DWH` is a system used for reporting and data analysis, and is considered a core component of business intelligence. DWHs are central repositories of integrated data from one or more disparate sources. They store current and historical data in one single place that are used for creating analytical reports for knowledge workers throughout the enterprise.

## Important Libraries
--------------------------

## Pandas

Click here for **[Official Page](http://pandas.pydata.org/)**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/Pandas_(software))**

**About**

`Pandas` is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language. It is already well on its way toward this goal.

1. Tabular data with heterogeneously-typed columns, as in an SQL table or Excel spreadsheet

2. Ordered and unordered (not necessarily fixed-frequency) time series data

3. Arbitrary matrix data (homogeneously typed or heterogeneous) with row and column labels

4. Any other form of observational / statistical data sets. The data actually need not be labeled at all to be placed into a pandas data structure

| Developer		 | Written In  | OS               | Type                  | License |
| -------------- |:-----------:|:----------------:|:---------------------:|:-------:|
| `Wes McKinney` | `Python`    | `Cross platform` | `Technical computing` | `BSD`   |

## NumPy

Click here for **[Official Page](http://www.numpy.org/)**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/NumPy)**

**About**

`NumPy` is the fundamental package for scientific computing with Python. It contains among other things:

1. A powerful N-dimensional array object

2. Sophisticated (broadcasting) functions

3. Tools for integrating C/C++ and Fortran code

4. Useful linear algebra, Fourier transform, and random number capabilities

| Developer		        | Written In  | OS               | Type                  | License |
| --------------------- |:-----------:|:----------------:|:---------------------:|:-------:|
| `Community project`	| `Python, C` | `Cross platform` | `Technical computing` | `BSD`   |

## SciPy

Click here for **[Official Page](https://www.scipy.org/)**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/SciPy)**

**About**

`SciPy` library depends on NumPy, which provides convenient and fast N-dimensional array manipulation. The SciPy library is built to work with NumPy arrays, and provides many user-friendly and efficient numerical routines such as routines for numerical integration and optimization. Together, they run on all popular operating systems, are quick to install, and are free of charge. NumPy and SciPy are easy to use, but powerful enough to be depended upon by some of the world’s leading scientists and engineers. If you need to manipulate numbers on a computer and display or publish the results, Scipy is the tool for the job.

Refers to several related but distinct entities:

1. The SciPy ecosystem, a collection of open source software for scientific computing in Python

2. The community of people who use and develop this stack

3. Several conferences dedicated to scientific computing in Python - SciPy, EuroSciPy and SciPy.in

4. The SciPy library, one component of the SciPy stack, providing many numerical routines


| Developer		        | Written In                | OS               | Type                  | License |
| --------------------- |:-------------------------:|:----------------:|:---------------------:|:-------:|
| `Community project`	| `Python, Fortran, C/C++`  | `Cross platform` | `Technical computing` | `BSD`   |

## Matplotlib

Click here for **[Official Page](https://matplotlib.org/)**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/Matplotlib)**

**About**

`Matplotlib` is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shell, the jupyter notebook, web application servers, and four graphical user interface toolkits.

| Developer		        | Written In | OS               | Type       | License |
| --------------------- |:----------:|:----------------:|:----------:|:-------:|
| `Michael Droettboom`	| `Python`   | `Cross platform` | `Plotting` | `BSD`   |

## IPython

Click here for **[Official Page](https://ipython.org/)**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/IPython)**

**About**

`IPython` is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language, that offers enhanced introspection, rich media, additional shell syntax, tab completion, and rich history. IPython currently provides the following features:

1. Powerful interactive shells (terminal and Qt-based)

2. A browser-based notebook with support for code, text, mathematical expressions, inline plots and other rich media

3. Support for interactive data visualization and use of GUI toolkits

4. Flexible, embeddable interpreters to load into one’s own projects

5. Easy to use, high performance tools for parallel computing

| Developer		        | Written In                | OS               | Type    | License |
| --------------------- |:-------------------------:|:----------------:|:-------:|:-------:|
| `Fernando Perez`      | `Python, JS, CSS, HTML`   | `Cross platform` | `Shell` | `BSD`   |

## Scikit-Learn

Click here for **[Official Page](http://scikit-learn.org/)**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/Scikit-learn)**

**About**

`Scikit-learn` (formerly scikits.learn) is a free software machine learning library for the Python programming language. It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.

1. Simple and efficient tools for data mining and data analysis

2. Accessible to everybody, and reusable in various contexts

3. Built on NumPy, SciPy, and matplotlib

4. Open source, commercially usable - BSD license

| Developer		        | Written In                | OS               | Type               | License |
| --------------------- |:-------------------------:|:----------------:|:------------------:|:-------:|
| `David Cournapeau`    | `Python, Cython, C/C++`   | `Cross platform` | `Machine Learning` | `BSD`   |

## Statsmodels

Click here for **[Official Page](http://www.statsmodels.org/)**

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/Statsmodels)**

**About**

`statsmodels` is a Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration. An extensive list of result statistics are available for each estimator. The results are tested against existing statistical packages to ensure that they are correct.

1. Linear regression models

2. Mixed Linear Model with mixed effects and variance components

3. Generalized linear models with support for all of the one-parameter exponential family distributions

4. Generalized Estimating Equations for one-way clustered or longitudinal data

| Developer		        | Written In | OS               | Type                  | License |
| --------------------- |:----------:|:----------------:|:---------------------:|:-------:|
| `Community project`	| `Python`   | `Cross platform` | `Technical computing` | `BSD`   |

## First Example
--------------------------

## Data Types
--------------------------

**Data Types**

* Qualitative

* Quantitative 

    - Discrete [Numerical]

    It is integer-based. It usually refers to situations such as the number of occurrences of an event.

    Example : (How many times have a customer bought a year?)

        - Binary

        - Norminal [Categorical]

        - Ordinal [Categorical]

            Ordinal data is also categorical data type. However, among their values, ordered relationship.

            Example : (Movie ratings, Customer product reviews etc.)

    - Continuous [Numerical]

    These types of data are measured values. Both integers and commas can. That is, they can take all the values on the number line.

    Example : (What are the weight of students in a school?)

        - Inverval

        - Ratio

**Examples**

> * `[Continuous]`  How much gas is in your tank?
> * `[Ordinal]`     Your assessment score for hospital service?
> * `[Categorical]` Places where students in the classroom?
> * `[Discrete]`    Age of students in the class?
> * `[Continuous]`  Total money spent at the shopping mall?

## Histogram
--------------------------

Click here for **[Wikipedia Page](https://en.wikipedia.org/wiki/Histogram)**

![Preview Thumbnail](https://raw.githubusercontent.com/Dentrax/Data-Mining-with-Python/master/Chapter01-Introduction/images/figure_histogram-graph.png)

`Histogram` is an accurate graphical representation of the distribution of numerical data. It is an estimate of the probability distribution of a continuous variable. It is a kind of bar graph. To construct a histogram, the first step is to "bin" the range of values—that is, divide the entire range of values into a series of intervals—and then count how many values fall into each interval. The bins are usually specified as consecutive, non-overlapping intervals of a variable. The bins (intervals) must be adjacent, and are often (but are not required to be) of equal size.

**Creating a Histogram**

1. First, all the data are sorted from small to large.
2. Find the range of data group. The range of a set of data is, the difference between the largest and smallest values.
3. Determines the how many pieces of data will be separated.
4. The group width is found. The largest natural number is taken as the group width, from the number obtained by dividing the value of the Range by the number of groups.
5. The data are divided into groups according to the data width, beginning with the smallest data.
6. The numbers of data in groups and groups that are created are tabulated.
7. The histogram is drawn by looking at the table.

**Drawing a Sample Histogram**

Datas : `162, 161, 170, 167, 170, 173, 163, 176, 174, 180, 179, 164, 169, 175, 177, 185, 169, 172, 180, 175, 168, 163, 172, 172, 169, 173, 170, 171, 168, 166, 167, 170`

1. All the data are sorted from small to large

Datas : `161, 162, 163, 163, 164, 166, 167, 167, 168, 168, 169, 169, 169, 170, 170, 170, 170, 171, 172, 172, 172, 173, 173, 174, 175, 175, 176, 177, 179, 180, 180, 185`

2. Range of data group : `185 – 161 = 24`

3. We have determined how many pieces of data to leave (Used 5 in this example)

4. Group width : `24 : 5 = 4,8` (the smallest natural number greater than this number is `5`)

5. `161-162-163-164-165` are written as `161-165`. (separation by `5`)  In that case, our groups: `161-165, 166-170, 171-175, 176-180, 181-185`

6. The numbers of data in groups and groups that are created are tabulated

| Groups    | People Count | 
| --------- |:------------:|
| `161-165` | `5`          | 
| `166-170` | `12`         | 
| `171-175` | `9`          | 
| `176-180` | `5`          | 
| `181-185` | `1`          | 


## Question
--------------------------

* Select from the DataFrame's between 5-10 rows and "Previous Employers" and "Hired" columns. Assign the result to a new Dataframe. Create a histogram showing the distribution of "Previous Employers" in this subset of data.

**Answer**

Please **[click here](https://github.com/Dentrax/Data-Mining-with-Python/tree/master/Chapter01-Introduction/answers.py)** to see the answer.


