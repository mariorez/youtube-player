# OBS-Youtube-Player

Designed for OBS Browser source to display/play a song/playlist fully automaticly with customs fixed params.

## Usage : add ? at the end of the link and copy Youtube link from "watch?v=XXXXX" or "watch?v=XXXXX&list=XXXXX")

exemple : https://mariorez.github.io/youtube-player/?watch?v=H59bAAJyVjc&list=PL3wn4S23QM9jxgFPGJ4DIGsynrco1VrzQ&index=1&controls=true
## Tutorial (video with subtitles instructions): https://youtu.be/y8VerA88A6U

## Features :

**volume :** Volume of the video player : &volume=VALUE (0 to 100, default is 45)\
 **w :** Width of the video player : &width=VALUE (default is 535) \
 **h :** Height of the video player : &height=VALUE (default is 300)\
 **hide :** Hide the video player : &hide=true|false (default is false)\
 **hideWhenStopped :** Hide all when video stops : &hideWhenStopped=true|false (default is false)\
 **quality :** Video quality of the player : &quality=small|medium|large|hd720|hd1080|highres|default (default is default)\
 **forcequality :** Enforce choosen video quality : &forcequality=true|false (default is false)\
 **speed :** Video speed of the player : &speed=0.2|0.5|1|1.25|1.5|2|any number (default is 1)\
 **t :** Start the video at desired time in seconds : &t=15 (default is 0)\
 **index :** On playlist, choose the first song by index : $index=2 (default is 0)\
 **loop :** Loop video/playlist when finished : &loop=true|false (default is true)\
 **random :** Randomize next song on playlist : &random=true|false (default is true)\
 **fade :** Enable the volume fade on song start & end : &fade=true|false (default is false)\
 **title :** Show the current song (name + author) : &title=true|false (default is false)\
 **controls :** Toggle video controls (progress, sound, play button, etc...) : &controls=true|false (default is false)\
 **debug :** Enable debug mode & show info on console : &debug=true|false (default is false)

Song title/author's display is fully customizable with CSS rules from OBS directly with `#songTitle` and `#songAuthor`

## Built-in features by default :

autoplay = enabled,  
Video controls (play, next, etc..) = hidden,  
Fullscreen button = hidden,  
Video info = hidden,  
Loop mode = enabled,  
Fade = disabled,  
Randomize = enabled,  
Video annotation = disabled,  
and more....  
