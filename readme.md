videoinfox v.2.00

MOST SREENSHOTS BELOW STILL NEEED UPDATED TO v.2.00 THE FIRST PICTURE HAS BEEN UPDATED.

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
<br />

 - Navigation was designed to be robust and efficient. One keypress for all menu selections.
<br />

 - Press &nbsp; Enter &nbsp; after copying a local filename or link to the clipboard to update display. Available system wide.
<br />


 - Play Clipboard can play either a local file or a downloadable video url via yt-dlp.
 - Play Clipboard will also give you codec, resolution and duration on the playing video. 
 - Play Clipboard is available in: &nbsp;\<HOME\> &nbsp;\<Playlist\> &nbsp;\<Played List\>
 - Play Clipboard will clear the url link out of the clipboard after you close the player.
 - To watch the last download after Play Clipboard cleared the link, select Last Download available in: &nbsp;\<HOME\> &nbsp;\<YT-DLP\>
 <br />
 
 - Copy a local file including full path to the clipboard then press &nbsp; p &nbsp; to Play Clipboard.
   <br />
   
 - Copy a video url to the clipboard and press &nbsp; enter &nbsp; for yt-dlp to extract video name  then press &nbsp; p &nbsp; to Play Clipboard. 
  <br />
 
 - (next version release will include Play Clipboard in &nbsp; \<YT-DLP\> &nbsp; and &nbsp; \<View Downloads\>
 
 <br />
 
 - File types searched for :&nbsp; &nbsp; .webm &nbsp; .mp4 &nbsp; .mkv &nbsp; .avi &nbsp; .divx
  <br />
  
 - Keep track of everything played &nbsp; \<PLAYED LIST\>
 - Save a list of videos from find result(s) &nbsp;\<PLAYLIST\>
 - Remove duplicates from the playlist and played video.
 - Remove any entries from lists that don't start with a &nbsp;\/
 - Enter a file with full path to play and get info. \&nbsp;<Enter Video File\>
 - Auto save last find result(s) and autoload until deleted.
 - Yt-dlp integration for easy download and play.
 - Download video and play later. &nbsp;\<YT-DLP\>
 - Download completed, auto play, delete when the player is closed. &nbsp;\<YT-DLP\>
 - Play last download &nbsp;\<YT-DLP\>
 - Pick file type and quality of video before download. &nbsp;\<YT-DLP\>
 - Download and update Videoinfox. &nbsp;\<SET\>
 - Download and update Yt-dlp. &nbsp;\<SET\>
 - Rapid directory changing by setting default directories. &nbsp;\<SET\>
 - Save directory state on exit to load on next run.
 - Change directory by entering full path. <CHANGE DIRECTORY>
 - Find directory and change to it by copying it to clipboard. <FIND DIRECTORY>
 - List video info one directory deep. Save per directory. <LIST DIRECTORY>
 - Recursive count of videos broken down by video type. <VIDEO COUNT>
 - Recursive duration (days:hrs:min:sec) Save per directory. <VIDEO DURATION>
 - GUI notifications.
<br />


Dependencies listed at bottom of page.

<br />
Home screen with Youtube link it the clipboard.&nbsp; &nbsp; Press&nbsp;  p &nbsp;to play
 
![Videoinfox HOME](https://i.imgur.com/VUgw7eE.png)

<br />
Play Clipboard

![Videoinfox HOME](https://i.imgur.com/TJTPQBT.png)

<br />
Find

![Videoinfox HOME](https://i.imgur.com/OnKZfEq.png)



<br />
Yt-dlp Menu

![Videoinfox HOME](https://i.imgur.com/DphLvOL.png)

<br />
Playlist&nbsp; (also Played List)

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

![Videoinfox FIRST RUN](https://i.imgur.com/QB9Ykax.png)





