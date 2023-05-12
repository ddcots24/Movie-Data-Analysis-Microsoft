# Movie-Data-Analysis-Microsoft
## Overview
Topic: Microsoft wants to enter the movie business industry
- We were tasked to give three recommendations to Microsoft for entering the industry as a part of their Data Scientist team
- We used the Python package Pandas to load in and clean data from data sets as well as analyze, create visualizations and make recommendations
## Business Understanding
- The key stakeholders are the higher ups in the company such as the CEO and Owners
- Microsoft is entering a very saturated industry with many big competitors
   - How can Microsoft best navigate starting a new movie studio?
- A good measure of success in any industry is the return on investment and profit
- In our analysis we focused in on recent movies from 2010-2019 and their profitability
- The more granular focus of our analysis was in the profitability of top: movie genres, movie run times and movie actors/actresses
## Data Understanding
- We used two different data sets
  - IMDB [website](https://www.imdb.com/)
    -   A data set which contained categorical information on movie start years, run times, peoples profession associated with the movie (actors, actresses, writers, directors, producers etc..)
  -  [The Numbers](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/blob/main/zippedData/tn.movie_budgets.csv) [website](https://www.the-numbers.com/)
     -  A data set which contained numerical information on movie production budgets and gross earnings from which we were able to calculate the profit
 -  We merged the two different data sets to conduct our analysis on movie profitability in our three areas of focus
## Data Analysis
### Most Profitable Genres
 - Based on our data we found most profitable genres by median profit
 ![Project 1 image 1](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/assets/131708046/c0b75b1a-4936-4eac-8d8d-797103ee79fc)
 - From the top 13 genres with the highest profitability based on the median profit we decided to focus in on the top 4 genres
### Top 4 Genre's Profitability based on Run Times 
- For these Top 4 profiting genres, we analyzed each with respect to profit by run times
![Project 1 image 2](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/assets/131708046/1d3c57ba-eaf3-4fbe-b59d-d0e8abea9e56)
- We found that for animation movies the most profitable run times are in the time range of 80-110 minutes
- For the other three genres, the most profitable run times are in the interval of 140-155 minutes
  - The 125-140 and 155-170 run times are quite profitable as well
### Action Genre Most Profitable Actor/Actress  
- Profitability of top 10 actors for the action genre
  - Chose the action genre because it had the most actors and actresses in the data set compared to the other top 4 genres
- We filtered down to actors who had been in 4 or more different action movies which represents their popularity and established success in the action genre
![Project 1 image 3](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/assets/131708046/ece9cbdc-7147-44d5-ac36-2cf03840b403)
## Conclusion
- If Microsoft were to enter the movie industry we would give 3 recommendations:
  - Pursue 1 of the top 4 most profitable genres (Animation, Adventure, Sci-Fi and Action)
  - For Adventure, Sci-Fi and Action focus on runtimes between 140-155 minutes. For Animation focus on runtimes between 80-110 minutes
  - For Action movies, recruit 1 of the 10 actors previously shown
 ## Repository Information
 - This repository contains:
   - 2 folders containing exploratory notebooks
   - A folder containing data
   - A gitignore file
   - A presentation pdf
   - Final project Jupyter Notebook
   - A readme file
### [Presentation](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/blob/main/Presentation.pdf)
