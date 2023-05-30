# Spotify_Music_Recommendation_System

![image](https://github.com/yosep2m430/Music-Recommendation-System/assets/102874665/56998e02-0b0f-494a-ab0e-751fc23c038c)

*Spotify is a continuously growing audio streaming platform serving both artists and listeners worldwide. With increasing competition, Spotify has seen a slow decline in its market share. Our goal is to develop a data-driven recommendation system to better cater to users’ tastes.* 

## Data
A CSV file containing user ID, tracks, and playlist data was obtained from Kaggle:<br>
https://www.kaggle.com/code/tj00001/building-music-recommendation-system-using-spotify/input?select=spotify_dataset.csv<br>

Another CSV file for top charting US songs' audio data in 1921- 2020 was also sourced from Kaggle:<br>
https://www.kaggle.com/datasets/ektanegi/spotifydata-19212020

## Data Wrangling
In  [Data Wrangling.ipynb](https://github.com/yosep2m430/Song-Recommendation-System-Capstone-3-/blob/main/Data%20Wrangling.ipynb), there are two types of datasets: a dataset for user listening behavior and a dataset for audio features. In the user listening behavior dataset, data without playlist information were dropped, because they do not allow us to learn about user behavior. Those without either track titles or the artist names were cleaned, because we can only identify the exact song when we have both the track title and the artist name; they were dropped, since we have no way of imputing missing artist names or track titles. Finally, feature names from playlist data were renamed to match those of 1920-2020 audio feature dataset.

## Exploratory Data Analysis (EDA)
- In [Exploratory Data Analysis (EDA).ipynb](https://github.com/yosep2m430/Song-Recommendation-System-Capstone-3-/blob/main/Exploratory%20Data%20Analysis%20(EDA).ipynb), the relationships between audio features and the relationships between user, tracks, and playlists are explored.

## Modeling
- In [Modeling.ipynb](https://github.com/yosep2m430/Song-Recommendation-System-Capstone-3-/blob/main/Modeling.ipynb), collaborative-filtering model, content-based filtering model, and hybrid model are explored.
- Hybrid model was able to find user with similarity of 0.816.

## Future Improvements

## Project Report
[Final Project Report](https://github.com/yosep2m430/Music-Recommendation-System/blob/main/Final%20Project%20Report-%20Music%20Recommendation%20System.pdf)
