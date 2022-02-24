# DF modified version
+ modification: 
  + add more flag for saving as much detail as possible
  + replace `youtube-dl`  to `yt-dlp`  
  + add the format parameters by [this stackoverflow thread](https://askubuntu.com/questions/856911/using-youtube-dl-to-download-entire-youtube-channel)
## youtube-dl config - downloading entire channels for archival

by https://www.reddit.com/user/Stephen304

https://www.reddit.com/r/DataHoarder/comments/858ny5/my_youtubedl_config_downloading_entire_channels/

# Usage

Edit channel urls in `youtube-dl-channels.txt`.

Empty file `youtube-dl-archive.txt` is used to store downloaded ids.

## Linux

    chmod +x download_archive.sh

Run using `./download_archive.sh`

## Windows

Run `download_archive.bat`
