
# Data Scientist Nanodegree
## Introduction to data science
### Project: Boston Airbnb listings Analysis

#### Installations:
This project requires Python 3.x and the following Python libraries installed:
scikit-learn==0.21.2
pandas==0.24.2
numpy==1.16.4
matplotlib==3.1.0
seaborn==0.9.0
You will also need to have software installed to run and execute an iPython Notebook.

install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

#### Project Motivation:
As per Udacity Data Scientist Nanodegree project Term 2 project to write a Data science blogpost using CRISP-DM. I was intriguted to analyze and find business related questions about airbnb listings for Boston city. This interest stem from being a frequent user of airbnb and a curious traveler that is interested in knowning the trends in prices and what can affect.

for more information refer to the medium blogpost for this project:

#### File Descriptions:
Data: Folder containing the airbnb data required for the analysis(this folder and associated folders needed to be created as per Data instructions).

Boston_Airbnb.ipnyb: A notebook containing the analysis for the data.

#### Run:
In a terminal or command window, navigate to the top-level project directory Write_BlogPost/ (that contains this README) and run one of the following commands:

ipython notebook Boston_Airbnb.ipynb

or

jupyter Boston_Airbnb.ipynb
This will open the iPython Notebook software and project file in your browser.

#### Data:
The data used in this project was acquired from airbnb repo for Boston city using the following link.

create a data directory containing the following required downloaded files from the above repo:

listings: Summarized listings data for Boston city.
calendar: Detailed calendar data for Boston city.
reviews: Summarized reviews data for Boston city.

### Summary:
In this project, we have analyzed Boston Airbnb data listings. Gathered Boston Airbnb listings, calendar_data and reviews_data from data@insideairbnb.com and analysed and cleaned. Used descriptive statistics and regression model(Multiple Linear Regression, Randon Forest Regression) and KMeans cluster to answer the following questions:

1. Most expensive month to visit Boston Airbnb?
The most expensive month was Septemper month with $232.2 followed by October, November.
March and February months was considerd as less expensive months.
Price was spike during the month of September to November and again slightly high during the month of May.
From June to August, avilability was stabilized.

2. Most expensive neighbourhood in Boston?
Harvard Square was the most expensive neighbourhood city with $359 near Boston Airbnb followed by Financial District.

3. What are the top amenities people needs most?
Top amenities that visitors would liked was wireless interent, followed by heating, kitchen...

4. Which month do people like to visit Boston Airbnb(Based on review counts)?
in the month of August, most of the visitors would like to visit Boston Airbnb followed July, June, May.
Less crowded months would be January,February and December months.

I found that the main drive for Airbnb prices were during peak months and how many people a listing can accomode. And also amenities sush as internet, tv, ac, heating... In order to get very good reviews from the visitors, it is very important to respond to their enquires. So, amenities are important. Location also very important inorder to book Airbnb.

I also found that, Random Forest Regression is best algorithm to predict the rental price of Boston Airbnb with R2_score of 0.61

#### Licensing, Authors, Acknowledgements:
Data was acquired from insideairbnb repo
This project is part of Data scientist Nanodegree from udacity
This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. Please refer to Udacity Terms of Service for further information.
