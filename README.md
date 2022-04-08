# 7.5-or-higher
### This is a personal project using IMDB data about movies and shorts. The main idea is to generate random suggestions to watch movies without spending too much time looking for one.

Last year my girlfriend and I realized that movies rated below 7 kind of make us feel like we've lost a little piece of our lives. So I decided to find a  solution to this and the "three hours looking for movies" problems.

It's simple, go to [IMDB datasets](https://www.imdb.com/interfaces/) and you'll find the IMDB databases. I downloaded the _title basics and ratings_ datasets, then I used the pandas package to filter out the 7.5 or higher rated movies, removed the information I don't need, and finally I saved it as final shorts and movies dataframes. 

Using these dataframes I applied some visualization techniques to present the duration of the movies and shorts segmented by intervals. Afterwards there is a pie chart showing the proportion of movies and shorts.
