# Dmenu Video Downloader
This script ease the task of downloading videos using youtube-dl using dmenu.

## Demo

## Dependency
+ Greenclip (You can tweak the script accordingly if you use any other clipboard manager)
+ Dmenu
+ Youtube-dl
+ aria2c (optional, but then you have to manually tweak the present script)

## Installation
```
git clone
chmod +x vid-download extract
```
## Usage
```
./vid-download
```
better to create an alias in bashrc to access from anywhere.

## Some important points
+ To download video only file and audio only file at quality selection menu, always first select the video first then audio you can do it in one go by pressing 
```
ctrl + Enter #for multiple selection.
```
+ Youtube-dl will automatically merge video and audio after downloading get finished.
+ Use case is that you can reduce the download size by selecting different quality audio and video
