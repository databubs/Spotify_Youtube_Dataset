# Introduction
Hello there! My name is Bobby and in this case study, I will be primarily focusing on visualizing music trends and popularity using datasets from Spotify and YouTube using R Studio.

# Ask
What are we trying to figure out of this dataset? Well for starters,

# Data Source
The data was obtained from Kaggle [Click to view the dataset](https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube)
The dataset consists of 28 columns and several thousand rows. The columns include the following:

<details>
  <summary>Click</summary>
Artist: the artist name

Url_spotify: the Spotify URL for the song

Track: the name of the song

Album: the album name

Album_type: the type of album (e.g., album, single, compilation)

Uri: the Spotify URI for the song

Danceability: a measure of how danceable the song is

Energy: a measure of how energetic the song is

Key: the musical key of the song

Loudness: a measure of how loud the song is

Speechiness: a measure of how much speech-like sounds are in the song

Acousticness: a measure of how acoustic the song is

Instrumentalness: a measure of how instrumental the song is

Liveness: a measure of how live the recording is

Valence: a measure of the song's positivity (e.g., happy, cheerful)

Tempo: the tempo of the song

Duration_ms: the length of the song in milliseconds

Url_youtube: the YouTube URL for the music video

Title: the title of the music video

Channel: the name of the YouTube channel that uploaded the music video

Views: the number of views the music video has on YouTube

Likes: the number of likes the music video has on YouTube

Comments: the number of comments the music video has on YouTube

Description: the description of the music video on YouTube

Licensed: whether or not the music video is licensed

official_video: whether or not the music video is an official music video

Stream: whether or not the song is available for streaming on Spotify
</details>



# Process
Extract csv file to a designated folder onto my desktop
"C:\Users\USER\Desktop\Spotify_Youtube"

Install packages:
```r
install.packages(c("ggplot2", "tidyverse", "readr"))
```
Load the packages up:
```r
library(ggplot2)
library(tidyverse)
library(readr)
```
Load .CSV onto R studio
```r
data <- read_csv("spotify_youtube.csv")
```


# Share

![alt text](https://github.com/databubs/Spotify_Youtube_Dataset/blob/main/Energy_Type_Album.png)

![alt text](https://github.com/databubs/Spotify_Youtube_Dataset/blob/main/Number_Of_Tracks.png)

![alt text](https://github.com/databubs/Spotify_Youtube_Dataset/blob/main/Purple_Relationship_Danceability.png)

![alt text](https://github.com/databubs/Spotify_Youtube_Dataset/blob/main/Valence_Color.png)



# Acknowledgements
The dataset was obtained from Kaggle, and the original source of the data is the Spotify API and the YouTube Data API. The data was collected on August 5th, 2021, and was made available for public use by its author, Matteo Viel.







