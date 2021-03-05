# Touristic trends and  insights of Airbnb in Seville, Spain

In this project an analysis of different Airbnb data available will be carried out to get an overview of the touristic 
trends in the city of Seville

## Table of Contents

1. <a href = "#Requirements" > Requirements </a>
2. <a href = "#Jupyter-Notebook"> Jupyter Notebook </a>
3. <a href = "#Data" > Data </a>
4. <a href = "#Summary-of-Results" > Summary of Results </a>
5. <a href = "#Article-of-the-Project" > Article of the Project </a>
6. <a href = "#Acknowledgements" > Acknowledgements </a>

## Requirements
The following libraries are needed to run the notebook:
+ numpy
+ pandas
+ itertools  
+ matplotlib
+ seaborn
+ datetime
+ wordcloud
+ PIL
+ string
+ nltk
  + word_tokenize
  + stopwords
  + RegexpTokenizer  
+ os

## Jupyter Notebook
Here will be done the analysis of the data to answer the following questions:

1. Is Seville a popular city the whole year? How price and availability change?
2. How has changed the market through the years? Did the pandemic has an impact?
3. Is there a relationship between neighbourhood and price?
4. Which words are the most used by tourists when doing a review?

## Data
This is the Airbnb data that will be used for the analysis:

1. [(```listings.csv```)](listings.csv): Detailed data of the accomodations available in the city
2. [(```reviews.csv```)](reviews.csv): Reviews of guests
3. [(```calendar.csv```)](calendar.csv): Data with availability and prices
4. [(```neighbourhoods.csv```)](neighbourhoods.csv): List with the neighbourhoods of Sevilla

## Summary of Results
The answers to the questions on the notebook were:
1. The popularity of Sevilla is approximately constant along the year with 4 peaks in April, May,
   September and October. The price is constant and there is more availability during the first
   semester of the year
   ![Popularity_of_Sevilla](https://github.com/pedflotor/Analysis-Airbnb-Sevilla/blob/master/Images/1..png)

2. Up to 2019 the growth was constant and continuous. However in 2020, when the pandemic started, the number of 
   stays in Seville sharply decreased.
   ![Growth](https://github.com/pedflotor/Analysis-Airbnb-Sevilla/blob/master/Images/2..png)

3. The overall average price and the average price of *Casco Antiguo* neighbourhood are very closed as expected since 
   the amount of apartments in this zone represents around the 70% of all the offer available in the city
   ![Price_average](https://github.com/pedflotor/Analysis-Airbnb-Sevilla/blob/master/Images/3..png)

4. In general ‘*great stay*’, ‘*great host*’ or ‘*highly recommend*’ and for *Casco Antiguo* neighbourhood the most 
   common words are ‘*walking distance*’, ‘*bien situé*’ or ‘*bien ubicado*’
   ![Popular_words](https://github.com/pedflotor/Analysis-Airbnb-Sevilla/blob/master/Images/4..png)
   

## Article of the Project
+ https://petanth91.medium.com/sevilla-the-city-with-a-special-colour-697e4320d377

## Acknowledgements
+ https://en.wikipedia.org/wiki/Seville
+ https://www.historiasdemiciudad.com/los-5-monumentos-de-sevilla-mas-importantes/9035
+ http://insideairbnb.com/get-the-data.html
+ https://www.kaggle.com/aashirwad01/airbnb-analysis
