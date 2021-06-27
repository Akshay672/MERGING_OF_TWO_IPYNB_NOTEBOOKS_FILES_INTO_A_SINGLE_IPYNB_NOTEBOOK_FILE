# MERGING OF TWO OR MORE .IPYNB NOTEBOOKS FILES INTO A SINGLE .IPYNB NOTEBOOK FILE

## History

In 2011, IPython introduced a new tool named the Notebook. Inspired by scientific programs like Mathematica or Sage, the Notebook offers a modern and powerful web interface to Python.

In 2015, the IPython developers made a major code reorganization of their ever-growing project. The Notebook is now called the Jupyter Notebook. 
IPython is now the name of the Python backend (aka kernel).

Jupyter notebooks were formerly known as IPython notebooks, which is where the "ipynb" extension got its name. 

IPYNB file type is primarily associated with Jupyter Notebook by Project Jupyter. 

## Jupyter Notebook

A browser-based application that allows user to create and share documents that contain live code, equations, visualizations and narrative text.

These documents are internally JSON files and are saved with the .ipynb extension. 

Notebook file can also be exported to a .pdf or .html that can then be shared with anyone.  

### Some Key Advantages:

 Exploratory Data Analysis: Jupyter allows users to view the results of the code in-line without the dependency of other parts of the code. 
 
 Data Visualization: As a component, the shared notebook Jupyter supports visualizations and includes rendering some of the data sets like graphics and charts,
 
 Live Interactions with Code: Jupyter Notebook uses “ipywidgets” packages, which provide standard user interfaces for exploring code and data interactivity
 
 Documenting code samples: Jupyter makes it easy for users to explain their codes line-by-line with feedback attached all along the way.

## Explanation

Project involves merging of Two or more .ipynb notebooks files into a single .ipynb notebook file were data of both the notebooks will be showcased in a single notebook.
For explanatory purposes we have taken the example of Mr. X who has has two Jupyter notebooks named Monday.ipynb file and Tuesday.ipynb file. 
Files contains total count of COVID +ve patients found all over Asia on Monday and Tuesday.

Mr. X’s boss “demands” see the data of both the files in one file called midweek.ipynb 

Mr.X reaction:

![anigif_sub-buzz-9506-1510940418-13](https://user-images.githubusercontent.com/85668824/123548194-662e5e80-d781-11eb-9251-c64dc2162111.gif)

## Methods

1. Nbmerge Tool in the Nbdime package

2. Using json Merge

3. Merge_notebook Methods


### Please refer the Merging_Methods.ipynb file for all the three methods and the results of these are saved in mideweek1, mideweek2 and mideweek3 respectively.

### Also attached the Presentaion for more better undersatnding.
