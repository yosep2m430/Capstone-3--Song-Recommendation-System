# Spotify_Music_Recommendation_System
-Spotify is a continuously growing audio streaming platform serving both artists and listeners worldwide. With increasing competition, Spotify has seen a slow decline in its market share. Our goal is to develop a data-driven recommendation system to better cater to users’ tastes. 

-In  [Data Wrangling.ipynb](https://github.com/yosep2m430/Song-Recommendation-System-Capstone-3-/blob/main/Data%20Wrangling.ipynb), there are two types of datasets: a dataset for audio features and a dataset for user listening behavior. More specifically:
  - US 1921- 2020 dataset: contains audio data for popular songs in 1921-2020 broken down into 20 features: danceability, valence, energy, tempo, loudness, speechiness, instrumentalness, liveness, acousticness, popularity, song name, artist name, song id, artist id, explicitness, duration, release date, key, mode (musical mode), and time signature.
  - User ID Playlist Dataset: contains user ID data, along with tracks, artists, and playlists they interacted with.
-In [Exploratory Data Analysis (EDA).ipynb](https://github.com/yosep2m430/Song-Recommendation-System-Capstone-3-/blob/main/Exploratory%20Data%20Analysis%20(EDA).ipynb), the relationships between audio features and the relationships between user, tracks, and playlists are explored.
-In [Modeling.ipynb](https://github.com/yosep2m430/Song-Recommendation-System-Capstone-3-/blob/main/Modeling.ipynb), collaborative-filtering model, content-based filtering model, and hybrid model are explored.
-Hybrid model was able to find user with similarity of 0.816.
