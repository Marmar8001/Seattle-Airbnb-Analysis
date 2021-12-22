# Seattle-Airbnb-Analysis

**Project Motivation :**
This project was done for completing Udacity nanodegree program to understand effective parameters for predicting AirBnB prices in Seattle in 2016.

This project investigates the effect of different parameters on price of airbnb homes. The data was taken from Kaggle and belongs to the year of 2016. This project will follow CRISP-DM methdology which consists of these four steps:

1) Business understanding
2) Data understanding and preparing
3) Modeling
4) Evaluation & Conclusion


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
