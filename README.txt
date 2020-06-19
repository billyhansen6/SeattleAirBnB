
1. Installations and Requirments

This project requires that you have the following packages installed:

numpy, pandas, matplotlib, seaborn, sklearn

2. Project Motivation

The motivation of this project is to gain understand about Air BnB data in Seattle. One objective is 
to predict what the price what the price of a listing will be given the time of year and 
all of the listing attributes. Here are some other questions I wanted to answer with the data:

- At what time of year are the air bnb prices the highest? When are they the lowest?
- How do the prices vary by property type?
- What kind of host have good review scores? 
- What kind of hosts have poor review scores?


3. File Descriptions

This project requires two datasets, both of which can be found at this kaggle website:
https://www.kaggle.com/airbnb/seattle

listings.csv is a dataset containing all unique listings in Seattle from 2016.
Calendar.csv is a dataset showing the availability and price for each of the listings above throughout the year.


4. How to Interact with this project

I spent considerable time cleaning the listing dataset, as it contains 92 columns of messy and sometimes
incomplete data. I selected the columns that seemed useful, filled null data with methods that 
preserved as much data as possible, and engineered some of the features.

Next I used the dataset to answer some of the questions I posed above.

I then preparred the data for modelling by creating dummy variables.

I used Multiple Linear Regression and Random Forest Regression to predict price using 10 fold 
cross validation. The MLR model was very bad, and the Random Forest Model was much better. Ways to improve the
project include the following:

- Dimensionality reduction.
- Try different models and spend time model tuning.
- More Feature Engineering.

5. Licensing, Authors, Acknowledgments, etc.

I worked on this project myself.
