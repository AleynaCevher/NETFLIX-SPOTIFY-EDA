# Netflix-Spotify Dataset Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis (EDA) of a combined Netflix-Spotify dataset using Python. The analysis delves into the relationship between various audio characteristics, track popularity, and audience engagement metrics such as views, likes, and comments.

## Dataset Description

The dataset used for this analysis consists of the following columns:

- **Artist**: The name of the artist.
- **Track**: The title of the track.
- **Album**: The name of the album.
- **Album_type**: The type of album (e.g., Single, Album).
- **Danceability**: The degree to which a track is suitable for dancing, based on tempo, rhythm stability, and beat strength.
- **Energy**: The intensity and activity level of the track.
- **Key**: The key in which the track is composed.
- **Loudness**: The overall loudness of the track measured in decibels (dB).
- **Speechiness**: The presence of spoken words in the track.
- **Acousticness**: The likelihood that the track is acoustic.
- **Valence**: The musical positiveness conveyed by the track.
- **Tempo**: The speed or pace of the track.
- **Duration_ms**: The duration of the track in milliseconds.
- **Channel**: The name of the channel associated with the track.
- **Views**: The number of views the track has received on YouTube.
- **Likes**: The number of likes the track has received on YouTube.
- **Comments**: The number of comments on the track.
- **Licensed**: Indicates if the track is licensed.
- **Official_video**: Indicates if the track has an official video.
- **Stream**: The number of streams the track has received on Spotify.

## Key Analyses Conducted

1. **Top 10 Most Watched Songs on YouTube**: Identification and visualization of the top 10 tracks with the highest views on YouTube, along with their corresponding characteristics such as Danceability, Energy, and Valence.

2. **Characteristics of Most Watched Tracks**: A deep dive into the characteristic features (Danceability, Energy, Speechiness, Acousticness, Valence) of the 8 most-watched songs on YouTube.

3. **Country Distribution of Artists**: Analysis of the geographical distribution of artists and how it relates to the popularity of their tracks.

4. **Year-wise Trends**: Exploration of trends in track popularity over the years, including changes in Danceability, Energy, and Valence.

5. **Top 10 Most Streamed Artists on Spotify**: Identification of the most streamed artists and tracks on Spotify, with a focus on their popularity across different regions.

6. **Album Types**: Analysis of the distribution of different album types (e.g., Single, Album) and their impact on track popularity and streams.

## Visualization

The analysis includes various visualizations such as bar charts, scatter plots, and line graphs to represent the distribution and trends within the dataset. Special emphasis was placed on understanding the relationship between audio features and audience engagement.

## Conclusion

This EDA provides insights into how certain audio characteristics influence the popularity of tracks on platforms like YouTube and Spotify. By examining various metrics, we gain a better understanding of what makes a track successful in terms of views, likes, and streams.

## Repository Structure

- **`/data`**: Contains the raw dataset used for the analysis.
- **`/notebooks`**: Jupyter notebooks with the code for data cleaning, analysis, and visualization.
- **`/visualizations`**: Outputs of the analysis, including charts and graphs.
- **`README.md`**: This file.

## How to Use

To reproduce the analysis, clone the repository and run the Jupyter notebooks in the `/notebooks` directory. Ensure that all dependencies are installed as listed in the `requirements.txt` file.

## License

This project is licensed under the MIT License.
