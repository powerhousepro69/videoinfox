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

 - Navigation was designed to be robust and efficient. One keypress for all menu selections.
 - Copy a filename to the clipboard and press \<p\> to play.
 - Play clipboard:  &nbsp; &nbsp;\<HOME\> &nbsp;\<PLAYLIST\> &nbsp;\<PLAYED LIST\> &nbsp;\<FIND\> &nbsp;\<YT-DLP\>
 - File types searched for :&nbsp; &nbsp; .webm &nbsp; .mp4 &nbsp; .mkv &nbsp; .avi &nbsp; .divx
 - Play videos and get video info from every screen that has a play feature.
 - Keep track of everything played \<PLAYED LIST\>
 - Save a list of videos from find result(s) \<PLAYLIST\>
 - Remove duplicates from the playlist and played video.
 - Remove any entries from lists that don't start with a &nbsp;\/
 - Press  \<enter\>  anywhere you see  \<Clipboard:\>  to update display.
 - Enter a file with full path to play and get info. \<Enter Video File\>
 - Auto save last find result(s) and autoload until deleted.
 - Yt-dlp integration for easy download and play.
 - Download video and autoplay \<HOME\>
 - Download video and play later. \<YT-DLP\>
 - When download has completed, auto play, delete when the player is closed. \<YT-DLP\>
 - Play last download \<YT-DLP\>
 - Pick type and quality of video before download. \<YT-DLP\>
 - Download and update Videoinfox. \<SET\>
 - Download and update Yt-dlp. \<SET\>
 - Rapid directory changing by setting default directories. \<SET\>
 - Save directory state on exit to load on next run.


Dependencies listed at bottom of page.

<br />
Home

![Videoinfox HOME](https://i.imgur.com/YETFnPS.png)

<br />
Play Clipboard

![Videoinfox HOME](https://i.imgur.com/TJTPQBT.png)

<br />
Find

![Videoinfox HOME](https://i.imgur.com/OnKZfEq.png)

<br />
Home (with http link)

![Videoinfox HOME](https://i.imgur.com/uoATDs3.png)

<br />
Yt-dlp Menu

![Videoinfox HOME](https://i.imgur.com/DphLvOL.png)

<br />
Playlist

![Videoinfox HOME](https://i.imgur.com/hpiQMqU.png)

<br />
List Directory

![Videoinfox HOME](https://i.imgur.com/kIMMech.png)

<br />
Video Count

![Videoinfox HOME](https://i.imgur.com/ORPVFGz.png)

<br />
Video Duration

![Videoinfox HOME](https://i.imgur.com/03KxKlU.png)

<br />
Find Directory

![Videoinfox HOME](https://i.imgur.com/WCHTlpd.png)

<br />
Settings

![Videoinfox HOME](https://i.imgur.com/VluP7RZ.png)


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

<br />
Dependencies
  
![Videoinfox DEPENDENCY CHECK](https://i.imgur.com/Sfe8ol0.png)

<br />
Setup for first the run or if the videoinfox directory gets deleted anytime after the first run.
<br />
<br />
First Run

![Videoinfox FIRST RUN](https://i.imgur.com/oE8qeqA.png)






