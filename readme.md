videoinfox v.1.88

For linux xserver - Find Video Files fast , get info on and play, Also, yt-dlp integration.

Not totally finished.  All the main features are fully functional.....  A few small things left to do.


![Videoinfox HOME](https://i.imgur.com/3xMvxpo.png)

![Videoinfox PLAY VIDEO](https://i.imgur.com/GLtCUNR.png)

![Videoinfox YT-DLP](https://i.imgur.com/ODPMA9K.png)

![Videoinfox YT-DLP](https://i.imgur.com/7YidEDq.png)

![Videoinfox FIND RESULTS](https://i.imgur.com/UGe9W4w.png)
  
![Videoinfox LIST DIRECTORY](https://i.imgur.com/EI8k4fC.png)                                                

![Videoinfox CHANGE DIRECTORY](https://i.imgur.com/njHqbxP.png)

![Videoinfox FIND DIRECTORY](https://i.imgur.com/V5ZG8Mg.png)

![Videoinfox VIDEO COUNT](https://i.imgur.com/QchN9fi.png)

![Videoinfox DURATION](https://i.imgur.com/5C5VAFw.png)

![Videoinfox ENTER FILE](https://i.imgur.com/hnboxUn.png)

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
  
  ![Videoinfox DEPENDENCY CHECK](https://i.imgur.com/WnjCTQe.png) 

