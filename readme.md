# Videoinfox v2.7.00 &nbsp; *Where Video Play is a Clipboard Copy Away*

#### Find local Video Files fast, immediately play and get info on. Download Video Urls effortlessly and auto play with Play Clipboard.

#### Add URL's to The Default Download List without leaving your gui or starting up Videoinfox.

#### Create your own url download list and Videoinfox will download the entire list with Yt-dlp.

<br />


#### This update:  &nbsp; &nbsp;  Changes, Additions and Bug Squashing.


Detailed information located in Version History in Settings &nbsp; (Set)




<br />


### To install : &nbsp; &nbsp; Run the 2 lines below.
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```
<br />


Videoinfox is a Linux shell script that feels like an app. If you enjoy watching local videos on your PC and want the ability to download video url's, you won't be disappointed. You can also make your own URL lists to download. While downloading a list, a log file will be generated for each list. The log is each http link from your list with the downloaded video filename. If the download list is aborted before completion, Yt-dlp has you covered. Just run the Download List feature again. Yt-dlp won't re-download files that you already have. There is a Played List that keeps track of everything you played with the exception of the Play Directory feature. There is also a playlist you can create from search results or from directory listings. Videoinfox does all the error handling. So you should never see any script errors.

Note: Played List and Playlist don't auto play yet, but will in the near future. Along with multiple playlist capability.

<br />

#### Harnessing the power of:

Videoinfox - My contribution.

Xclip - Interact with the clipboard.

Yt-dlp - Download video urls.

FFplay - Play videos.

FFmpeg - Get duration in hh:min:sec

FFprobe - Get codec, resolution & duration in seconds.



<br />

### Videoinfox Features:


#### Navigation was designed to be robust and efficient. One keypress for all menu selections.

  - Check for update on startup and notifity if update is available.
  - Download and update Videoinfox.
  - Play either a local file or a downloadable video url via yt-dlp.
  - Create Download List(s) of video urls with your preferred text editor & videoinfox will use yt-dlp to download the list.
  - Keep pasting your Video URL clipboard copies on the fly to the Default Download List without needing to startup Videoinfox.
  - See codec, resolution and duration on the playing video.
  - Play Clipboard available in: &nbsp; -Home &nbsp; -Played List &nbsp; -Play List &nbsp; -Yt-dlp Menu &nbsp; -View Downloads
  - Play Clipboard blinking notification when there is a valid video file or video url for play.
  - Play Directory autoplay on the Home Screen.
  - Navigate Tree blinking  Play Directory  notification when there are video files in the current directory.
  - Navigate Tree blinking  Change Directory  notification when there is a valid directory in the clipboard
  - Video Player (ffplay) auto closes when the video ends.
  - Auto clear the url link out of the clipboard after the video player is closed.
  - To watch the last download after Play Clipboard cleared the link select Last Download.
  - Auto clear the clipboard of invalid files and urls.
  - Press enter after your copy to the clipboard to validate clipboard content.
  - File types searched for:  &nbsp; .webm &nbsp; .mp4 &nbsp; .mkv &nbsp; .avi &nbsp; .divx
  - Keep track of everything played except Play Directory.
  - Save a list of videos from find results and directory listing.
  - Remove duplicates from the Playlist and Played List.
  - Enter a file with full path to get info on and play.
  - Auto save last find result(s) and autoload until deleted.
  - Yt-dlp integration for easy download and play.
  - Download video to play later.
  - Download Default - Yt-dlp with no arguments.
  - Download Choose  - Choose video type and qualiy before download.
  - Self Destruct - Download, auto play, delete when the player is closed.
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


 
### To use Play Clipboard:

#### Copy a local file including full path to the clipboard and press  enter  to verify the file is valid. Then  p  to Play Clipboard.
 
#### Copy a video url to the clipboard and press  enter  to verify the url is valid. Then  p  to Play Clipboard.




<br />

** If videoinfox is removed, the directory  ~/.config/videoinfox  will have to be manually deleted.

#### Dependencies listed at bottom of page.

<br />
HOME SCREEN WITH VIDEO URL IN THE CLIPBOARD. &nbsp; &nbsp; PRESS &nbsp;  p &nbsp; TO DOWNLOAD AND AUTO PLAY FULLSCREEN.
 
![Videoinfox HOME](https://i.imgur.com/poQOxK9.png)

<br />
PLAY CLIPBOARD & PLAY DIRECTORY

![Play Clipboard](https://i.imgur.com/TJTPQBT.png)

<br />
YT-DLP MENU

![Yt-dlp Menu](https://i.imgur.com/NRTL3H2.png)

<br />
DOWNLOAD USER CREATED URL LISTS

![download list](https://i.imgur.com/4qAtGII.png)

<br />
DEFAULT DOWNLOAD LIST. &nbsp; ADD TO THE DEFAULT LIST WITHOUT LEAVING YOUR GUI OR STARTING VIDEOINFOX. 

![Videoinfox HOME](https://i.imgur.com/UjmVJqs.png)

<br />
FIND

![Videoinfox HOME](https://i.imgur.com/hwtyrdi.png)


<br />
NAVIGATE TREE

![Navigate Tree](https://i.imgur.com/fWh8p4v.png)

<br />
PLAYLIST &nbsp; & PLAYED LIST

![Videoinfox HOME](https://i.imgur.com/hpiQMqU.png)


<br />
MORE OPTIONS

![Videoinfox HOME](https://i.imgur.com/j0V0PtJ.png)


<br />
LIST DIRECTORY

![Videoinfox HOME](https://i.imgur.com/kIMMech.png)

<br />
VIDEO COUNT

![Videoinfox HOME](https://i.imgur.com/ORPVFGz.png)

<br />
VIDEO DURATION

![Videoinfox HOME](https://i.imgur.com/03KxKlU.png)

<br />
FIND DIRECTORY

![Videoinfox HOME](https://i.imgur.com/WCHTlpd.png)

<br />
SETTINGS

![Videoinfox HOME](https://i.imgur.com/hrOdE5o.png)


<br />
 
 YT-DLP is not on the dependeny list becuase Videoinfox will dowload it to &nbsp; ~/.config/videoinfox &nbsp;
 All calls to yt-dlp are pointed to &nbsp; ~/.config/videoinfox/yt-dlp &nbsp;
 There is an update option in &nbsp; \<Set\>&nbsp; Settings to update yt-dlp &nbsp; (just the copy in ~/.config/videoinfox) &nbsp;
 I didn't want to overwrite anyones copy of &nbsp; /user/local/bin/yt-dlp &nbsp;  &nbsp;
 Also, I wanted to make sure all new Videoinfox script installs included the most recent version of Yt-dlp 
 
<br />
   
#### Dependencies:   
 
- xclip &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;copy and paste feature.  xclip only works with Xsession  
- ffmpeg &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;extrat duration in &nbsp; (hrs:min:sec) &nbsp; format
- ffprobe &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;extract codec, resolution and duration in floating seconds format  &nbsp; (x.xxxxxx)
- ffplay &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; play video                                        
- bc &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; floating point math
- notify-send  &nbsp; &nbsp; &nbsp; display gui notifications

 <br />
 
#### Videoinfox runs a dependency check at startup.  If any dependencies are not found, the script will exit.
  
#### Any missing dependencies will be displayed.

<br />
DEPENDENCIES
  
![Videoinfox DEPENDENCY CHECK](https://i.imgur.com/HjqIZqM.png)


<br />

#### Setup for first the run or if the videoinfox directory gets deleted anytime after the first run.

<br />
FIRST RUN

![Videoinfox FIRST RUN](https://i.imgur.com/IzaDGUs.png)


<br />

### Reddit /Videoinfox for discussion.


