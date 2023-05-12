# Movie-Data-Analysis-Microsoft
## Overview
Topic: Microsoft wants to enter the movie business industry
- We were tasked to give three reccomendations for Microsoft to enter the industry as a part of their Data Scientist team
- We used Pandas to clean data from data sets, make analysis, and make reccomendations
## Business Understanding
- The key stakeholders are the higher ups in the company such as the CEO and Owners
- Microsoft is entering a very saturated industry with many big competitors
   - How does microsoft get into the industry?
- A good measure of success in any industry is the return on investment and profit
- In our analysis we focused in on recent movies from 2010-2019 and their profitability
- We got more granular in our analysis and focused on the profitabily of top: movie genres, movie run times and movie actors/actresses
## Data Understanding
- We used two different data sets
  - IMDB 
    -   A data set which contained categorical information on movie start years, run times, peoples profession associated with the movie (actors, actresses, writers, directors, producers etc..)
  -  The Numbers
     -  A data set which contained numerical information on movie production budgets, and gross earnings where we were able to calculate the profit
 -  We merged the two different data sets and then were able conduct our analysis on movie profitability
## Data Analysis
### Most Profitable Genres
 - Based on our data we found most profitable genres by median profit
 ![Project 1 image 1](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/assets/131708046/c0b75b1a-4936-4eac-8d8d-797103ee79fc)
 - From the top 13 genres with the highest profitability based on the median profit we decided to focus in on the top 4 genres
### Top 4 Genre's Profitability based on Run Times 
- We then took a look at the top 4 genres at the highest average profitability for each respective genre for their run times
![Project 1 image 2](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/assets/131708046/1d3c57ba-eaf3-4fbe-b59d-d0e8abea9e56)
- We can see that for animation movies that the most profitable run times are from 80-110 minutes
- For the other three genres, we can see that the most profitable run times are from 140-155 minutes
  - The 125-140 and 155-170 run times are profitable as well
### Action Genre Most Profitable Actor/Actress  
- Profitibality of top 10 actors for the action genre
  - Chose the action genre because it had the most actors and actresses in the data set compared to the other top 4 genres
- We chose actors who had been in 4 or more different movies to choose actors who have been popular for the genre and have had traction in the movie industry
![Project 1 image 3](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/assets/131708046/ece9cbdc-7147-44d5-ac36-2cf03840b403)
## Conclusion
- If microsoft were to enter the movie industry we would give them three recommendations
  - Pursure one of the top 4 most profitable genres(Animation, Adventure, Sci-Fi, Action)
  - For Adventure, Sci-Fi and Action focus on runtimes between 140-155 minutes. For Animation focus on runtimes between 80-110 minutes
  - For Action movies, recruit 1 of the 10 actors previously shown
