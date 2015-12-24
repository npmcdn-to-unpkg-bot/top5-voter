# top5-voter

A simple voting app built with React, React-Router, Firebase, LocalStorage, IFTTT, and Spotify.

When tracks are added to a playlist, Spotify triggers IFTTT to add the tracks to Firebase using the [Maker channel](https://ifttt.com/maker). This Firebase of Spotify tracks is queried depending on the app's route. Users can then "like" or "dislike" tracks, updating Firebase and their local storage.