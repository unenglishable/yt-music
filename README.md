# yt-music

## running "one-click" via macos dock

### setup

(complete all steps in INSTALLATION first)

then add the automator app to dock...

```bash
# cd yt-music/
open .
```

drag-and-drop yt-music.app to dock


### usage

1. copy a youtube video link (cmd+c)

2. click on yt-music app in dock

3. enjoy your music :)


## running via command line

(complete all steps in INSTALLATION first)

`yt-music "<video-link>"`

OR

`yt-music "<playlist-link>"`


## INSTALLATION (macOS)


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

## configuration (optional)

select a directory for files to be stored and processed in

~/.bashrc
```bash
# (defaults to $HOME/youtube)
export YT_MUSIC_DIR=$HOME/youtube
```
