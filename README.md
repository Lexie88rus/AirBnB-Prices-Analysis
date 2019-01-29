# AirBnB Prices Analysis
Analysis of Seattle AirBnB reservation prices

## Analysis Overview
Finding an accomodation is the most typical problem to be solved, when travelling to other city or country. And one of the most important things in choosing an accomodation is the reservation price. What are the main factors, which affect the reservation prices? Does time of the year influence prices and what are the busiest times of the year to visit particular city? How can we save money on the reservation?
Fortunately, we can try to answer these questions by analysing publicly accessible __[AirBnB](https://www.airbnb.com)__ data, available on __[Inside AirBnB](http://insideairbnb.com/get-the-data.html)__ and on __[Kaggle](https://www.kaggle.com/airbnb/seattle)__.

## Key Outcomes
The main takeaways of the the analysis using Seattle dataset include:
* Basic characteristics of the place (number of bedrooms, bathrooms, beds and accomodates) affect the reservation price.
* The reservation price varies depending on the time of the year. For example, the busiest time to visit Seattle is summer.
* The host qualities and the number of reviews and review scores might also affect the reservation price. That is why if you want to save money, you may, for example, look for places which have fewer reviews. This will help to find the places with same characteristics (bathrooms, bedrooms, location etc.), but lower reservation price.

## Repository Contents
Repository contains following files:
* *AirBnB Reservation Prices Analysis.ipynb* - Jupyter Notebook (Python 3), contains all source code and steps of the analysis.
* *seattle* - folder contains media files used in *AirBnB Reservation Prices Analysis.ipynb*.

## References
The following resources were used for the analysis:
* __[AirBnB Seattle data used for analysis on Kaggle](https://www.kaggle.com/airbnb/seattle)__
* __[Description of AirBnB's price suggestion algorithm](https://www.vrmintel.com/inside-airbnbs-algorithm/)__

## External Libraries
In addition to standard Python libraries, the following machine learning packages are used:
* __[Scikit-learn](https://scikit-learn.org/stable/)__
* __[XGBoost](https://xgboost.readthedocs.io/en/latest/)__ 
