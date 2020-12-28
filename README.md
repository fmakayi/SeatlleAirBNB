
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Methods](#methods)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.*.
* numpy
* pandas
* matplotlib.pyplot
* sklearn.linear_model
* seaborn
* %matplotlib inline

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using Seattle AirBNB data from 2016 to better understand:

1. Which type of properties are rarely booked?
2. What time of the year is best for listing your property on AirBNB?
3. Which factors determine the price a host can charge ?
4. How best to predict review scores





## File Descriptions <a name="methods"></a>

There is one notebooks available here to showcase work related to the above questions. The notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

## Methods <a name="files"></a>
There was a lot of missing data in the data provided
Columns with more than 75% of the data missing were removed or dropped from the
data frame
For columns with less than 75% of the data missing, the missing values were imputed
with the mean vale of the column.
For categorical variables I created dummy variables using 0, 1 encodings

I used linear regression with sklearn to fit a model to the data

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://fmakayi.github.io/).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBNB for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/seattle/data).
Extra information from Airbnb can be found [here](https://www.airbnb.co.za/resources/hosting-homes/a/the-best-amenities-to-offer-right-now-203)
