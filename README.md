# Dmenu Video Downloader
This script ease the task of downloading videos using youtube-dl and dmenu.

## Demo
![demo1.gif](https://raw.githubusercontent.com/thomas154/gifs-for-repositories/master/dmenu-downloader-gif/demo1.gif)

## Dependency
+ Greenclip (You can tweak the script accordingly if you use any other clipboard manager)
+ Dmenu
+ Youtube-dl
+ aria2c (optional, but then you have to manually tweak the present script)

## Installation
```
git clone https://github.com/thomas154/dmenu-video-downloader.git
cd dmenu-video-downloader
chmod +x vid-download extract
```
## Usage
```
./vid-download
```
better to create an alias in bashrc to access from anywhere.

## Some important points
+ To download video only file and audio only file at quality selection menu, always first select the video first then audio you can do it in one go by pressing (as shown in demo).
```
ctrl + Enter #for multiple selection.
```
+ Youtube-dl will automatically merge video and audio after downloading get finished.
+ Use case is that you can reduce the download size by selecting different quality audio and video.


![demo2.gif](https://raw.githubusercontent.com/thomas154/gifs-for-repositories/master/dmenu-downloader-gif/demo2.gif)
