---
permalink: /index.html
---

# Exploring the Cold Start Problem via Spotify

## Seth Billiau, William Drew, Sarah Lucioni
### Group 56

Website URL: [CS 109a Final Project](https://sethbilliau.github.io/spotify_playlists)

### Abstract

When it comes to music, streaming is the way of the future. Convenient, cheap, and widely accessible, streaming is easier than ever with more people turning to popular services for their musical needs. In April of 2019, industry leader Spotify announced that they had reached a staggering 217 million monthly active users with over 100 million paid subscribers (Porter, “Spotify Is First to 100 Million Paid Subscribers.”).

In addition to providing music for its users, Spotify also provides a robust music recommendation system. Leveraging data science and machine learning techniques, Spotify aggregates a number of different models to generate new playlists based on a user’s musical preferences.

Developing a user’s musical taste is no small feat, but Spotify is able to overcome this hurdle by collecting user feedback on generated playlists with an up/down vote system and by aggregating information from a user’s listening history. But what if they didn’t have all of that information? How should Spotify generate a new playlist for a brand new user given minimal user information? Imagine a new user stumbles upon Spotify for the first time and plays a song. From this single song, is it possible to generate a likeable playlist?

Our project attempts to answer this question by developing such a "cold start" model, generating a new playlist for a user given just a single song.
