# LIRI-Bot
UNCC-BOOTCAMP-LIRI-ASSIGNMENT

The app working:

https://youtu.be/YRIHFjyu3CY

![videoWorking](/Users/dan/Documents/UNCC-Bootcamp/homework/liri-node-app/videoWorking.gif)



## What is it?

The LIRI bot is a node application that simulates the functionality of Apple's SIRI in a very limited manner. The app has the ability to run the following functions:

### spotify-this

Spotify-this uses the following command:

`node liri.js spotify-this <song name>`

Using the spotfiy API this command returns:

1. Artist
2. Song
3. Preview
4. Album

By default it returs results for "The Sign" by ace of Base.

### concert-this

Concert this uses the following command:

`node liri.js concert-this <artist/band request>`

Using the Bands In Town Artisist Events API this command returns:

1. Date
2. Name
3. City
4. Country
5. Country

### movie-this

Movie  this uses the following command:

`node liri.js movie-this <movie name request>`

Using the IMDB API this command returns:

1. Title
2. Release Year
3. IMDB Rating
4. Rotten Tomatoes
5. Country
6. Language
7. Plot
8. Actors: Bruce Willis, Gary Oldman, Ian Holm, Milla Jovovich

By default (no command entered) this returns details for the movie "Mr. Nobody"

### do-what-it-says

do what it says uses the following command:

`node liri.js do-what-it-says`

Using the fs (file system) NODE package, the contents of the random.txt file in the same directory is read and runs the command:

`node liri.js spotify-this I Want It That Way`

### log.txt

using append file, all results are logged to the log.text file.



