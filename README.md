# ALX-T-Project-1-TMDb-Movie-Data
This dataset contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.(Cleaned from original data from Kaggle)
In this project I set out to explore a dataset which is made up of information on about 10,000 movies produced between 1960 to 2016.
I looked at the various attributes and shape of our data set and embarked on data cleaning afterwards, dropping unnecessary columns that were not needed in answering our analysis questions. The dataset contained 10866 rows and 21 columns.
In cleaning our data and getting it ready for explorations:
•	The columns 'homepage', 'tagline', 'keywords', 'overview', 'vote_average' columns are not useful for this analysis, hence were dropped from the dataset.
•	The adjusted budget and adjusted revenue data were converted to integer data type (currently float).
•	We augment our data by calculating the profit (adjusted for inflation) using the revenue_adj and budget_adj columns and adding an Adjusted profit "profit_adj" column to our dataset.
•	We dropped null (NaN) values from 'director' and 'genre' columns
•	We were left with 10800 rows and 14 columns

Questions for Analysis
In this analysis I will attempt to explore the different attributes of our data and answer the following questions:
1.	Which movie genre is the most popular over the years?
2.	Which movie has the highest revenue?
3.	Which year was the most number of movies released?
4.	Which movie made the most profit?

Summary
Based on our analysis we discovered the following:
1.	Drama is the most popular movie genre across the years, followed by Comedy, Thriller and Action movies.
2.	The movie with the highest revenue(adjusted for inflation) is Avatar closely followed by Titanic
3.	The highest number of movies were released in 2014
4.	The movie with the highest profit(adjusted for inflation) is Avatar
Limitations of your exploration
A major limitation to our analysis and data exploration was the presence of missing data, and deficiencies in data measurements and a rather too broad formualtion of research questions. Further study and analysis based on a narrower and more in-depth analysis questions is recommended.
