# Appo Music

## `About`

Appo Music is a full-stack clone of the incredible Apple Music online streaming platform, with an aim to re-create it's core features, seamless design, and excellent user experience.

Backend:

-   Ruby on Rails

Frontend:

-   JavaScrip ES6
-   React
-   Redux

## `Features`

### Music Player

-   Fully functional music player
-   Clicking/playing a song adds song to music player and automatically creates a queue of next songs
-   Loop/shuffle functionality (setting saved for next session if logged in)
-   "LCD" display with current playback information and relevant links to song artist & album
-   30 Second previews for logged out users
-   Space bar support to play/pause from keyboard

<img src="/readme/musicplayer.gif">

### Search

-   Live search the entire database
-   Results seperated by appropriate categories
-   Selecting a result leads to relevant page

<img src="/readme/search.gif">

### Artist Page

-   Displays most recent release and chronological discography
-   Live list of top songs – calculated by play count
    -   Selecting a top songs leads to album that contains it, hightlights song, and brings it into view for easy selection
-   Quickplay
    -   Start playback of artist's most popular songs
-   Artist description modal

<img src="/readme/artist.gif">

### Album Page

-   Displays album track listing and information
-   Ability to save individual songs or entire album to user library
-   Ability to add song to playlist

<img src="/readme/album.gif">

### Playlist CRUD

-   User can create, rename, delete and add songs to playlist
-   Playlist page contains all playlist songs with a rotating display of their album's cover artwork

<img src="/readme/playlist.gif">

### User Authentication

-   Simple, yet elegant modal for user account creation and login
-   Demo user provided with automatic login functionality

<img src="/readme/auth.gif">

## `Future Features`

-   Up/arrow/enter key functionality on album/playlist pages
-   Improved mobile compatibility
