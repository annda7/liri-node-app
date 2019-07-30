# Liri-node-app - Homework!


## liri.js can take in one of the following commands:<h2>

1. concert-this
2. spotify-this-song
3. do-what-it-says
4. movie-this


# 1. concert-this

This will search the Bands in Town Artist Events API:

* Name of the venue
* Venue location
* Date of the Event (use moment to format this as "MM/DD/YYYY")

![concert-this](/images/concertthis.png)


# 2. spotify-this-song

This will show the following information about the song in your terminal/bash window
  

* Artist(s)
* The song's name
* A preview link of the song from Spotify
* The album that the song is from

![spotify-this-song](/images/spotify-this1.png)

###     *If no song is provided then your program will default to "The Sign" by Ace of Base.

![spotify-this-song](/images/spotify-this.png)


# 3. do-what-it-says

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.
![do-what-it-says](/images/do-what-it-says.png)


# 4. movie-this
This will output the following information to your terminal/bash window:

   * Title of the movie.
   * Year the movie came out.
   * IMDB Rating of the movie.
   * Rotten Tomatoes Rating of the movie.
   * Country where the movie was produced.
   * Language of the movie.
   * Plot of the movie.
   * Actors in the movie.

![movie-this](/images/movie-this1.png)

###     *If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

![movie-this](/images/movie-this2.png)





Technologies Utilized
Node packages:

Node-Spotify-API
Axios
    You'll use Axios to grab data from the OMDB API and the Bands In Town API
Moment
DotEnv





Author
Saranda Sharpe