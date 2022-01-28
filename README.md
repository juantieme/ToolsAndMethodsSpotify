# Visual Eurovision Project

With this project we tried to extract data using Spotify API to analyse songs performed in the last 10 years on Eurovision, the popular European singing contest. 

We did that by first inputting the unique ID into the API. After creating a playlist with wanted Eurovision songs we exported it via Spotify’s automated feature which returned JSON files containing the information about the artist, song, name, year, popularity and various audio features (danceability, energy, loudness, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration (in milliseconds) and a time signature). For this purpose we used the 'CodeForSpotifyPlaylist.ipynb' notebook to extract this information. The output can be found in the directory 'raw data'.

With this information we created various subdatasets containing converting the dataset to suit different visualization models. This was done using the 'CodeForConversionToVisualization.ipynb' notebook. The resulting CSV files can be found in the 'cooked data' directory.

We used these datasets to make visualizations on the website [Flourish](https://flourish.studio/examples/) and used these for our further analysis.

The result of the analysis has been published on a github pages website found [here.](https://juantieme.github.io/project.html)
