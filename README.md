## MacOS Spotify Song Looper
This script provides an ability to loop a part of a song played on MacOS Spotify client. This is handy for practicing a riff. It leverages [Spotify's AppleScript API](https://developer.spotify.com/applescript-api/).

### Usage
1. Create a loop profile which contains `track_uri start_position end_position`

For example,
```
spotify:track:3A5o0lL7xAvKd1loW3uIID 0:00 0:14
```
The profile file contains
Using this profile will loop intro part of [Matt Costa's Astair](https://open.spotify.com/embed/track/3A5o0lL7xAvKd1loW3uIID) between 2th and 11th second.

2. Run `looper.sh <path_to_profile>`

#### Getting Track URI
![](http://i.imgur.com/tJxCvNF.png)
