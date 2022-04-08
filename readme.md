videoinfox v.1.91

For xserver - Find Video Files fast , get info on and play, Also, yt-dlp integration.

Install : Run the 2 lines below
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```
Dependencies listed at bottom

![Videoinfox HOME](https://i.imgur.com/3xMvxpo.png)

![Videoinfox PLAY VIDEO](https://i.imgur.com/GLtCUNR.png)

![Videoinfox YT-DLP](https://i.imgur.com/ODPMA9K.png)

![Videoinfox YT-DLP UPDATE](https://i.imgur.com/OBwTttB.png)

![Videoinfox FIND RESULTS](https://i.imgur.com/UGe9W4w.png)
  
![Videoinfox LIST DIRECTORY](https://i.imgur.com/EI8k4fC.png)                                                

![Videoinfox CHANGE DIRECTORY](https://i.imgur.com/njHqbxP.png)

![Videoinfox FIND DIRECTORY](https://i.imgur.com/V5ZG8Mg.png)

![Videoinfox VIDEO COUNT](https://i.imgur.com/QchN9fi.png)

![Videoinfox DURATION](https://i.imgur.com/5C5VAFw.png)

![Videoinfox ENTER FILE](https://i.imgur.com/hnboxUn.png)

![Videoinfox HELP](https://i.imgur.com/9wsPGkU.png) 




   
Dependencies:   
 
- xclip .......... (paste feature.  xclip only works with Xsession)
  
- ffmpeg ......... (extrat Duration in <hrs:min:sec> format)
- ffprobe ........ (extract Codec, Resolution and Duration in floating seconds format (x.xxxxxx))
- ffplay ......... (play the video that is in the clipboard.)                                        
  
- bc ............. (floating point math.)
  
- notify-send .... (display gui notifications.)


 
  Videoinfox runs a dependency check at startup.  If any dependencies are Not Found, the script will exit.
  
  Any dependencies that are missing will be displayed.
  
  ![Videoinfox DEPENDENCY CHECK](https://i.imgur.com/WnjCTQe.png)
  
  Directory and file creation for first the run or if the videoinfox directory gets deleted anytime after the first run.
  
  ![Videoinfox FIRST RUN](https://i.imgur.com/fP5DDnW.png)






