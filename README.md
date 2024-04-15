# Spotify Classification Dashboard and Model Analysis

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/suppiero/spotify_classification_dash/main?urlpath=https%3A%2F%2Fgithub.com%2Fsuppiero%2Fspotify_classification_dash%2Fblob%2Fmain%2Fspotify_song_classification.ipynb)

## Project Overview

Crafting predictive models to determine whose playlist a song belongs to and summarizing results into an interactive dashboard. 

In this project, my friend Nirvit and I shared our 2023 Spotify Wrapped playlists so we could visualize comparisons between our music tastes and then create a model to try and predict whose playlist a song belongs to. Finally, I have compiled the results of each model into an interactive dashboard using [Panel](https://panel.holoviz.org/).

You can explore my methods and examine my code in a more user-friendly format over on my [blog post](https://suppiero.github.io/projects/spotify_classification_dashboard/spotify_song_classification.html).

## Result
![Project Screenshot](Spotify_Dashboard_Recording_30_fps.gif)

## Data

The Spotify datasets utilized in this project, sourced from Chosic, provide comprehensive information on various song attributes.

[**Gather Your Own Spotify Dataset**](https://www.chosic.com/spotify-playlist-analyzer/?plid=37i9dQZF1Fa1IIVtEpGUcU)

**Track Metadata**
| column | description |
| --- | --- |
| Song | Song title |
| Artist | Song artist |
| Genre | Song genre category |

**Audio Numerical Quantitive Data**
| column | description |
| --- | --- |
| Loud | How loud a song is (db) |
| Time Seconds | Duration of the song in seconds |
| BPM | Average song tempo / how fast a song is |

**Audio Qualitative Data**
| column | description |
| --- | --- |
| Energy | How energetic the song is |
| Dance | How easy the song is to dance to |
| Happy | How positive the mood of the song is |
| Acoustic | How acoustic sounding the song is |
| Speech | How much of a song is spoken word |
| Popularity |  How popular a song is (at time of data collection) |
| Live | How likely the song is a live recording (higher value = live recording) |
| Instrumental | Measures if the song is more music and less vocals |


**Audio Categorical Data**
| column | description |
| --- | --- |
| Key | The most repeated key in the song |
| Time Signature | Numerical representation of rhythmic structure in song |
| Camelot | Musical key of a song for harmonic mixing |
| Playlist Owner | Who's playlist the song belongs to |

## Usage

To use the project, follow these steps:

1. Ensure you have the required dependencies installed (to install the dependencies, please refer to the requirements.txt file).
2. Make sure you have obtained the Spotify datasets (see the [Data](#data) section).
3. Run the project script or notebook using Python.
4. Explore the visualizations and interact with the points, buttons, and bar plots to analyze different aspects of the Spotify data and models.
5. To serve the dashboard locally, use the command:
```terminal
panel serve spotify_song_classification.ipynb
```
