# Videoinfox v3.9.00

## *Where Video Play is a Clipboard Copy Away*
<br />

### 100% Linux Shell Script. Videoinfox is one file under one megabyte.


#### Find local Video Files fast, immediately play and get info on. Download Videos effortlessly and auto play.

#### Add URL's to The Default Download list on the fly without leaving your gui or starting up Videoinfox.

#### Add URL's to Unlimited User Set Lists on the fly without leaving your gui or starting up Videoinfox.

#### Download all your video url lists with Videoinfox's Yt-dlp integration including a Download Queue.
<br />


### To install : &nbsp; &nbsp; Run the 2 lines below.
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```

** Features List and Screenshots below still need updated.

<br />
Download multiple URL User Lists simultaneously.

You have to start Download List first then run another instance of Videoinfox to start downloading the next list.
<br />

Videoinfox is a Linux shell script that feels like an app. If you enjoy watching local videos on your PC and want the ability to download video url's, you won't be disappointed. You can also make your own URL lists to download. While downloading a list, a log file will be generated for each list. The log is each http link from your list with the downloaded video filename. If the download list is aborted before completion, Yt-dlp has you covered. Just run the Download List feature again. Yt-dlp won't re-download files that you already have. There is a Played List that keeps track of everything played by Play Clipboard, Last Download and Play Line. The Playlist will never write to the Played List. Create unlimited Playlists and autoplay. Download Queue to add unlimited Videoinfox created User Download Lists for batch processing. Videoinfox does all the error handling and reporting.

#### Add videos to the Playlist from: 

- Search Results: &nbsp; Find for recursive searching and Show All for recursive directory listing.
                                 
- Directory Listings: &nbsp; Navigate Tree for current directory listing. 

- Directory To Playlist: &nbsp; Add all videos in the current directory to a new Playlist.

- Played List: &nbsp; Play Clipboard, Last Download and Play Line all write to the Played List.  

#### Create unlimited playlists.

<br />

### Harnessing the power of:

Videoinfox - Over 8200 lines of code.

Xclip - Interact with the clipboard.

Yt-dlp - Download video urls.

FFplay - Play videos.

FFmpeg - Get duration in hh:min:sec

FFprobe - Get codec, resolution & duration in seconds.



<br />

### Videoinfox Features:


#### Navigation was designed to be robust and efficient. One keypress for all menu selections.

  - Check for update on startup and notifity if update is available. Download and update in Videoinfox.
  - Play a local file by entering the line number. Play single video or autoplay the entire list.
  - Create unlimited Playlists from: Recusive search results, Recursive directory listings and the Played List
  - Play Clipboard: Blinking notification when there is a valid video url for play.
  - Play Clipboard: Download a video url that is in the clipboard via Yt-dlp and autoplay.
  - Play Clipboard is available in: Home  Played List  Play List  Yt-dlp Menu  View Downloads
  - See codec, resolution and duration on the playing video.
  - Play Directory autoplay available on: Home Screen, Navigate Tree and View Downloads.
  - Autoplay video files in the current directory with option to quit. videoinfox -d
  - Blinking Play Directory otification when there are video files in the current directory.
  - Navigate Tree Blinking Change Directory notification when there is a valid directory in the clipboard.
  - Navigate Tree with Play Directory autoplay and Play Line with autoplay. Select line number to start play.
  - Video Player (ffplay) auto closes when the video ends.
  - Auto clear the clipboard after the video player is closed.
  - To watch the last download after Play Clipboard cleared the link select Last Download.
  - Auto clear the clipboard of invalid files and urls.
  - Press enter after your copy to the clipboard to validate clipboard content.
  - File types searched for: .webm   .mp4   .mkv   .avi   .divx
  - Rapid directory changing by setting default directories (4) in Settings. The 5th is dir at last exit.
  - Default Dirs - 1 2 3 4 5  available in: Home  Navigate Tree  Download List  More Options
  - Play Line option. Only play the line number entered and write to Played List.
  - Autoplay Line option. Start autoplay from any line in the Played List by entering the line number.
  - Played List will keep track of everything played except for Play Directory and Autoplay Line.
  - Played List: Play All option that will auto play the entire list with option to quit.
  - Playlist: Save a list of videos from search results, directory listings and Played List.
  - Remove duplicates from the Playlist and Played List.
  - Enter a video file with full path to get info on and play.
  - Auto save last find result(s) and autoload until deleted. Defaulted to never save. Change in Settings.
  - Yt-dlp integration for easy download and play of single url's or entire lists.
  - Download Queue: Add unlimited Videoinfox User Download Lists to the queue for download.
  - Download Default: Yt-dlp with no arguments. Download only. No auto play.
  - Download Choose: Choose video type and quality before download. Download only. No auto play.
  - Self Destruct: Download, auto play, delete when the player is closed.
  - Last Download in: Home and Yt-dlp Menu for: Play Clipboard, Download Default and Download Choose.
  - Download List: Blinking notification on list load.
  - View Logs: Blinking notification on log load.
  - Default List: Keep pasting Video URL's on the fly from the clipboard to the Default List.
  - Default List companion: Create a gui shortcut for: videoinfox -a  to add to the Default List.
  - Unlimited User Lists: Keep pasting Video URL's on the fly from the clipboard to the User Set List.
  - User Set List companion: Create a gui shortcut for: videoinfox -l  to add to the User Set list.
  - Download any list. Any name and location. No need to use the Videoinfox interface: videoinfox -u listname
  - Download and update Yt-dlp in Videoinfox.
  - Save directory state on exit to load on next run.
  - Change directory by entering full path.
  - Find directory and change to it by copying it to clipboard.
  - List video info one directory deep. Save per directory.
  - Recursive count of videos broken down by video type.
  - Recursive duration (days:hrs:min:sec) Save per directory.
  - GUI notifications.
  - More features . . .


 
### To use Play Clipboard:

 
#### Copy a video url to the clipboard then press enter to verify validity then &nbsp; p &nbsp; to download and auto play.



<br />

#### Dependencies listed at bottom of page.



<br />
HOME SCREEN WITH A VIDEO URL IN THE CLIPBOARD. 

PRESS &nbsp; p &nbsp; TO DOWNLOAD AND AUTO PLAY FULLSCREEN. 
![Videoinfox HOME](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/HOME.png)


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
DOWNLOAD LIST MENU WITH DOWNLOAD QUEUE

CREATE USER LISTS AND ADD URL'S TO THEM WITHOUT LEAVING YOUR GUI OR STARTING VIDEOINFOX.

![download list menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/download-list.png)


<br />
DEFAULT DOWNLOAD LIST.

ADD TO THE DEFAULT LIST WITHOUT LEAVING YOUR GUI OR STARTING VIDEOINFOX.
![Videoinfox download list help](https://i.imgur.com/vEIx5DB.png)


<br />
DEFAULT DOWNLOAD LIST HELP.

![Videoinfox Download list help 2](https://i.imgur.com/LPNoA47.png)


<br />
USER LIST HELP.

![Videoinfox User List help](https://i.imgur.com/nHBamaY.jpg)


<br />
NAVIGATE TREE WITH PLAY DIRECTORY, AUTOPLAY PLAY AND PLAY LINE

![Navigate Tree](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/navigate-tree.png)


<br />
NAVIGATE TREE >>> AUTOPLAY LINE. &nbsp; START AUTOPLAY FROM ANY LINE BY ENTERING THE LINE NUMBER.

![Navigate Tree Play Line](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/navigate-tree-autoplay-line.png)


<br />
FIND VIDEOS TO PLAY OR GET INFO.

SELECT PLAY NUMBER AND ENTER THE NUMBER THAT YOU WANT TO PLAY.

![Videoinfox Find](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/find.png)


<br />
PLAYED LIST

![Videoinfox Played List](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/playedlist.png)


<br />
PLAYLIST

![Videoinfox Playlist](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/playlist.png)


<br />
MORE OPTIONS

![Videoinfox More Options](https://i.imgur.com/HXyfhCU.png)


<br />
LIST DIRECTORY

![Videoinfox List Directory](https://i.imgur.com/kIMMech.png)

<br />
VIDEO COUNT

![Videoinfox Video Count](https://i.imgur.com/ORPVFGz.png)

<br />
VIDEO DURATION

![Videoinfox Duration](https://i.imgur.com/03KxKlU.png)

<br />
FIND DIRECTORY

![Videoinfox Find Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/find-directory.png)

<br />
SETTINGS

![Videoinfox Settings](https://i.imgur.com/vun9YFS.png)

<br />
videoinfox -h

![videoinfox -h](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/videoinfox-h.png)

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


#### Privacy Policy: &nbsp; Videoinfox will never collect or attempt to transmit any information on it's users.

     Internet activity will only happen under the following circumstances:

      - On First Run, Github will be contacted to download Yt-dlp.
      - On every start, Github will be contacted to download Videoinfox for Update Available Check.
      - Everytime Videoinfox Update or Yt-dlp Update is selected in Settings, Github will be contacted.
      - If there isn't a copy of Yt-dlp in Videoinfox's config directory, Github will be contacted
        everytime you select the Yt-dlp Menu to attempt a download of Yt-dlp.
      - Everytime Yt-dlp is used to download a video url.
        Refer to Yt-dlp's site for their privacy policy. https://github.com/yt-dlp/yt-dlp



** If videoinfox is removed, the directory  ~/.config/videoinfox  will have to be manually deleted.
<br />

##### Reddit /Videoinfox for discussion.
<br />

###  v3.9.02 Fix: Option display in View Playlist with a valid http video link in the clipboard.

         Fix: Resume Autoplay would error on a new Playlist without initially running Start Autoplay.

         Added below line to Playlist >>> Help
         When Resume Autoplay reaches the end of the playlist, it will remain there until Start Autoplay is run again.

###  v3.9.00 View Playlist appearance update + new options in View Playlist and Navigate Tree >>> Show All.

         Add: Start Autoplay in View Playlist saves the last played video to Resume Autoplay.
              Resume Autoplay will also save the last played video.
              ** Use Start Autoplay first to begin watching **
              ** Use Resume Autoplay after to continue watching and keep track of where you left off in the playlist **
              More info. located in View Playlist >>> Help 

         Add: Delete Line in View Playlist. Delete line number entered from the playlist.

         Add: Directory To Playlist in Navigate Tree >>> Show All.
              This option will write a one level deep directory listing to a new playlist.
              Good for creating a tv show season number x playlist.

         Change: All blinking  -  changed to non blinking  ~  everywhere except the Yt-dlp Menu
                 ** This will be updated in the Yt-dlp Menu along with selection by number instead of clipboard copy.

         Change: Home Screen, Played List and Playlist
                 Clipboard: is hidden if there isn't a valid video url available in the clipboard.

         Fix: Home Screen >>> View Playlist
              After using Play Clipboard, the user set directory wasn't being restored on quit to home screen.

         Fix: View Playlist >>> Change Playlist
              The playlist name display wasn't updating if the loaded playlist was deleted.
              Note: If the loaded playlist is deleted, the default playlist will be loaded.

         Note: The loaded playlist is auto saved when another playlist is loaded.


<br />

 Note: There are only 2 areas left in Videoinfox that still use the clipboard feature.

       1. More Options >>> Find Directory

       2. Yt-dlp Menu >>> Download List

       - Download List     - Set User List
       - View List
       - View Logs         - Delete User List     - Add to Queue

 The above will all eventually be converted over from clipboard copy to line number for all selections.
 Once that is finished, the only time the clipboard feature will be used is in the gui. Copying video
 url's to the clipboard to download or when building a download list with a videoinfox keyboard shortcut.


<br />

![Code Stats](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/code-stats.png)


