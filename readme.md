# Videoinfox v4.2.13

### *Where video download and play is a clipboard copy away . . .*

![Videoinfox HOME](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/HOME.png)

### 100% Linux Shell Script. Videoinfox is one file under one megabyte.

Find local Video Files fast, immediately play and get info on. Download Videos effortlessly and autoplay.
Add URL's to unlimited User Set Lists on the fly without leaving the browser. Download all your video url lists
with Videoinfox's Yt-dlp integration including a Download Queue. Watch videos with (default) ffplay, mpv or
any video player.
<br />


### To install : &nbsp; &nbsp; Run the 2 lines below.
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```
<br />

#### NEW in v4.2.12 &nbsp; Add: -Download Only on Home Screen. Download a video url that is in the clipboard.
#### NEW in v4.2.11 &nbsp; Add: -Make Playlist on Home Screen. Save all search results as a Playlist.
#### NEW in v4.2.00 &nbsp; Added Playlist Queue. Added Intermission in Settings + more options.
#### NEW in v4.1.00 &nbsp; All keyboard driven. No more copying screen results to the clipboard.

<br />
Download multiple URL User Lists simultaneously.

You have to start Download List first then run another instance of Videoinfox to start downloading the next list.
<br />

Videoinfox is a Linux shell script that feels like an app. If you enjoy watching local videos on your PC and want the ability to download video url's, you won't be disappointed. You can also make your own URL lists to download. While downloading a list, a log file will be generated for each list. The log is each http link from your list with the downloaded video filename. If the download list is aborted before completion, Yt-dlp has you covered. Just run the Download List feature again. Yt-dlp won't re-download files that you already have. There is a Played List that keeps track of everything played by Play Clipboard, Last Download and Play Line. The Playlist will never write to the Played List. Create unlimited Playlists and autoplay. Download Queue to add unlimited Videoinfox created User Download Lists for batch processing. Videoinfox does all the error handling and reporting.

#### Create unlimited playlists. Add videos to the Playlist from: 

- Add to Playlist: Search Results. &nbsp; Find for recursive searching and Show All for recursive directory listing.

- Make Playlist on Home Screen. Save all search results as a Playlist.

- Add to Playlist: Directory Listings. &nbsp; Navigate Tree >>> Show All for one level deep directory listing. 

- Directory to Playlist in Navigate Tree >>> Show All &nbsp; Add all videos in the current directory to a new Playlist.

- Queue to Playlist in Play Queue to save the queue as a playlist.

- Add to Playlist: Played List. &nbsp; Play Clipboard, Last Download and Play Line all write to the Played List.  

#### Start Autoplay on a playlist from the beginning to the end of the list or Start Autoplay from anywhere in the list and play to the end of the list. Resume Autoplay will start with last the video that was playing on Start Autoplay quit. Resume Autoplay will also keep track of the last video that was playing on quit.

<br />

### Harnessing the power of:

Videoinfox - Over 8400 lines of code.

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
  - Directory To Playlist: Create a new playlist from a 1 level deep dir listing. Good for seasons of TV shows.
  - Playlist Queue to load unlimited playlists for autoplay with last played video marker.
  - Queue to Playlist: Save the Playlist Queue to a Playlist. 
  - Play Clipboard: Download a video url that is in the clipboard via Yt-dlp and autoplay.
  - Play Clipboard is available in: Home  Played List  Play List  Yt-dlp Menu  View Downloads
  - See codec, resolution and duration on the playing video.
  - Play Directory autoplay available on: Home Screen, Navigate Tree and View Downloads.
  - Set Intermission time in seconds. Change the time in seconds on video end/player quit. Initially set to 10.
  - Command Line Option: Autoplay video files in the current directory with option to quit. videoinfox -d
  - Navigate Tree with Play Directory, Play and Autoplay. Select line number to start play.
  - Video Player auto closes when the video ends. Ffplay is used by default. Any video player can be used.
  - Auto clear the video url from clipboard after the video player is closed.
  - To watch the last download after Play Clipboard cleared the link select Last Download.
  - Auto clear the clipboard of invalid video urls.
  - Press enter after your copy to the clipboard to validate clipboard content.
  - File types searched for: .webm   .mp4   .mkv   .avi   .divx
  - Rapid directory changing by setting default directories (4) in Settings. The 5th is dir at last exit.
  - Default Dirs - 1 2 3 4 5  available in: Home  Navigate Tree  Download List  More Options
  - Played List: log everything played except for: Play Directory, Autoplay, and anything played from a Played List.  
  - Played List: Play All option that will auto play the entire list with option to quit.
  - Duplicates auto-removed from the Played List.
  - Playlist: Save a list of videos from search results, directory listings and Played List.
  - Remove duplicates from the Playlist.
  - Enter a video file with full path to get info on and play.
  - Auto save last find result(s) and autoload until deleted. Defaulted to never save. Change in Settings.
  - Yt-dlp integration for easy download and play of single url's or entire lists.
  - Download Queue: Add unlimited Videoinfox User Download Lists to the queue for download.
  - Download Default: Yt-dlp with no arguments. Download only. No auto play.
  - Download Choose: Choose video type and quality before download. Download only. No auto play.
  - Self Destruct: Download, auto play, delete when the player is closed.
  - Last Download in: Home and Yt-dlp Menu for: Play Clipboard, Download Default and Download Choose.
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
  - + more options . . .


 
### To use Play Clipboard:

 
#### Copy a video url to the clipboard then press enter to verify validity then &nbsp; p &nbsp; to download and auto play.


<br />

#### Dependencies listed at bottom of page.

<br />
PLAY DIRECTORY

Autoplay directory one level deep.

![Play Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAY-DIRECTORY.png)


<br />
OPTION TO QUIT A WHEN A VIDEO ENDS OR THE VIDEO PLAYER IS QUIT.

Applies to Play Directory, Autoplay, Start Autoplay and Resume Autoplay

![Quit Play Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PD-QUIT.png)


<br />
YT-DLP MENU

Download video url in clipboard or download and autoplay with Play Clipboard

![Yt-dlp Menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/YT-DLP-MENU.png)


<br />
DOWNLOAD LIST MENU WITH DOWNLOAD QUEUE

1. Create unlimited user lists. Add video url's to the list from the clipboard without leaving the browser.
   
   (Copy the url to clipboard then add video url to a user set list with the videoinfox -l gui keyboard shortcut.)

2. Download single list or load unlimited user lists into the download queue for batch download.

![download list menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DOWNLOAD-LIST.png)


<br />
DEFAULT DOWNLOAD LIST

Copy the url to clipboard then add video url to to the default list in videoinfox

or stay in your browser and add url with the videoinfox -a gui keyboard shortcut.

![Videoinfox download list help](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DEFAULT-LIST.png)


<br />
NAVIGATE TREE

![Navigate Tree](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/NAVIGATE-TREE.png)

<br />
FIND DIRECTORY

![Videoinfox Find Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/FIND-DIRECTORY.png)


<br />
NAVIGATE TREE >>> SHOW ALL with Autoplay, Play, Directory To Playlist and Playlist Add

![NT Show All](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/NT-SHOW-ALL.png)


<br />
FIND VIDEOS TO Play, Autoplay, Playlist Add or get Info

![Videoinfox Find](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/FIND.png)


<br />
VIEW PLAYLIST

![Videoinfox Playlist](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAYLIST.png)


<br />
VIEW PLAYLIST -Change and Queue

![Videoinfox Change and Queue](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/CHANGEANDQUEUE.png)


<br />
VIEW PLAYLIST -Change and Queue -Play Queue

![Videoinfox Play Queue](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAYQUEUE.png)


<br />
MORE OPTIONS

![Videoinfox More Options](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/MORE-OPTIONS.png)


<br />
LIST DIRECTORY

![Videoinfox List Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/LIST-DIRECTORY.png)

<br />
VIDEO COUNT

![Videoinfox Video Count](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/VIDEO-COUNT.png)

<br />
VIDEO DURATION

![Videoinfox Duration](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/VIDEO-DURATION.png)


<br />
SETTINGS

![Videoinfox Settings](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/SETTINGS.png)

<br />
videoinfox -h

![videoinfox -h](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/VIDEOINFOX-H.png)

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
  
![Videoinfox DEPENDENCY CHECK](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DEPENDENCY.png)


<br />

#### Setup for first the run or if the videoinfox directory gets deleted anytime after the first run.

<br />
FIRST RUN

![Videoinfox FIRST RUN](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/FIRST-RUN.png)
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

###  v4.2.13 Fix: Custom player settings now available to videoinfox -d

          Edit: Help in videoinfox -h, Home Help and View Playlist Help

###  v4.2.12 Add: -Download Only on Home Screen. Download a video url that is in the clipboard.

          -Download Only is the same as Download Default in Yt-dlp Menu.

###  v4.2.11 Add: -Make Playlist on Home Screen. Save all search results as a Playlist.

          Add: -Find Dir on Home Screen.

          Edit: Home Help.
  
###  v4.2.04 Change: Another edit in Quit message on video end/player quit in -Play Directory and Autoplay.

###  v4.2.03 Change: Quit message on video end/player quit in -Play Directory and Autoplay.

###  v4.2.02 Add: added message to Home -Find if there are no video files.
    
          MSG: No video files recursively reachable from the current directory . . .

          Change: View Playlist options: -Remove Line -Remove Duplicates -Clear Playlist all autosave the changes.
          Before this change the active playlist was only saved when selecting option -Change Playlist


###  v4.2.00 Playlist Queue added. Load unlimied playlists into the queue for autoplay with last played video marker.

          >>> View Playlist option: -Change Paylist was renamed to -Change and Queue.
          
          New Options in -Change and Queue:     -Add to Queue     -Queue List     -Play Queue.

          Queue List options:     g - Remove Duplicate Playlists     r - Rewrite Queue With Current List     d - Delete Queue

          Play Queue options:     j - Play     o - Start Autoplay      z - Queue to Playlist     r - Remove Line
                                  i - Info     l - Resume Autoplay                               g - Remove Duplicates
                                                                                                 d - Delete Queue

         Add: -Remove Duplictes added to >>> View Playlist. Duplicates were auto-removed. Now they are not.

         Add: -Find Directory added to YT-DLP MENU >>> DOWNLOAD LIST -Create/Change Directory

         Add: -Intermission option in Settings. Change the time in seconds on video end/player quit. Initially set to 10.

         Change: in FIRST RUN >>> SETUP Timeout changed to Press enter to continue . . . . . .

         Fix: -Set -Videoinfox Update. Directory wasn't being restored on -Update

<br />



![Code Stats](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/CODE-STATS.png)


