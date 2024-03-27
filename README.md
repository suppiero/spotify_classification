# Spotify Classification Dashboard and Models

Building models to classify whether a song came from my Spotify Wrapped 2023 - Top 100 playlist or my friend’s.

# Data

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


[**Gather Your Own Spotify Dataset:**](https://www.chosic.com/spotify-playlist-analyzer/?plid=37i9dQZF1Fa1IIVtEpGUcU)
