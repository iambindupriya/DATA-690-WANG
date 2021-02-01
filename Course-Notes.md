# Class-Notes
## This file contains every week's notes
## *{Weekx-Lecture-workflow >> Chapter x Notes}*


### Week1-Lecture-workflow

1. This week was an introductory class. I learnt about deepnote platform. It is an all in one platform to write code, markdown, terminals and also has a file management system to upload files directly. I like the platform very much. Especially how everything is integrated into one. 

2. I worked on a starter project where I created ipynb, py, markdown files to test how they work. Markdown is an awesome way to organise lecture notes. It has pre defined headers like h1 h2 etc to distinguish the headings etc.

3. I learnt about some basic python functions like range etc. 

4. The professor also explained about every week assignments, readings, using github to finish tasks every week.


### "PRELIMINARIES" Chapter 1 Notes

**Types of data** 
Tabular, matrices multidimensional, multiple tables, time series

**We us Python for data analysis because**
For data analysis and interactive computing and data visualization, Python will inevi‐ tably draw comparisons with other open source and commercial programming lan‐ guages and tools in wide use, such as R, MATLAB, SAS, Stata, and others

**Python is slower**
python is an interpreted. so it is slower when compared to java or c

**python libraries**
numpy, pandas, matplotlib, scipy, scikit-learn(support machine learning algorithms)

**statsmodels-statistical analysis package**
this package contains sub-modules like ANOVA, AR, ARIMA, VAR, kernel methods, visualisation results support.

**to install and update packages**
use pip install package-name
conda update package-name

**python 3 is well supported and widely deployed**

**community and conferences**
pydata
pystatsmodels
numpy-discussion 
scipy-user are various communities and forums

pycon
eurocon are conferences

**import conventions**
`import numpy as np
    import matplotlib.pyplot as plt
    import pandas as pd
    import seaborn as sns
    import statsmodels as sm`

**jargons**
data wrangling
pseudocode
syntactic sugar

---End of chapter 1 notes---

### "Python Language Basics, IPython, and Jupyter Notebooks" Chapter 2 Notes

**inovke python interpreter**
`$python`
prompt->>>

**IPython executes the code using this command**
`ipython`

**tab completion**
While entering expressions in the shell, pressing the Tab key will search the namespace for any variables (objects, functions, etc.) matching the characters typed so far


**to import modules**
`import module-name`

**? is used for introspection**
object? --> means
If the object is a function or instance method, the docstring, if defined, will also be shown

**to write block of code in python**
indentation is used rather than curly braces

**Object**
Every number, string, data structure, function, class, module, and so on exists in the Python interpreter in its own “box,” which is referred to as a Python object. Each object has an associated type (e.g., string or function) and internal data. In prac‐ tice this makes the language very flexible, as even functions can be treated like any other object.

**comments -->#**

**Assignment - Importance**
Assignment is also referred to as binding, as we are binding a name to an object. Variable names that have been assigned may occasion‐ ally be referred to as bound variables.

**Referencing in python, dynamic referencing**
When you pass objects as arguments to a function, new local variables are created ref‐ erencing the original objects without any copying. If you bind a new object to a vari‐ able inside a function, that change will not be reflected in the parent scope. It is therefore possible to alter the internals of a mutable argument.

**Attributes and their respective methods**
Objects in Python typically have both attributes (other Python objects stored “inside” the object) and methods (functions associated with an object that can have access to the object’s internal data).

**Duck typing**
Often you may not care about the type of an object but rather only whether it has certain methods or behavior. This is sometimes called “duck typing,” after the saying “If it walks like a duck and quacks like a duck, then it’s a duck.”

**Mutable objects**
Most objects in Python, such as lists, dicts, NumPy arrays, and most user-defined types (classes), are mutable. This means they can be changed once created. 

**None type**
None is the Python null value type. If a function does not explicitly return a value, it implicitly returns None

**Conditional statement, control flow and loops are common just like other programming languages**

---End of chapter 2 notes---




