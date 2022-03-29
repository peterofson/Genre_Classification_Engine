# Music Genre Classification: Album Cover Images vs Text: A Compact Recommendation Engine
## Abstact
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Music services entice their users by making personal playlists, recommending new songs,
and can make a playlist based on a song or artist. At its root, music recommendation comes
down to genres. This study extracts album covers images and lyrics for ten music genres to be
classified with a convolutional neural network (CNN) compared to that of a Long Short-Term
Memory (LSTM) as well as an ensemble algorithm


## Introduction
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Spotify is the largest music streaming service in the world as of 2022 (Spotify, 2022) but
it fails to grab new and upcoming music which isn’t in their library. It also tends to get stuck and
recommend the same songs based on the user’s history. A huge drawback which this paper will
focus on implementing. Three algorithms will be trained to classify genres based on album cover
images pulled from Spotify. Once trained, a function will grab new and upcoming albums from
SoundCloud to be classified. Then a playlist can be made from the SoundCloud data by choosing
which genre a user wants to hear. This playlist will feature new and upcoming music that the
Spotify algorithm doesn’t pick up, while simultaneously not letting the genre labels have too
much weight in recommendations. 
