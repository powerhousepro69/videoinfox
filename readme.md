videoinfox v.1.83

Not totally finished.  All the main features are fully functional.....  A few small things left to do.


![Videoinfox HOME (https://i.imgur.com/3xMvxpo.png)

![Videoinfox FIND RESULTS](https://i.imgur.com/GLtCUNR.png)

![Videoinfox FIND RESULTS](https://i.imgur.com/UGe9W4w.png)
  
![Videoinfox LIST DIRECTORY](https://i.imgur.com/EI8k4fC.png)                                                

![Videoinfox YT-DLP](https://i.imgur.com/ODPMA9K.png) 

![Videoinfox HELP](https://i.imgur.com/nKtJvZt.png) 


   
Dependencies:   
 
- xclip needed for autopaste feature.  xclip only works with Xsession
  
- ffmpeg is used to extrat Duration in <hrs:min:sec> format
- ffprobe is used to extract Codec, Resolution and Duration in floating seconds format (x.xxxxxx)
- ffplay is used to play the video that is in the clipboard.                                        
  
- bc (already installed on most disrtros)  needed to do floating point math.
  
- notify-send (already installed on most disrtros) needed to display gui notifications.


 
  Videoinfox runs a dependency check at startup.  If any dependencies are Not Found, the script will exit.
  
  Any dependencies that are missing will be displayed.

