# Airbnb - Roomcheck
Roomcheck is a little statisic tool, that depicts montly prices and availabilites of rooms in a city.


## Table of contents

- [Quickstart](#quick-start)
- [What's included](#whats-included)
- [Description](#description)
- [Copyright and license](#copyright-and-license)

# Quickstart
Download Git Repo and datasets and run jupyter notebook.

- Install Pandas: `pip install pandas`
- Install Numpy: `pip install numpy`
- Install Plotlib: `pip install matplotlib` 

## What's included

In the current version, roomcheck answer following questions:
- Price development during a given timeline in a city 
- Availablilty of rooms in city
- Price depended on score rate
- Possible reasons for price increase/ decrease
- Price for best rooms

## Description

#### Price development:
Based on the given dateset, a mean and median plot is calculated and splitted by month

#### Availability:
Sum of all rooms, listed as available ans splitted by month

#### Price depended on score rate:
Similar like price development, the graphic shows a price development for rooms grouped by their their average score.
Currently it only depicts one bed rooms.

#### Price for best rooms:
Another plot, that shows the prive development for the best rooms based on the highest review number and score.


## Copyright and license
Unlicensed  product. Free to use. All libaries in this project are public licensed 
