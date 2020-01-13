# DataWranglingWorkshop

Notebooks and sample data for a workshop session on data wrangling

There are two exercises here, each with a template Jupyter notebook, and a "solution" notebook that contains (one possible) approach to performing the task.
In both cases, it is recommended that you try your own approach before looking at the solution, making use of it if you get stuck, and/or comparing notes at the end.

## Exercise 1: IMDB

Using a csv file containing Internet Movie Database data (originally used in a Kaggle challenge), determine whether Action movies or Romance movies are better.

This is a fairly straightforward task on a mostly-clean input dataset, the only challenge coming from the slightly non-standard format of the csv file.

## Exercise 2: Camden broadband.

Given input data on broadband speeds in different regions of Camden, and a csv file containing Internet User Classification data for geographic regions throughout the country, look at what type of user has the tightest requirements on minimum broadband speed.

This exercise makes extensive use of the *geopandas* package to produce choropleth maps from shape files.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nbarlowATI/DataWranglingWorkshop/master)

### Credits

 * The IMDB exercise is inspired by a blog post from the author of *clevercsv*, Gerrit van den Burg:
https://towardsdatascience.com/handling-messy-csv-files-2ef829aa441d

 * The Camden Broadband data is taken from, and the exercise based on, a session at a Data Profiling workshop in Dec 2019 by James Cheshire (UCL).