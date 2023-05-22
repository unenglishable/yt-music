# yt-music

`yt-music "<video-link>"`

OR

`yt-music "<playlist-link>"`


## instructions (macOS)


### requirements

```bash
brew update
brew upgrade
brew install yt-dlp ffmpeg
```


### installing

```bash
git clone git@github.com:unenglishable/yt-music
cd yt-music
./link.sh
```

## configuration

select a directory for files to be stored and processed in

~/.bashrc
```bash
# (defaults to $HOME/youtube)
export YT_MUSIC_DIR=$HOME/youtube
```
