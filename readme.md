videoinfox v.1.99

For xserver - Find video files, get info on and play.  &nbsp; Yt-dlp integration.

To install &nbsp;: &nbsp;Run the 2 lines below
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```

<br />

 Videoinfox Features:

 - Navigation was designed to be robust and efficient.
 - File types searched for: &nbsp;   .webm &nbsp; .mp4 &nbsp; .mkv &nbsp; .avi &nbsp; .divx
 - Play videos and get video info from find result(s).
 - Copy one find result to the clipboard and press &nbsp; \<p\> &nbsp; to play.
 - Keep track of everything played &nbsp; >>> &nbsp; Played List
 - Save a list of videos from find result(s) &nbsp; >>> &nbsp; Saved Finds
 - Remove duplicates and put both lists in alphabetical order.
 - Press &nbsp; \<enter\> &nbsp; anywhere you see &nbsp; \<Clipboard:\> &nbsp; to update display.
 - Enter file with full path to play and get info.
 - Store last find result(s) and autoload until deleted.
 - Yt-dlp integration for easy download and view.
 - Download and update both Videoinfox and Yt-dlp
 - Rapid directory changing by setting default directories.
 - Save directory state on exit to load on next run.
 - Change directory by entering full path.
 - Find directory and change to it by copying it to clipboard.
 - List video info one directory deep.  Save per directory.
 - Recursive count of videos broken down into video type.
 - Recursive duration &nbsp; (days:hrs:min:sec) &nbsp; Save per directory.
 - GUI notifications.

Dependencies listed at bottom of page.

<br />

![Videoinfox HOME](https://i.imgur.com/YETFnPS.png)

![Videoinfox HOME](https://i.imgur.com/TJTPQBT.png)

![Videoinfox HOME](https://i.imgur.com/OnKZfEq.png)

![Videoinfox HOME](https://i.imgur.com/uoATDs3.png)







<br />
   
Dependencies:   
 
- xclip &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;paste feature.  xclip only works with Xsession  
- ffmpeg &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;extrat duration in &nbsp; (hrs:min:sec) &nbsp; format
- ffprobe &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;extract codec, resolution and duration in floating seconds format  &nbsp; (x.xxxxxx)
- ffplay &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; play video                                        
- bc &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; floating point math
- notify-send  &nbsp; &nbsp; &nbsp; display gui notifications

 <br />
 
Videoinfox runs a dependency check at startup.  If any dependencies are not found, the script will exit.
  
Any missing dependencies will be displayed.
  
  ![Videoinfox DEPENDENCY CHECK](https://i.imgur.com/WnjCTQe.png)

 <br />

  Setup for first the run or if the videoinfox directory gets deleted anytime after the first run.
  
  ![Videoinfox FIRST RUN](https://i.imgur.com/fP5DDnW.png)






