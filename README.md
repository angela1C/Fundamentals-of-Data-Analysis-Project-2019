# Fundamentals_Data_Analysis_Project-2019
This is the repository for my project for the Fundamentals of Data Analysis at GMIT 2019.

This assessment concerns the well-known tips dataset and the Python packages seaborn and jupyter.
The project is broken into three parts, as follows.

1. Description: A git repository containing a jupyter notebook that uses descriptive statistics and plots to describe the tips dataset. (30%). Provide a good summary of the tips dataset.

2. Regression: To the above jupyter notebook add a section that discusses and analyses whether there is a relationship between the total bill and tip amount (30%). A good analysis of the relationship between total bill and tip, with good explanations of the analysis.
 
3. Analyse: Again using the same notebook, analyse the relationship between the variables within the dataset. (40%). Reasonable work investigating the relationship between the variables, with interesting relationships highlighted and discussed.



## How to download this repository

Go to the URL for the repository on GitHub at https://github.com/angela1C/Fundamentals_Data_Analysis_Project-2019
Click the green Clone or download button

## How to run the code

**Python 3** was used to develop this project and is needed to run the code in the notebook. Python 3 can be downloaded from the official Python website at https://www.python.org/downloads/. It can also be downloaded using the **Anaconda Python distribution** at https://www.anaconda.com/distribution/. 

The Jupyter Notebook [tips-project.ipynb](https://github.com/angela1C/Fundamentals_Data_Analysis_Project-2019/blob/master/tips-project.ipynb) itself can be viewed directly in this GitHub repository in a browser without Python 3 being installed. On occasion the Jupyter Notebook may not render correctly in which case the url <https://github.com/angela1C/Fundamentals_Data_Analysis_Project-2019> can be copied and pasted in to the [Jupyter nbviewer ](https://nbviewer.jupyter.org ) at
https://nbviewer.jupyter.org  where you enter the location of a Jupyter Notebook and click `Go` to have it rendered there.

The notebook containing all the work is called **tips-project.ipynb**. If the repository is downloaded it can be run locally by navigating to the folder and entering the command `jupyter lab` or `jupyter notebook` on the command line. This will open Jupyter in the browser. The notebook can be opened then within the Jupyter session.
Once opened you can can select `Restart Kernel and Run All` from the Run or Kernel menu.
You can also run the selected cells and advance through the notebook using the run icon. The code should be run from top to bottom.
The main python libraries used `pandas`, `seaborn`, `matplotlib.pyplot` and `numpy` are loaded at the beginning of the notebook. These are part of the anaconda distribution of python. Any additional libraries used are loaded within the relevant section of the notebook but are not central to the project. 

## Overview of the notebook.
The notebook is broken into 3 parts corresponding to the project instructions. 

### Part 1
Part 1 looks at some of the background of the Tips dataset and loads the dataset into python using the pandas library. The dataset is a small prepared dataset and therefore no cleaning of the data is required. Exploratory data analysis (EDA) is performed using the python Pandas library to get an overview of the structure of the dataset and to describe the data using statistics. The Seaborn library is used to create visualisations.

There are both categorical and quantitative variables in the dataset which determined the kind of statistics and visualisations that are appropriate to apply. In this section I focused mostly on univariate exploratory data analysis using the variables in the dataset as later sections look more closely at multivariate EDA of the dataset. 

I did include a bit of detail about the python packages used, the statistics that were applied to the dataset and the type of plots used. This will provides a reference point for other projects in the future.

### Part 2

In this section I looked at the relationship between the total bill and the tip amount using regression. Seaborn plots were the main focus and while these do not give the statistical values they do visualise the regression relationship between variables and the effects of other variables on the relationship between total bill and tip amount. Some statistics were produced using the python NumPy package.
Some detail about regression is included and will provide a reference point for future projects.

### Part 3 
In this section I focused on the relationships between the sex and smoker variables and also looked at the party size variable. Many of the relationships between the variables in the dataset were explored as part of part 2. 

### References used are located at the end of the notebook.

