# Spotify Playlist Recommendation based on input text by the user

For this project, we used deep learning techniques to create a Spotify playlist based on the text input by the user. 

## How it works 

Spotify provide audio features to 'define' each track that can be playback in the streaming platform. For example:

- Danceability: Describes how suitable a track is for dancing based on a combination
of musical elements including tempo, rhythm stability, beat strength, and overall
regularity.
- Energy: Represents a perceptual measure of intensity and activity. Typically,
energetic tracks feel fast, loud, and noisy. For example, death metal has high energy,
while a Bach prelude scores low on the scale
- Loudness: The overall loudness of a track in decibels (dB). Loudness values are
averaged across the entire track and are useful for comparing relative loudness of
tracks
- Liveness: Detects the presence of an audience in the recording. Higher liveness
values represent an increased probability that the track was performed live.
- Valence: Describes the musical positiveness conveyed by a track. Tracks with high
valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low
valence sound more negative (e.g. sad, depressed, angry). 

In the meantime, we can use the songs' lyrics to train a DL model, in order to predict the according Spotify features for a given text.

By this, we can compare the predicted vector with the Spotify DB, and create an interesting playlist which expresses the sentiment of the text, containing the n-most similar songs.
