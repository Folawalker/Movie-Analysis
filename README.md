# Movie Analysis
The project aims to perform Exploratory Data Analysis(EDA) on movies released between 1980-2020
# Table of Content
- Project Overview
- Dataset
- Usage
- Exploratory Data Analysis
  - Overview of the data
  - General Analysis
  - Yearly Trends
  - Correlation Analysis
  - Country-Wise Analysis
  - Director-wise Analysis
  - Company-Wise Analysis
  - Comparative Analysis
- Contributions
# Project Overview
The primary goal of this project is to understand the relationships between various factors like budget, revenue, etc and a movie’s performance to help studios make data driven decisions.
# Dataset
- `Name`: The title of the movie
- `Rating`: Rating of the movie (R, PG, etc.)
- `Genre`: Main genre of the movie
- `Year`: Year the movie was released
- `Released`: The specific date the movie was released
- `Score`: IMDB user rating
- `Votes`: Number of user votes
- `Director`: Movie director
- `Writer`: Writer of the movie
- `Star`: Main actor/actress
- `Country`: Country of origin
- `Budget`: Movie budget
- `Gross`: Revenue of the movie
- `Company`: The production company
- `Runtime`: Duration of the movie
# Usage
Download the 'csv' file to access the raw dataset and download the '.ipynb' file to visualize and analyze.
# Exploratory Data Analysis
## 1. Overview of the Data
- Shape of the Dataset: Check the number of rows and columns.
- Data Type: Verifying the data type of each column
- Missing Values: Identify any missing values in the dataset and deal with them accordingly
- Summary Statistics: Check for the mean, median, standard deviation, minimum, and maximum for numerical features.
## 2. General Analysis
- Movie Rating
  - Top 10 Rated Movies: Movies with the highest rating
  - Bottom 10 Rated Movies: Movies with the lowest rating
- Revenue Generation
  - Top 10 Grossing Movies: Movies with the highest revenue generated
  - Bottom 10 Grossing Movies: Movies with the lowest revenue generated
- Genres Rating
  - Top 5 Scoring Genres: Genres with the highest average rating
  - Bottom 5 Scoring Genres: Genres with the lowest average rating
## 3. Yearly Trends
- Budget Changes Over Time: Check and visualize average and total movie budget across the years 
- Revenue Generation Over Time: Analyze and visualize average and total revenue generated across the years
- Movie Ratings Over Time: Check and visualize average movie rating over time
## 4. Correlation Analysis
- Budget vs Gross Revenue: Check correlation between budget and revenue
- Correlation Heatmap: Check correlation between all numerical variables in the dataset
## 5. Country-Wise Analysis
Movie Rating: Check how average movie ratings change across countries
Budget: Check how budget changes across countries
Gross Revenue: Check how revenue generated varies across countries
## 6. Director-Wise Analysis
Most Popular Directors By Number of Movies
By Rating
Directors With Highest Peak
By Budget
By Revenue
