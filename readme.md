# Videoinfox v2.7.12 &nbsp; 

## *Where Video Play is a Clipboard Copy Away*

#### Find local Video Files fast, immediately play and get info on. Download Videos effortlessly and auto play.

#### Add URL's to the Default Download list on the fly without leaving your gui or starting up Videoinfox.

#### Create your own url download lists with your preferred text editor and load in Videoinfox to Download.

<br />


#### This update:  &nbsp; &nbsp; Bug Squashed: Download List.

Fix: &nbsp; After downloading a user list, the directory wasn't changing back to what is was before downloading list. 

<br />


### To install : &nbsp; &nbsp; Run the 2 lines below.
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```
<br />


Videoinfox is a Linux shell script that feels like an app. If you enjoy watching local videos on your PC and want the ability to download video url's, you won't be disappointed. You can also make your own URL lists to download. While downloading a list, a log file will be generated for each list. The log is each http link from your list with the downloaded video filename. If the download list is aborted before completion, Yt-dlp has you covered. Just run the Download List feature again. Yt-dlp won't re-download files that you already have. There is a Played List that keeps track of everything you played with the exception of the Play Directory feature. There is also a playlist you can create from search results or from directory listings. Videoinfox does all the error handling. You should never encounter any script errors.

Note: Played List and Playlist don't auto play yet, but will in the near future. Along with multiple playlist capability.

<br />

### Harnessing the power of:

Videoinfox - My contribution.

Xclip - Interact with the clipboard.

Yt-dlp - Download video urls.

FFplay - Play videos.

FFmpeg - Get duration in hh:min:sec

FFprobe - Get codec, resolution & duration in seconds.



<br />

### Videoinfox Features:


#### Navigation was designed to be robust and efficient. One keypress for all menu selections.

  - Check for update on startup and notifity if update is available.  Download and update in Videoinfox.
  - Play either a local file or a downloadable video url via yt-dlp.
  - Create Download List(s) with your preferred text editor & videoinfox will use yt-dlp to download the list.
  - Default List: &nbsp; Keep pasting Video URL's on the fly from the clipboard to the list without starting Videoinfox.
  - See codec, resolution and duration on the playing video.
  - Play Clipboard is available in: &nbsp; Home &nbsp; Played List &nbsp; Play List &nbsp; Yt-dlp Menu &nbsp; View Downloads
  - Play Clipboard: &nbsp; Blinking notification when there is a valid video file or video url for play.
  - Play Directory autoplay available on: &nbsp; Home Screen and in Navigate Tree.
  - Blinking &nbsp; Play Directory &nbsp; notification when there are video files in the current directory.
  - Navigate Tree  &nbsp;  Blinking &nbsp; Change Directory &nbsp; notification when there is a valid directory in the clipboard.
  - Video Player (ffplay) auto closes when the video ends.
  - Auto clear the clipboard after the video player is closed.
  - To watch the last download after Play Clipboard cleared the link select Last Download.
  - Auto clear the clipboard of invalid files and urls.
  - Press enter after your copy to the clipboard to validate clipboard content.
  - File types searched for:   .webm &nbsp; .mp4 &nbsp; .mkv &nbsp; .avi &nbsp; .divx 
  - Rapid directory changing by setting default directories in Settings. &nbsp; 4 available to set.  The 5th is dir at last exit.
  - Default Dirs - 1 2 3 4 5 &nbsp; directory switching available in: &nbsp; Home &nbsp; Navigate Tree &nbsp; Download List &nbsp; More Options
  - Played List: &nbsp; Keep track of everything played except for: &nbsp; Play Directory.
  - Playlist: &nbsp; Save a list of videos from find results and directory listing.
  - Remove duplicates from the Playlist and Played List.
  - Enter a video file with full path to get info on and play.
  - Auto save last find result(s) and autoload until deleted.  Defaulted to never save.  Can be changed in Settings.
  - Yt-dlp integration for easy download and play of single url's or entire lists.
  - Download Default: &nbsp; Yt-dlp with no arguments.  Download only.  No auto play.
  - Download Choose: &nbsp; Choose video type and qualiy before download.  Download only.  No auto play.
  - Self Destruct: &nbsp; Download, auto play, delete when the player is closed.
  - Last Download: &nbsp; Watch last download is available in: &nbsp; Home and Yt-dlp Menu.
  - Download List: &nbsp; Blinking notification on list load.
  - View Logs: &nbsp; Blinking notification on log load.
  - Default List companion: &nbsp; Create a gui shortcut for: &nbsp; videoinfox -a &nbsp; to add to the default list. 
  - Download and update Yt-dlp in Videoinfox.  
  - Save directory state on exit to load on next run.
  - Change directory by entering full path.
  - Find directory and change to it by copying it to clipboard.
  - List video info one directory deep. Save per directory.
  - Recursive count of videos broken down by video type.
  - Recursive duration (days:hrs:min:sec) Save per directory.
  - GUI notifications.


 
### To use Play Clipboard:

#### Copy a local file including full path to the clipboard and press  enter  to verify validity and  p  to play.
 
#### Copy a video url to the clipboard and press  enter  to verify validity and  p  to download and auto play.




<br />

** If videoinfox is removed, the directory  ~/.config/videoinfox  will have to be manually deleted.

#### Dependencies listed at bottom of page.

<br />
HOME SCREEN WITH A VIDEO URL IN THE CLIPBOARD. 

PRESS &nbsp; p &nbsp; TO DOWNLOAD AND AUTO PLAY FULLSCREEN. 
![Videoinfox HOME](https://i.imgur.com/bhl60L7.png)


<br />
PLAY CLIPBOARD

![Play Clipboard](https://i.imgur.com/JPGT8Cd.png)


<br />
PLAY DIRECTORY

![Play Directory](https://i.imgur.com/4sw8VR6.png)


<br />
OPTION TO QUIT PLAY DIRECTORY EVERYTIME A VIDEO ENDS OR THE VIDEO PLAYER IS QUIT.

![Play Directory](https://i.imgur.com/c6N5iJ3.png)


<br />
YT-DLP MENU

![Yt-dlp Menu](https://i.imgur.com/NRTL3H2.png)


<br />
DOWNLOAD LIST. USER CREATED URL LISTS OR THE DEFAULT LIST

![download list](https://i.imgur.com/a8RLhLv.png)


<br />
DEFAULT DOWNLOAD LIST.

ADD TO THE DEFAULT LIST WITHOUT LEAVING YOUR GUI OR STARTING VIDEOINFOX.
![Videoinfox HOME](https://i.imgur.com/vEIx5DB.png)


<br />
NAVIGATE TREE

![Navigate Tree](https://i.imgur.com/5pJMjgx.png)


<br />
FIND

![Videoinfox HOME](https://i.imgur.com/hwtyrdi.png)


<br />
PLAYLIST

![Videoinfox HOME](https://i.imgur.com/hpiQMqU.png)


<br />
MORE OPTIONS

![Videoinfox HOME](https://i.imgur.com/HXyfhCU.png)


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

![Videoinfox HOME](https://i.imgur.com/vun9YFS.png)


<br />
 
 YT-DLP is not on the dependeny list becuase Videoinfox will dowload it to: &nbsp; ~/.config/videoinfox &nbsp;
 All calls to yt-dlp are pointed to: &nbsp; ~/.config/videoinfox/yt-dlp &nbsp;
 There is an update option in: &nbsp; \<Set\>&nbsp; Settings to update yt-dlp &nbsp; (just the copy in ~/.config/videoinfox) &nbsp;
 I didn't want to overwrite anyones copy of: &nbsp; /user/local/bin/yt-dlp &nbsp;  &nbsp;
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


