# SpotifyGeeklet
Geeklets to show the Title, Artist, Album &amp; Album Artwork of the currently playing track in Spotify.

## How it Works
The main component is an AppleScript file which gathers the currently playing track information and downloads the album artwork image to the /tmp directory.  Once downloaded, the downloaded image (JPEG) is converted to TIFF and the originsl JPEG is deleted.  This is done so that when music is not playing, a "default" artwork, which is a blank TIFF file, is copied to the /tmp directory so the album artwork clears on the desktop.

## Installation Instructions
1. Click the **Clone or download** button and select **Download ZIP**
2. Decompress the downloaded **SpotifyGeeklet-master.zip** file
3. In your **Documents** folder, create a **Geektool** folder if you don't have it already
4. In the new **Geektool** folder, create a **SpotifyNowPlaying** folder
5. Copy the files from the decompressed **SpotifyGeeklet-master.zip** file into the **SpotifyNowPlaying** folder
6. Open each of the geeklet files in the **SpotifyNowPlaying** folder to add to Geektool

## File List & Descriptions
- **ArtworkDisplayer.glet** - this geeklet displays the album artwork of the currently playing song
- **ArtworkRunner.glet** - this geeklet runs the AppleScript file which retrieves the album artwork of the currently playing song
- **DefaultArtwork.tiff** - this is a blank image file which is used when no music is playing
- **NowPlaying.glet** - this geeklet displays the track name, artist and album name of the currently playing song
- **SpotifyNowPlaying.scpt** - this AppleScript retrieves the currently playing track information and downloads the album artwork so it can be displayed
