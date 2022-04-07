videoinfox v.1.83


![Videoinfox HOME SCREEN](https://i.imgur.com/wMSSunr.png)

![Videoinfox FIND RESULTS SCREEN](https://i.imgur.com/UGe9W4w.png)
  
![Videoinfox FIND RESULTS SCREEN](https://i.imgur.com/ODPMA9K.png) 
 
 
  
Dependencies:   
 
- xclip needed for autopaste feature.  xclip only works with Xsession
  
- ffmpeg is used to extrat Duration in <hrs:min:sec> format
- ffprobe is used to extract Codec, Resolution and Duration in floating seconds format (x.xxxxxx)
- ffplay is used to play the video that is in the clipboard.                                        
  
- bc (already installed on most disrtros)  needed to do floating point math.
  
- notify-send (already installed on most disrtros) needed to display gui notifications.

 
  Videoinfox runs a dependency check at startup.  If any dependencies are Not Found, the script will exit.

  Videoinfox will display which dependencies are missing.

