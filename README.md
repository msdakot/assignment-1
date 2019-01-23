# Assignment #1

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/assignment-1/)

### Due Date: 9am on 1/30

This week's assignment will be broken into two parts:

## Part 1: Installing Python

Follow the [instructions](getting-python.md) in this repository for downloading and installing Anaconda locally and creating a new Python environment.

**Note: If you are unable to successfully install Python locally, you can also use the Binder link above to proceed with step 2.
After loading Binder, a new Jupyter notebook can be created to complete Part 2.**

However, local installation is still preferred, so please also contact me any problems encountered.

## Part 2: Finding the Philadelphia ZIP Code with the maximum ZHVI over time

Use a Jupyter notebook to find the Philadelphia ZIP code with the largest average annual ZHVI value, for each year in the data set. The Zillow data is available in this repository: [data/Zip_Zhvi_AllHomes.csv]().

The Jupyter notebook should used _pandas_ to load the data and analyze it. The following steps should be followed:

1. Load the ZHVI data for each ZIP code, selecting only Philadelphia ZIP codes.
1. Calculate the annual average ZHVI for each ZIP code in Philadelphia and each year.
1. Identify the ZIP code with the maximum value for each year.

The final result should be the year and the ZIP code with the maximum value.

## Submission

Please send your Jupyter notebook `.ipynb` showing
your calculation for Part 2 above.

Files should be submitted to nicholas.adam.hand@gmail.com by 9am on 1/30.
