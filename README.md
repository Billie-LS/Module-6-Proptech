# **Columbia University Engineering, New York FinTech BootCamp** 
# **August 2022 Cohort**
## *Proptech tool application - simulate one-click service to buy properties and then rent them*

Objective - to simulate local community PropTech consulting operations. 
Scenario - as acting analyst, within PropTech Firm (stakeholder/user), utilize data visualization skills, including aggregation, interactive visualizations, and geospatial analysis, to identify properties in the San Francisco market that are viable investment opportunities. 
Product/deliverable - creation of a Jupyter notebook that contains your analysis of the housing rental market data for San Francisco. The analysis will be complete with professionally styled and formatted interactive visualizations.

Part 1:  import, clean, and analyze data

Part 2:  develop visualization tools to analyze the data

Beyond the scope of the assignment, the author sought to conduct additional refinement and/or analysis of the data obtained and demonstrate further visualization....  Supplemental and/or extra analysis beyond the scope of the project is noted as 'supplemental' were approrpiate. 

---


## **Methods**
### The code script analysis performed:
    
#### Step I - Create a visual aggregation explore the housing units by year (2010 to 2016)

![viz1](Images/viz1.png)

#### Step I - Supplementals

![viz2](Images/viz2.png)


#### Step II - Create an interactive line plot that visualizes both Sale Price Sqr Foot and Gross Rent by Neighborhood

![viz3](Images/viz3.png)

### Step III - Create an interactive GeoViews points plot for All Neighborhoods

![viz4](Images/viz4.png)

---
## **Technologies**
---
### **Dependencies**

This project leverages Jupyter Lab v3.4.4 and python v3.7 with the following packages:

* [pandas](https://pandas.pydata.org/docs/) - Software library written for the python programming language for data manipulation and analysis.

* [read_csv](https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html) - From 'pandas', reads a comma-separated values (csv) file into DataFrame.

* [concat](https://pandas.pydata.org/docs/reference/api/pandas.concat.html) - From 'pandas', concatenate pandas objects along a particular axis, allows optional set logic along the other axes.

* [numpy](https://numpy.org/doc/stable/) - Software library, NumPy is the fundamental package for scientific computing in Python, provides vast functionality.

* [Path](https://docs.python.org/3/library/pathlib.html) - From pathlib - Object-oriented filesystem paths, Path instantiates a concrete path for the platform the code is running on.

* [hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html) - provides a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data into numerous formats listed within linked documentation.


### **Hardware used for development**

MacBook Pro (16-inch, 2021)

    Chip Appple M1 Max
    macOS Monterey version 12.6

### **Development Software**

Homebrew 3.5.10

    Homebrew/homebrew-core (git revision 0b6b6d9004e; last commit 2022-08-30)
    Homebrew/homebrew-cask (git revision 63ae652861; last commit 2022-08-30)

anaconda Command line client 1.10.0

    conda 4.13.0
    Python 3.9

pip 22.1.2 from /opt/anaconda3/envs/dev/lib/python3.7/site-packages/pip (python 3.7)


git version 2.37.2

---
## *Installation of application (i.e. github clone)*

 In the terminal, navigate to directory where you want to install this application from the repository and enter the following command

```python
git clone git@github.com:Billie-LS/Proptech_analysis_and_visualization.git
```

---
## **Usage**

From terminal, the installed application is run through jupyter lab web-based interactive development environment (IDE) interface by typing at prompt:

```python
  > jupyter lab
```

The file you will run is:

```python
  san_francisco_housing.ipynb
```

---
## **Project requirements**
### see starter code

---
## **Version control**

Version control can be reviewed at:

[repository](https://github.com/Billie-LS/Proptech_analysis_and_visualization)


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

Santiago Pedemonte
    [LinkedIn](https://www.linkedin.com/in/s-pedemonte/)
    [@GitHub](https://github.com/Santiago-Pedemonte)


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


