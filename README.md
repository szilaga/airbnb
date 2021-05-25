# Airbnb - Roomcheck
Roomcheck is a little statisic tool, that depicts montly prices and availabilites of rooms in a city.


## Table of contents

- [Quickstart](#quick-start)
- [What's included](#whats-included)
- [Description](#description)
- [Copyright and license](#copyright-and-license)

# Quickstart
Download Git Repo including the datasets. Run jupyter notebook.

- Install Pandas: `pip install pandas`
- Install Numpy: `pip install numpy`
- Install Plotlib: `pip install matplotlib` 
- Install Seaborn: `pip install seaborn`

## What's included

In the current version, roomcheck answer following questions:
- Price development during a given timeline in a city 
- Availablilty of rooms in city
- Price depended on score rate
- Possible reasons for price increase/ decrease
- Price for best rooms

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

## Copyright and license
Unlicensed  product. Free to use. All libaries in this project are public licensed 
