# Data Visualization Development Guide

This folder contains the source code for making interactive plots in the weibsite [covid19-mobility.com](covid19-mobility.com). 

We use plotly to make the plots and generate offline html code, which can be directly integrated into the website.

`us_fuel_demand.py` is good to start.

If you want to know how the website is developed, you can go to the gh-pages branch of this repo. It is built on jekyll. No worries about the details. You just need to read `index.md`. Then you will know how it works.

# Visualization to be done

+ Mobility projection curve by state (four curves in total)
    - contains projected/historical Apple mobility
    - contains projected/historical Google mobility

    Then we can make a list of US states at https://covid19-mobility.com/projection/. Click on the state name will direct you to the state's projection curve.
