# **Columbia University Engineering, New York FinTech BootCamp** 
# **August 2022 Cohort**
## *Proptech tool application - simulate one-click service to buy properties and then rent them*

Objective - to simulate local community PropTech consulting operations. 
Scenario - as acting analyst, within PropTech firm (stakeholder/user), utilize data visualization skills, including aggregation, interactive visualizations, and geospatial analysis, to identify properties in the San Francisco market that are viable investment opportunities. 
Product/deliverable - creation of a Jupyter notebook that contains your analysis of the housing rental market data for San Francisco. The analysis will be complete with professionally styled and formatted interactive visualizations.

Part 1:

Part 2:

This product represents a simplified prototype.  It allows systematic evaluation of current asset holdings (crypto-currencies, stock Funds, and bond funds) to determine present value as well as projected future value.  In addition, it assesses current asset holdings value in relation to projected emergency needs.

Beyond the scope of the assignment, the author sought to conduct additional analysis of the data obtained and demonstrate further visualization....  Supplemental and/or extra analysis beyond the scope of the project is noted as 'supplemental' were approrpiate. 

---

## Note: the market is dynamic.  The dates chosen for this analysis are dynamic.  As such, all figures provided will differ from values returned on any specific day in which this code is operated.  That is to say, figures and values presented herein will be outdated compared to values obtained by user realtime.  All results should be viewed as accurate estimates in relation to the date they are calculated.

---
## **Methods**
### The code script analysis performed:

  )
    
#### Step I - 

![holdings_pie](Images/holdings_pie.png)

#### Step II -



![3yr_scatter](Images/3yr_scatter_hx.png)

![MC_3data_30predict](Images/3_30_MC.png)

![current_30](Images/current_val_sb_30.png)

![MC_3data_30predict](Images/3_10_MC.png)

![current_30](Images/current_val_sb_10.png)



            
   SUPPLEMENTAL and/or EXPANDED ANALYSIS was introduced by the author -
   The historical data was cleaned and analyzed in order to 
       visualize with `plot.scatter` and parameters- x='timestamp', y='close', c='volume' ,
       utilize `pct_change` function in order to calculate daily returns.
   The `corr` function was used to calculate correlations for each fund pair.
   The `heatmap` function from the Seaborn library was used to create a heatmap of correlation values visualization.
   Monte Carlo simulations were also conducted utilizing 5 years of historical closing prices
       Run Monte Carlo simulation of 500 samples and 5 years prediction for the 40/60 portfolio
       visualize- overlay line plot resulting from a simulation
       visualize- plot probability distribution of the Monte Carlo simulation
   Monte Carlo simulations were also conducted utilizing 7 years of historical closing prices
       Run Monte Carlo simulation of 500 samples and 1 year prediction for the 40/60 portfolio
       visualize- overlay line plot resulting from a simulation
       visualize- plot probability distribution of the Monte Carlo simulation
   
![all_dataframes_htmap](Images/htmaps.png)    
   
   Additional information about the heatmap method from seaborn on the [documentation page](https://seaborn.pydata.org/generated/seaborn.heatmap.html#seaborn.heatmap).



---
## **Technologies**
---
### **Dependencies**

This project leverages Jupyter Lab v3.4.4 and python v3.7 with the following packages:

* [os](https://docs.python.org/3/library/os.html) - provides a portable way of using operating system dependent functionality.

* [getenv](https://docs.python.org/3/library/os.html?highlight=os%20getenv#os.getenv) - From 'os', return the value of the environment variable key if it exists, or default if it doesn’t.

* [requests](https://requests.readthedocs.io/en/latest/) - an elegant and simple HTTP library for Python, allows you to send HTTP/1.1 requests extremely easily.

* [json](https://docs.python.org/3/library/json.html?highlight=json) - JavaScript Object Notation, is a lightweight data interchange format inspired by JavaScript object literal syntax 

* [pandas](https://pandas.pydata.org/docs/) - Software library written for the python programming language for data manipulation and analysis.

* [Timestamp](https://pandas.pydata.org/docs/reference/api/pandas.Timestamp.html) - From 'pandas', equivalent of python’s Datetime, used for the entries that make up a DatetimeIndex, and other timeseries oriented data structures in pandas.

* [concat](https://pandas.pydata.org/docs/reference/api/pandas.concat.html) - From 'pandas', concatenate pandas objects along a particular axis, allows optional set logic along the other axes.

* [Dataframe](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) - From 'pandas', data structure also contains labeled axes (rows and columns). Arithmetic operations align on both row and column labels. Can be thought of as a dict-like container for Series objects. The primary pandas data structure.

* [numpy](https://numpy.org/doc/stable/) - Software library, NumPy is the fundamental package for scientific computing in Python, provides vast functionality.

* [timedelta](https://numpy.org/doc/stable/reference/arrays.datetime.html) - From 'NumPy', from datetime, allows the subtraction of two datetime values, an operation which produces a number with a time unit.

* [dot_env](https://pypi.org/project/python-dotenv/) - Python-dotenv reads key-value pairs from a .env file and can set them as environment variables.

* [alpaca-trade-api](https://pypi.org/project/alpaca-trade-api/0.29/) - a python library for the Alpaca trade API. It allows rapid trading algo development easily, with support for the both REST and streaming interfaces.

* [MCForecastTools]- a python library for the Monte Carlo simulation framework, exists as a file named MCForecastTools.py, in the same folder as the challenge notebook. This file contains all the logic, in the form of Python code, required to run the Monte Carlo simulation on portfolio price data.

For additional and / or supplemental processing and visulaization this project also makes use of the following packages:

* [matplotlib.pyplot](https://matplotlib.org/stable/tutorials/introductory/pyplot.html) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python; matplotlib.pyplot is a collection of functions that make matplotlib work like MATLAB.

* [seaborn](https://seaborn.pydata.org/tutorial/introduction) - Software library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures.



### **Hardware used for development**

MacBook Pro (16-inch, 2021)

    Chip Appple M1 Max
    macOS Monterey version 12.5.1

### **Development Software**

Homebrew 3.5.10

    Homebrew/homebrew-core (git revision 0b6b6d9004e; last commit 2022-08-30)
    Homebrew/homebrew-cask (git revision 63ae652861; last commit 2022-08-30)

anaconda Command line client 1.10.0

    conda 4.13.0
    Python 3.7.13

pip 22.1.2 from /opt/anaconda3/envs/dev/lib/python3.7/site-packages/pip (python 3.7)


git version 2.37.2

---
## *Installation of application (i.e. github clone)*

 In the terminal, navigate to directory where you want to install this application from the repository and enter the following command

```python
git clone git@github.com:Billie-LS/Emergency_and_Retirement_Financial_Planner.git
```

---
## **Usage**

From terminal, the installed application is run through jupyter lab web-based interactive development environment (IDE) interface by typing at prompt:

```python
  > jupyter lab
```

---
## **Project requirements**
### see starter code

---
## **Version control**

Version control can be reviewed at:

```python
https://github.com/Billie-LS/Module-6-Proptech
```

[repository](https://github.com/Billie-LS/Module-6-Proptech)


---
## **Contributors**

### **Author**

Loki 'billie' Skylizard
    [LinkedIn](https://www.linkedin.com/in/l-s-6a0316244)
    [@GitHub](https://github.com/Billie-LS)


### **BootCamp lead instructor**

Vinicio De Sola
    [LinkedIn](https://www.linkedin.com/in/vinicio-desola-jr86/)
    [@GitHub](https://github.com/penpen86)


### **BootCamp teaching assistants**

Corey Recai
    [LinkedIn](https://www.linkedin.com/in/corey-recai/)

Santiago Pedemonte
    [LinkedIn](https://www.linkedin.com/in/s-pedemonte/)
    [@GitHub](https://github.com/Santiago-Pedemonte)


### **askBCS assistants**

A
    [LinkedIn](https://www.linkedin.com/)

B
    [LinkedIn](https://www.linkedin.com/)


### **GitHub inspiration - dynamic and/or current date formatting ideas**


C 
    [@GitHub](https://github.com/)


### **Additional references**


[SparkByExamples.com](https://sparkbyexamples.com/pandas/pandas-drop-a-level-from-a-multi-level-column-index/)

[W3Schools](https://www.w3schools.com/python/python_dictionaries.asp)

[Geeks for Geeks](https://www.geeksforgeeks.org/get-yesterdays-date-using-python/)

[pandas.to_datetime documentation](https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html)

[Numpy Datetimes and Timedeltas](https://numpy.org/doc/stable/reference/arrays.datetime.html)

---
## **License**

MIT License

Copyright (c) [2022] [Loki 'billie' Skylizard]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


