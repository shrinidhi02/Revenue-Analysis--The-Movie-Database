# Revenue-Analysis--The-Movie-Database
REVENUE ANALYSIS: THE MOVIE DATABASE

**Introduction:**

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. It has 10,866 rows and 21 columns. The source of this data set is Kaggle.

**Explanation of the columns:**

- id: unique id for each movie 
- imdb_id: unique id given by imdb for each movie 
- popularity: Popularity of the movie 
- budget: Movie budget in dollars 
- revenue: Movie revenue in dollars 
- original_title: Movie title 
- cast: Movie cast 
- homepage: website of the movie 
- director: Director/s of the movie 
- tagline: Tagline 
- keywords: Keyowords of the movie 
- overview: Movie overview 
- runtime: Runtime of the movie 
- genres: Movie genre 
- production_companies: Production company 
- release_date: Release_date of the movie 
- vote_count: Vote counts 
- vote_average: Average vote counts 
- release_year: Release year of the movie 
- budget_adj: Inflation adjusted budget of the movie 
- revenue_adj: Inflation adjusted revenue of the movie 
- budget_adj_mil: Inflation adjusted budget of the movie (in millions) (added later for analysis) 
- rev_adj_mil: Inflation adjusted revenue of the movie (in millions) (added later for analysis)

**Research questions:**
- What features are associated with higher revenue?
- How does the revenue trend look like over years?
- How are inflation adjusted budget and revenue are related? Does higher budget mean higher revenue?
- Does higher vote lead to higher revenue?
- How does runtime affect the revenue?

**Limitations:**

Almost 50% of budgeted values and 60% of revenues are missing. These values are replaced by mean for the purpose of the analysis. Hence, analysis might change if those values are available
The revenues of recent releases might increase over the years by selling the copyrights of it to the online streaming platforms

**Data Extraction:**

Kaggle

**Data Cleaning/Feature Engineering:**

Removed nulls
Updating Data Types

**Exploratory Data Analysis:**

Reviewed the dataset
Flitered records and null values review
Data Visualization for final findings
Created barcharts, histograms and scatter plots to answer various questions

**Code and Dataset Details:**

- Python Version: 3.6.3

- Packages: pandas, numpy, matplotlib

- Detailed Code (Github Version) : https://github.com/shrinidhi02/Revenue-Analysis--The-Movie-Database/blob/main/Revenue%20Analysis_The%20Movie%20Database.ipynb

**Main Findings:**

- The correlation between inflation adjusted budget and revenue is stronger as compared to other quantitative variables
- The average revenue trend over years is very erratic. Highest average revenue was observed in year 1977. Although it might be assumed that the trend would be upward based on the availability of different mediums to watch movies, the actual trend observed is very different than the general notion
- It can be observed that the correlation between inflation adjusted budget and revenue is 0.65, which can be considered to be strong. However, it does not necesaarily mean that higher budget always leads to higher revenue
- It can be observed that the revenue increases with the increase in the average votes except when the votes crosses 8.1. This might be because there might not be sufficient samples pertaining to 8.2 average votes. Whatever samples would be of 8.2 avg votes,they would not have high revenue
- It can be observed that the revenue is highest between runtime of 2 and 3 hours. Hence, it might be profitable to produce the content between 2 & 3 hrs duration

