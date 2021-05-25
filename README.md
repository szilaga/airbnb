# Airbnb - Roomcheck
The Airbnb - Roomcheck is a collection of statistical methods and plots, written in python to answer specific questions related to
an Airbnb datasets, which can be downloaded <a href="https://www.kaggle.com/airbnb/seattle">@kaggle</a>.


## Table of contents

- [Quickstart](#quick-start)
- [Idea](#idea)
- [What's included](#whats-included)
- [Description](#description)
- [Copyright and license](#copyright-and-license)



# Quickstart
Download the entire Git Repo including the datasets. Execute the notebook <b>"airbnb_analysis.ipynb"</b> in your jupyter.<br/>
Before execution: If you do not already have installed the listed libraies below, please install them in a previous step.

- Install <a href="https://pypi.org/project/pandas/">Pandas:</a> `pip install pandas`
- Install <a href="https://pypi.org/project/numpy/">Numpy:</a> `pip install numpy`
- Install <a href="https://pypi.org/project/matplotlib"/>Plotlib:</a> `pip install matplotlib` 
- Install <a href="https://pypi.org/project/seaborn">Seaborn:</a> `pip install seaborn`


## Idea
This project can be seen as a collection of methods, written in python to analyse a relation dataset.
It will be extended with additional methods to get some inspirations, in what way data kind be examined.


## What's included
```text
airbnb/
├── data/
│   ├── calendar.csv
│   ├── listings.csv
│   ├── reviews.csv
├── airbnb_analysis.ipynb
├── README.MD
```



## Description

#### Function getPriceDevelopment(method):
Based on the given dateset, a mean and median plot is calculated and splitted by month
Input: Methode "median" or "mean"

#### Function getPlotScoreBed(beds=1,score_from = 0, score_to = 10):
Creates a bar plot, that provides the average price development over the month, separated by the review score rate.
Input: Number of beds; score_range_from; score_range_to;

#### Function bestAccomondations(beds=1,top=3):
Creates a bar plot, that provides the average price development over the month of the top three accomodations ranked by review score and number of reviews.

#### Availability:
Sum of all rooms, listed as available ans splitted by month

#### Strongest influence in price development:
Seaborn heatmap that provides a correlation matrix to investigate, which columns have a strong dependencies in respect of the given column set.


## Contributing
If you like this project, please feel free to code. 

## Copyright and license
The code itself is free licensed. All libaries, used in this project are still under the given licence model.
For more information please check the licence @pypi.org for every library listed above.


