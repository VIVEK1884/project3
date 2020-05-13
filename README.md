# project3
Table of contents
[Introduction: Business Problem]
Data
Methodology
Analysis
Results and Discussion
Conclusion ]

Introduction: Business Problem
The aim of this project is to find a safe and secure location for opening of commercial establishments in Vancouver, Canada. Specifically, this report will be targeted to stakeholders interested in opening any business place like Grocery Store in Vancouver City, Canada.

The first task would be to choose the safest borough by analysing crime data for opening a grocery store and short listing a neighbourhood, where grocery stores are not amongst the most commom venues, and yet as close to the city as possible.

We will make use of our data science tools to analyse data and focus on the safest borough and explore its neighborhoods and the 10 most common venues in each neighborhood so that the best neighborhood where grocery store is not amongst the most common venue can be selected.

Data
Based on definition of our problem, factors that will influence our decission are:

finding the safest borough based on crime statistics
finding the most common venues
choosing the right neighbourhood within the borough
We will be using the geographical coordinates of Vancouver to plot neighbourhoods in a borough that is safe and in the city's vicinity, and finally cluster our neighborhoods and present our findings .

Following data sources will be needed to extract/generate the required information:
Part 1: Using a real world data set from Kaggle containing the Vancouver Crimes from 2003 to 2019: A dataset consisting of the crime statistics of each Neighbourhoof in Vancouver along with type of crime, recorded year, month and hour.

Part 2: Gathering additional information of the list of officially categorized boroughs in Vancouver from Wikipedia.: Borough information will be used to map the existing data where each neighbourhood can be assigned with the right borough.

Part 3: Creating a new consolidated dataset of the Neighborhoods, along with their boroughs, crime data and the respective Neighbourhood's co-ordinates.: This data will be fetched using OpenCage Geocoder to find the safest borough and explore the neighbourhood by plotting it on maps using Folium and perform exploratory data analysis.

Part 4: Creating a new consolidated dataset of the Neighborhoods, boroughs, and the most common venues and the respective Neighbourhood along with co-ordinates.: This data will be fetched using Four Square API to explore the neighbourhood venues and to apply machine learning algorithm to cluster the neighbourhoods and present the findings by plotting it on maps using Folium.

Part 1: Using a real world data set from Kaggle containing the Vancouver Crimes from 2003 to 2019 Vancouver Crime Report Properties of the Crime Report

TYPE - Crime type YEAR - Recorded year MONTH - Recorded month DAY - Recorded day HOUR - Recorded hour MINUTE - Recorded minute HUNDRED_BLOCK - Recorded block NEIGHBOURHOOD - Recorded neighborhood X - GPS longtitude Y - GPS latitude Data set URL: https://www.kaggle.com/agilesifaka/vancouver-crime-report/version/2

Reading from the Dataset  
Due to sheer amount of data(~ 600,000 rows), it was not possible to process all of them and instead for this project we will be considering the recent crime report of the 2018.  

Methodology  
Categorized the methodologysection into two parts:     

-Exploratory Data Analysis_: Visualise the crime repots in different Vancouver boroughs to idenity the safest borough and normalise the neighborhoods of that borough. We will Use the resulting data and find 10 most common venues in each neighborhood  
Modelling: To help stakeholders choose the right neighborhood within a borough we will be clustering similar neighborhoods using K - means clustering which is a form of unsupervised machine learning algorithm that clusters data based on predefined cluster size. We will use K-Means clustering to address this problem so as to group data based on existing venues which will help in the decision making process.  
Expolring the data by Visualising  
Modelling  
Results and Discussion¶  
Conclusion  
