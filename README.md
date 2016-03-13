# Scientific Python course

Lecture notes from the course taught at the [University of Bordeaux](http://www.u-bordeaux.com) in the academic year 2015/16 for PhD students.  
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.  

Each student needs to come with a notebook computer running either Linux, OSX or Windows.  

![](XKCD.png)
Adapted from https://xkcd.com/353/

|

The scientific Python ecosystem is made of several modules that constitute
together the scientific stack. There are hundreds of
[Python scientific packages](https://pypi.python.org/pypi?:action=browse&c=385)
and most of them are built on top of numpy, scipy, matplotib, pandas, cython
and/or sympy. We won't cover everything in this short course, but you should
get enough information to decide if your research can benefit from Python. And
I bet it will likely do.

Also, make sure to have a look at the [awesome python](https://github.com/vinta/awesome-python), a curated list of Python frameworks, libraries and software.

|

This course is mostly based on the teaching material kindly provided by:

* [Software Carpentry]
* [Scipy Lecture Notes]



|

Beginner course
-------------------------------------------------------------------------------

Day 1 | Monday, March 14, 2016     |          | Day 2 | Tuesday, March 15, 2016 
----- | ---------------------------| -------- | ----- | ----------------------------------------
09:00 | Installation & Welcome     | –––––––– |       | 
09:15 | [Introduction]() (part 1)  |          | 09:00 | [Computation I]() (part 1)
10:30 | *Coffee break*             |          | 10:30 | *Coffee break & questions*
10:45 | [Introduction]()  (part 2) |          | 10:45 | [Computation I]() (part 2)
12:00 | *Lunch break*              |          | 12:00 | *Lunch break*
14:00 | [Programming]() (part 1)   |          | 14:00 | [Visualization I]() (part 1)
15:30 | *Coffee break & questions* |          | 15:30 | *Coffee break & questions*
15:45 | [Programming]() (part 2)   |          | 15:45 | [Visualization I]() (part 2)
17:00 | *Wrap-up*                  |          | 17:00 | *Wrap-up*

|

### Introduction to Python

This [gentle introduction to Python](introduction.md) explains how to install
Python and introduces some very simple concepts related to numerical
expressions and other data types.

### Programming with Python

[Scipy Lecture Notes]. This
[lecture](http://www.scipy-lectures.org/intro/language/python_language.html)
does not attempt to be comprehensive and cover every single feature, or even
every commonly used feature. Instead, it introduces many of Python's most
noteworthy features, and will give you a good idea of the language’s flavor and
style.


### Scientific computation I

[Scipy Lecture Notes]. The primary goal of this
[lesson](http://www.scipy-lectures.org/intro/numpy/index.html) is to introduce
the numpy (numerical python) module which is de facto the standard module for
numerical computing with Python. It is essential for you to become familiar
with this module since it will be used everywhere in the next lessons.

**See also**:

  * [Numpy tutorial](https://github.com/rougier/numpy-tutorial)
  * [100 Numpy exercises](https://github.com/rougier/numpy-100)
  * [Numpy MedKit](http://mentat.za.net/numpy/numpy_advanced_slides/)

### Scientific visualization I

This [tutorial](https://github.com/rougier/matplotlib-tutorial) gives an
overview of Matplotlib, the core tool for 2D & 2.5D plotting that produces
publication quality figures as well as interactive environments across
platforms.

**See also**:

  * [10 Simple rules for better figures](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833)
  * [Pyplot tutorial](http://matplotlib.org/users/pyplot_tutorial.html)
  
  
|

Advanced course
-------------------------------------------------------------------------------

Day 1 | Thursday, March 16, 2016    |          | Day 2 | Friday, March 17, 2016 
----- | --------------------------- | -------- | ----- | ----------------------------------------
09:00 | [Computation II]() (part 1) | –––––––– | 09:00 | [C/Python integration]() (part 1)
10:30 | *Coffee break & questions*  |          | 10:30 | *Coffee break & questions*
10:45 | [Computation II]() (part 2) |          | 10:45 | [C/Python integration]() (part 2)
12:00 | *Lunch break*               |          | 12:00 | *Lunch break*
14:00 | [Version control]() (part 1)|          | 14:00 | [Visualization II]() (part 1)
15:30 | *Coffee break & questions*  |          | 15:30 | *Coffee break & questions*
15:45 | [Version control]() (part 2)|          | 15:45 | [Visualization II]() (part 2)
17:00 | *Wrap-up*                   |          | 17:00 | *Wrap-up*

|

### Scientific computation II

[Scipy Lecture Notes]. This
[lesson](http://www.scipy-lectures.org/intro/scipy.html) introduces the scipy
package that contains various toolboxes dedicated to common issues in
scientific computing. Its different submodules correspond to different
applications, such as interpolation, integration, optimization, image
processing, statistics, special functions, etc.

**See also**:

  * [Scipy Tutorial](http://docs.scipy.org/doc/scipy/reference/tutorial/)
  * [Numerical Analysis: Python vs Matlab](http://hyperpolyglot.org/numerical-analysis)


### Version control

[Software Carpentry]. This lesson introduces
[version control using git](http://swcarpentry.github.io/git-novice/01-basics.html). Version
control is the lab notebook of the digital world: it's what professionals use
to keep track of what they’ve done and to collaborate with other people. And it
isn't just for software: books, papers, small data sets, and anything that
changes over time or needs to be shared can and should be stored in a version
control system.

**See also**:

  * [Git Book](https://git-scm.com/book/en/v2)
  * [Git cheat sheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)


### C/Python integration

[Scipy Lecture Notes]. This
[chapter](http://www.scipy-lectures.org/advanced/interfacing_with_c/interfacing_with_c.html)
contains an introduction to the many different routes for making your native
code (primarily C/C++) available from Python, a process commonly referred to
wrapping. The goal of this chapter is to give you a flavour of what
technologies exist and what their respective merits and shortcomings are, so
that you can select the appropriate one for your specific needs.


### Scientific visualization II

This
[lesson](http://glumpy.readthedocs.org/en/latest/tutorial/introduction.html)
introduces the (modern) OpenGL API through the use of [glumpy](http://glumpy.github.io) 
which a python library for scientific visualization that is both fast, scalable and beautiful.
Glumpy offers an intuitive interface between numpy and modern OpenGL.


|

----

|

![](PhD-Comics.png)


<!----------------------------- External links ------------------------------->
[Python]:     http://www.python.org
[Numpy]:      http://www.numpy.org
[Scipy]:      http://www.scipy.org
[Pandas]:     http://pandas.pydata.org
[Matplotlib]: http://matplotlib.org
[IPython]:    http://ipython.org
[Jupyter]:    http://jupyter.org
[Git]:        https://git-scm.com
[OpenGL]:     https://www.opengl.org
[Glumpy]:     https://glumpy.github.io
[Bokeh]:      https://bokeh.org
[Cython]:     http://cython.org
[Software Carpentry]:  http://software-carpentry.org
[Scipy Lecture Notes]: http://www.scipy-lectures.org
<!---------------------------------------------------------------------------->
