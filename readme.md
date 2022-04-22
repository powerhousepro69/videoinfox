videoinfox v.2.056 &nbsp; Where Video Play Is A Clipboard Copy Away


Find local Video Files fast, immediately play and get info on.
Download Video Urls effortlessly and autoplay with Play Clipboard.

THIS UPDATE ADDED:  missing features in Navigate Tree

- Clipboard content is now saved when entering Navigate Tree and restored on quit.

- Total Files: (recursive) was added to the display.

- When navigating in or out of a directory, 
  Play Directory will blink when video files are available in the current directory.
 <br />
 
- Yt-dlp menu - Clear clipboard after download.
 <br />


Note:  Screenshots below need updated.



 <br />

To install &nbsp;: &nbsp;Run the 2 lines below.
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```
<br />

Download feature wouldn't have been possible without YT-DLP
<br /> 
Play Clipboard voodoo wouldn't have been possible without XCLIP
<br />

Videoinfox Features:


- Navigation was designed to be robust and efficient. One keypress for all menu selections.
- Check for update on startup and notifity if update is available.
- Play either a local file or a downloadable video url via yt-dlp.
- See codec, resolution and duration on the playing video.
- Play Clipboard available in: &nbsp; -Home &nbsp; -Played List &nbsp; -Played List &nbsp; -Yt-dlp menu &nbsp; -View Downloads
- Play Directory with autoplay on Home Screen.
- Navigate Tree with Play Directory notification when there are video files in the current directory.
- Video Player (ffplay) auto closes when the video ends.
- Auto clear the url link out of the clipboard after the video player is closed.
- To watch the last download after Play Clipboard cleared the link select Last Download  <Home> <Yt-dlp>
- Auto clear the clipboard of invalid files and urls.
- Press enter after your copy to the clipboard to validate clipboard content.
- File types searched for : &nbsp; .webm  &nbsp; .mp4 &nbsp; .mkv &nbsp; .avi &nbsp; .divx
- Keep track of everything played  <Played List>
- Save a list of videos from find results and played list  <Play List>
- Remove duplicates from the playlist and played video.
- Remove any entries from lists that don't start with a  /
- Enter a file with full path to play and get info. p  <Video File>
- Auto save last find result(s) and autoload until deleted.
- Yt-dlp integration for easy download and play.  <Yt-dlp>
- Download video to play later.   <Download Video>
- Pick file type and quality of video before download.  <Download Video>
- Download completed, auto play, delete when the player is closed. <Self Destruct>
- Watch last download <Last Download>
- Download and update Videoinfox. <Set>
- Download and update Yt-dlp. <Set>
- Rapid directory changing by setting default directories. <Set>
- Save directory state on exit to load on next run.
- Change directory by entering full path. <Change Directory>
- Find directory and change to it by copying it to clipboard.  <Find Directory>
- List video info one directory deep. Save per directory. <List Directory>
- Recursive count of videos broken down by video type.  <Video Count>
- Recursive duration (days:hrs:min:sec) Save per directory.  <Video Duration>
- GUI notifications.



 
To use Play Clipboard:

Copy a local file including full path to the clipboard and press  enter  to verify the file is valid.
Then  p  to Play Clipboard.
 
Copy a video url to the clipboard and press  enter  to verify the url is valid.
Then  p  to Play Clipboard.

Note: Pressing  enter  after content is copied to the clipboard isn't required before pressing  p
      It is just to vaidate the clipboard content for the display.
      You can also copy to the clipboard and select  p  without needing  enter.
      This feature will auto clear invalid clipboard content.
<br />
If videoinfox is removed, the dircetory  ~/.config/videoinfox  will have to be manually deleted.

 Dependencies listed at bottom of page.

<br />
Home screen with Youtube link it the clipboard.&nbsp; &nbsp; Press&nbsp;  p &nbsp;to download and autoplay full screen.
 
![Videoinfox HOME](https://i.imgur.com/VUgw7eE.png)

<br />
Play Clipboard

![Play Clipboard](https://i.imgur.com/TJTPQBT.png)

<br />
Find

![Videoinfox HOME](https://i.imgur.com/OnKZfEq.png)



<br />
Yt-dlp Menu

![Videoinfox HOME](https://i.imgur.com/DphLvOL.png)

<br />
Playlist &nbsp; (also Played List)

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
 
 YT-DLP is not on the dependeny list becuase Videoinfox will dowload it to &nbsp; ~/.config/videoinfox &nbsp;
 All calls to yt-dlp are pointed to &nbsp; ~/.config/videoinfo/yt-dlp &nbsp;
 There is an update option in &nbsp; \<Set\>&nbsp; Settings to update yt-dlp &nbsp; (just the copy in ~/.config/videoinfox) &nbsp;
 I didn't want to overwrite anyones copy of &nbsp; /user/local/bin/yt-dlp &nbsp;  &nbsp;
 Also, I wanted to make sure all new Videoinfox script installs included the most recent version of Yt-dlp 
 
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





