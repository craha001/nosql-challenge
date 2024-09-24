# nosql-challenge
For this weeks module 12 challenge, we worked with MongoDB to perform NoSQL queries. A food magazine called, "Eat,Safe,Love," reached out in order for us to evaluate some ratings data
in order to help their journalists and food critics decide where to focus future articles. 

## Part 1: Database and Jupyter Notebook Set Up
For this part, please open the NoSQL_setup_starter.ipynb. Here we have imported the data provided in the resources file using our terminal and it can actually be imported
using jupyter notebook as well. Once the instance of the mongo client was created and the database information was confirmed we can move on to updating the DataBase.

## Part 2: Update the Database
In this section we are still using the NoSQL_setup_starter.ipynb. The magazine editors required some modifications to the database. First of which was adding a new halal restaurant which just opened up in 
Greenwich meaning it must be added to the database. Then they were no longer interested in any establishments in Dover, so any establishments found in Dover using the latitude and logitude of the location
were removed. 

## Part 3: Exploratory Analysis
For our analysis please open up the NoSQL_analysis_starter.ipynb file. The following are the questions that were answered:

1. Which establishments have a hygiene score equal to 20?  
   There were 41 establishments that had this hygiene score. The names can be found in the results_df dataframe.

2. Which establishments in London have a RatingValue greater than or equal to 4?  
   33 establishments in London have a RatingValue greater than or equal to 4. Names of these establishments can be found in the results_londong DataFrame.

3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?  
   Here are the top 5 establishments with a RatingValue of 5 near Penang Falvours: TIWA N TIWA African Restaurant Ltd, Fineway Cash & Carry,
   Lucky Food & Wine, Premier Express, and Everest Stores Ltd.

4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.  
   The number of establishments was 55 and below are the top ten:
	Thanet	
	Greenwich	
	Maidstone	
	Newham	
	Swale
	Chelmsford	
	Medway	
	Bexley	
	Southend-On-Sea	
	Tendring


## Contributions
I collaborated on this assignment with Brendan Golden, Nicolas Ortega, and Wei Wang. 

