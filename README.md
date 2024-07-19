# MovieMatch
A movie recommendation system similar to Netflix
Content Based Recommender System recommends movies similar to the movie, the user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API. 

I used *web scraping* to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.
## Running Flask Tests


To run a Flask deployment tests, run the following command

```bash
  python main.py
```
<br>
<img src="https://github.com/Lahari25/MovieMatch/blob/main/MovieMatch/in.jpg" width="950" height="400">
