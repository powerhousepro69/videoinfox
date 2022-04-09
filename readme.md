videoinfox v.1.96

For xserver - Find video files fast , get info on and play, Also, yt-dlp integration.

Install : Run the 2 lines below
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```


 Videoinfox Features:

 - Navigation was designed to be robust and efficient.
 - File types searched for:   .webm  .mp4  .mkv  .avi  .divx
 - Play videos and get video info from find result(s).
 - Copy one find result to the clipboard and press \<p\> to play.
 - Keep track of everything played >>> Played List
 - Save a list of videos from find result(s) >>> Saved Finds
 - Remove duplicates and put both lists in alphabetical order.
 - Press \<enter\> anywhere you see \<Clipboard:\> to update display.
 - Enter file with full path to play and get info.
 - Store last find result(s and autoload until deleted.
 - Yt-dlp integration for easy download and view.
 - Download and update both Videoinfox and Yt-dlp
 - Rapid directory changing by setting default directories.
 - Save directory state on exit to load on next run.
 - Change directory by entering full path.
 - Find directory and change to it by copying it to clipboard.
 - List video info one directory deep and save per directory.
 - Recursive count of videos broken down into video type.
 - Recursive duration. days:hrs:min:sec and save per directory.
 - GUI notifications.



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






