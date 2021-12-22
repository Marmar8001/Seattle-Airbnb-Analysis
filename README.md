# Seattle-Airbnb-Analysis

**Project Motivation :**

This project was done for completing Udacity nanodegree program to understand effective parameters for predicting AirBnB prices in Seattle in 2016.

**Files in Repository:**

There are two csv files and one python file in the repository. The python file shows the details of data cleaning, exploratory analysis, modeling and model evaluation.
The calenadar.csv file shows the listing ids as well as month and price of them.
The listing.csv file shows the listings and their features like numbers of bedrooms, bathrooms, reviews etc.


**Table of Contents in python file:**

* Business Understanding
* Importing Necessary Packages
* Reading the Datasets
* Data Cleaning & Visualization
* Data Modeling
* Evaluation & Correlation

**Summary of Results:**

The main results from the study were :

1)how the price changes during different months of the year?
The maximum average price per day was seen in June, July and August and minimum average price was seen on January and November.

2)What kinds of rooms were more observed in the postings?
Most of the posting were entire home/apartments.

3)How was the distribution of listing prices?
The listing prices in most of the cases were below 200 dollars. Most of the cases were around 100 dollars per night. There were very few cases around $1000 per night.The distribution was close to normal distribution and alittle skewed to the right.

4)How the number of accomodates correlates with average price?
The price was increasing with number of accomodates untill 11 accomodates. After 11 accomodates, the price was not increasing with number of accomodates.

5)Which parameters were correlated more with eachother?
Based on the heatmap, price was correlating with number of accomodates, bedrooms, bathrooms and beds. Reveiw_scores parameters were correlating with host being superhost or not.

6)Which parameters affect the price more based on the modeling result?
The final feature importance on random forest model showed that five most important features were number of bedrooms, bathrooms, reveiw_scores_rating and the length of the time the person was host as well as number of accomodates.

**acknowledgments:**

Thanks to Kaggle for having interesting dataset to analyze!
