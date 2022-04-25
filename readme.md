videoinfox v.2.062 &nbsp; Where Video Play Is A Clipboard Copy Away


Find local Video Files fast, immediately play and get info on.
Download Video Urls effortlessly and autoplay with Play Clipboard.

THIS UPDATE ADDED: Bug Squashed
<br />

LAST UPDATE v2.061 

Download List added to the Yt-dlp Menu

Create download list(s) of video urls with your preferred text editor.
                     
Then use Videoinfox to download the entire list with Yt-dlp.

The help located in:   Download List   explains how the download list feature works.






Added content to Help.


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
  - Download and update Videoinfox.
  - Play either a local file or a downloadable video url via yt-dlp.
  - Create Download List(s) of video urls with your preferred text editor & videoinfox will use yt-dlp to download the list.
  - See codec, resolution and duration on the playing video.
  - Play Clipboard available in:   -Home   -Played List   -Played List   -Yt-dlp menu   -View Downloads
  - Play Clipboard blinking notification when there is a valid video file or video url for play.
  - Play Directory autoplay on the Home Screen.
  - Navigate Tree blinking  Play Directory  notification when there are video files in the current directory.
  - Navigate Tree blinking  Change Directory  notification when there is a valid directory in the clipboard
  - Video Player (ffplay) auto closes when the video ends.
  - Auto clear the url link out of the clipboard after the video player is closed.
  - To watch the last download after Play Clipboard cleared the link select Last Download.
  - Auto clear the clipboard of invalid files and urls.
  - Press enter after your copy to the clipboard to validate clipboard content.
  - File types searched for :   .webm   .mp4   .mkv   .avi   .divx
  - Keep track of everything played except Play Directory.
  - Save a list of videos from find results and played list.
  - Remove duplicates from the playlist and played video.
  - Remove any entries from lists that don't start with a /
  - Enter a file with full path to play and get info. p
  - Auto save last find result(s) and autoload until deleted.
  - Yt-dlp integration for easy download and play.
  - Download video to play later.
  - Download Default - Yt-dlp with no arguments.
  - Download Choose  - Choose video type and qualiy before download.
  - Download completed, auto play, delete when the player is closed. (self Destruct)
  - Watch last download.
  - Download and update Yt-dlp.
  - Rapid directory changing by setting default directories.
  - Save directory state on exit to load on next run.
  - Change directory by entering full path.
  - Find directory and change to it by copying it to clipboard.
  - List video info one directory deep. Save per directory.
  - Recursive count of videos broken down by video type.
  - Recursive duration (days:hrs:min:sec) Save per directory.
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

If videoinfox is removed, the directory  ~/.config/videoinfox  will have to be manually deleted.

 Dependencies listed at bottom of page.

<br />
Home screen with Youtube link it the clipboard.&nbsp; &nbsp; Press&nbsp;  p &nbsp;to download and autoplay full screen.
 
![Videoinfox HOME](https://i.imgur.com/poQOxK9.png)

<br />
Play Clipboard

![Play Clipboard](https://i.imgur.com/TJTPQBT.png)

<br />
Yt-dlp Menu

![Yt-dpp Menu](https://i.imgur.com/NRTL3H2.png)

<br />
Yt-dlp Menu Download List
![Yt-dpp Menu](https://i.imgur.com/imGG5T6.png)





<br />
Find

![Videoinfox HOME](https://i.imgur.com/hwtyrdi.png)


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





