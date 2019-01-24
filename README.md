# liri-node-app

LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.

![Screenshot](Screenshots\Screenshot (1).png);


spotify-this-song
LIRI utilizes the node-spotify-api package to retrieve song information from the Spotify API. If no song is provided, LIRI will default to "The Sign" by Ace of Base.

![screenshot 7](https://user-images.githubusercontent.com/44128719/51650434-5887a580-1f45-11e9-912f-6ad4b2cf2ccb.png)

concert-this uses Bands in Town Artist Events API to show information about an artist's upcoming shows.

![screenshot 9](https://user-images.githubusercontent.com/44128719/51650758-acdf5500-1f46-11e9-9d4f-c1154a3746ff.png)


movie-this retrieves from OMDB! If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'
If you haven't watched "Mr. Nobody," then you should: http://www.imdb.com/title/tt0485947/

![screenshot 8](https://user-images.githubusercontent.com/44128719/51650598-157a0200-1f46-11e9-9af5-4cd70e6af73a.png)

do-what-it-says will read the random.txt file and will run the spotify-this-song command for the song "I Want It That Way" by The Backstreet Boys.

![screenshot 5](https://user-images.githubusercontent.com/44128719/51650644-45290a00-1f46-11e9-92be-dd401235a529.png)

