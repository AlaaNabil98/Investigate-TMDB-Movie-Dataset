# Investigate-TMDB-Movie-Dataset
The primary goal of the project is to go through the dataset and the general data analysis process using numpy, pandas and matplotlib.
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

## Project Overview
In this project, I analyzed the TMDb movies dataset and then communicated my findings about it, this data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings, revenue, budget, director, release date, runtime, and more patterns.
I used the Python libraries NumPy, Pandas, Matplotlib, and Seaborn to make my analysis easier.

## What do you need to install?
You will need an installation of Python, plus the following libraries:
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Research Questions:
1)Top 20 Rated Movies?

2)What Kinds of properties are associated with Top 20 Rated Movies?

3)Top 20 Profitable Movies?

4)What Kinds of properties are associated with Top 20 Profitable Movies?

5)Top 10 Directors by Number of Released Movies?

6)What is The Distribution of Runtime?

7)What is The Correlations Between Movies Properties?

8)How Movies Profit changed over Years?

9)What is The Average Genre Profit?

10)What is The Distribution of Genre Profit?

11)How average Genre Profit changed over Years?

## Conclusions:
1)Top 5 Rated Movies are The Story of Film: An Odyssey, The Mask You Live In, Black Mirror: White Christmas, Life Cycles, and Pink Floyd: Pulse.

2)Top 5 Profitable Movies are Avatar, Star Wars: The Force Awakens, Titanic, Jurassic World, and Furious 7 .

3)Top 5 Directors with the number of released movies are Woody Allen, Clint Eastwood, Steven Spielberg, Martin Scorsese, and Ridley Scott.

4)Movie Duration must be between 58 and 142 minutes.

5)50% of the Movies' Duration is between 90 and 111 minutes.

6)Movies' Revenue, Profit, and Popularity are increased according to their Budget increase.

7)The Average Movies Profit is increased over time.

8)The Profitable Movies Genres are Adventure, Action, and Fantasy.


## Limitations:
* This Analysis isn't completely error-free, but it shows us the properties of profitable movies.
* During my analysis, I split genre values that separated by "|" into many rows for the exploration phase, this increases the analysis time.
* There is no currency unit for the budget, revenue, and profit columns so they may be in different currencies for different countries.
