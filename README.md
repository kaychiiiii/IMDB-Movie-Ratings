# IMDB-Movie-Ratings
An analysis of IMDB movie datasets, retrieved on 4 Dec 2021.

* Data source: [IMDb Datasets](https://www.imdb.com/interfaces/)
* Datasets: `title.akas.tsv.gz`, `title.basics.tsv.gz`, `title.crew.tsv.gz`, `title.ratings.tsv.gz`, `name.basics.tsv.gz`
* Libraries: `matplotlib`, `seaborn`, `pandas`, `numpy`, `math`

## Summary:
* The cleaned dataset `my_df.csv` consists of only US movies with IMDB ratings recorded
* Most movies have an IMDB rating of 6.2 to 7.0
* Most movies received between 100 to 1000 votes, with a minimum and maximum of 5 and 2498691 votes respectively
* Most movies were released after 2006
* The average IMDB ratings for movies after 1910 hovered around a low 6.0, but recently the range of scores were larger
* Christopher Nolan has six films within the top 30 most number of votes, followed by three films from a different director
* IMDB ratings of 10.0 received only a maximum of 511 votes
* Movies with extremely high ratings were mostly recent releases
* Drama is the most popular genre, followed by comedy
