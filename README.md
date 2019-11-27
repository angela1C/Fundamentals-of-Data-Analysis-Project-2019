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


## Overview of the notebook.
The notebook is broken into 3 parts corresponding to the project instructions. 

### Part 1
I first looked at some of the background of the Tips dataset and loaded the dataset into python using the pandas library. The dataset is a small prepared dataset and therefore no cleaning as such was required. Exploratory data analysis (EDA) was the next step. Pandas was used to get a good overview of the structure of the dataset and to describe the data using statistics. Seaborn was used to create visualisations.
There are both categorical and quantitative variables in the dataset which determimed the kind of statistics and visualisations that are appropriate to apply. In this section I focused mostly on univariate exploratory data analysis using the variables in the dataset as later sections look more at multivariate EDA of the dataset. 

I did include a bit of detail about the python packages used, the statistics that were applied to the dataset and the type of plots used.
This provides a reference point for other projects in the future.

### Part 2

In this section I looked at the relationship between the total bill and the tip amount using regression and some statistics. Seaborn plots were the main focus and while these do not give the statistical values they do visualise the regression relationship between variables and the effects of other variables on the relationship between total bill and tip amount. 
I did include some detail about regression.



References

Python Software Foundation. Welcome to python.org. https://www.python.org/.
GitHub Guides. Mastering markdown. https://guides.github.com/features/mastering-markdown/
Project Jupyter. Project jupyter. https://jupyter.org/.
Michael Waskom. seaborn. https://seaborn.pydata.org/.
Michael Waskom. Tips data set. https://github.com/mwaskom/seaborn-data/blob/master/tips.csv.