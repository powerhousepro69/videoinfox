# Videoinfox v4.1.31

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


#### NEW in v4.1.00 &nbsp; All keyboard driven. No more copying screen results to the clipboard.


<br />
Download multiple URL User Lists simultaneously.

You have to start Download List first then run another instance of Videoinfox to start downloading the next list.
<br />

Videoinfox is a Linux shell script that feels like an app. If you enjoy watching local videos on your PC and want the ability to download video url's, you won't be disappointed. You can also make your own URL lists to download. While downloading a list, a log file will be generated for each list. The log is each http link from your list with the downloaded video filename. If the download list is aborted before completion, Yt-dlp has you covered. Just run the Download List feature again. Yt-dlp won't re-download files that you already have. There is a Played List that keeps track of everything played by Play Clipboard, Last Download and Play Line. The Playlist will never write to the Played List. Create unlimited Playlists and autoplay. Download Queue to add unlimited Videoinfox created User Download Lists for batch processing. Videoinfox does all the error handling and reporting.

#### Create unlimited playlists. Add videos to the Playlist from: 

- Search Results: &nbsp; Find for recursive searching and Show All for recursive directory listing.
                                 
- Directory Listings: &nbsp; Navigate Tree for one level deep directory listing. 

- Directory To Playlist: &nbsp; Add all videos in the current directory to a new Playlist.

- Played List: &nbsp; Play Clipboard, Last Download and Play Line all write to the Played List.  

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
  - Play Clipboard: Download a video url that is in the clipboard via Yt-dlp and autoplay.
  - Play Clipboard is available in: Home  Played List  Play List  Yt-dlp Menu  View Downloads
  - See codec, resolution and duration on the playing video.
  - Play Directory autoplay available on: Home Screen, Navigate Tree and View Downloads.
  - Autoplay video files in the current directory with option to quit. videoinfox -d
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
PLAY DIRECTORY

Autoplay directory one level deep.

![Play Directory](https://i.imgur.com/4sw8VR6.png)


<br />
OPTION TO QUIT A WHEN A VIDEO ENDS OR THE VIDEO PLAYER IS QUIT.

Applies to Play Directory, Autoplay, Start Autoplay and Resume Autoplay

![Play Directory](https://i.imgur.com/c6N5iJ3.png)


<br />
YT-DLP MENU

![Yt-dlp Menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/YT-DLP-MENU.png)


<br />
DOWNLOAD LIST MENU WITH DOWNLOAD QUEUE

1. Create unlimited user lists. Add video url's to the list from the clipboard without leaving the browser.
   
   (Copy the url to clipboard then add video url to a user set list with the videoinfox -l gui keyboard shortcut.)

2. Download single list or
   Load unlimited user lists into the download queue for batch download.

![download list menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DOWNLOAD-LIST.png)


<br />
DEFAULT DOWNLOAD LIST.

Copy the url to clipboard then add video url to to the default list in videoinfox

or stay in your browser and add url with the videoinfox -a gui keyboard shortcut.

![Videoinfox download list help](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DEFAULT-LIST.png)


<br />
NAVIGATE TREE WITH PLAY DIRECTORY, AUTOPLAY and PLAY

![Navigate Tree](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/NAVIGATE-TREE.png)


<br />
NAVIGATE TREE >>> SHOW ALL WITH DIRECTORY TO PLAYLIST

![NT Show All](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/NT-SHOW-ALL.png)


<br />
FIND VIDEOS TO PLAY OR GET INFO.

SELECT PLAY, AUTOPLAY, INFO OR PLAYLIST ADD

![Videoinfox Find](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/FIND.png)


<br />
PLAYLIST

![Videoinfox Playlist](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAYLIST.png)


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

![Videoinfox Settings](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/SETTINGS.png)

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

###  v4.1.31 Add: Download Directory: is now displayed in Yt-dlp Menu >>> Download List >>> Default List

          Change: Screen is cleared for option -Clear Default List in Yt-dlp Menu >>> Download List >>> Default List

###  v4.1.20 Add: Loaded playlist is now displayed on the below screens which have option -Playlist Add in common.

          [Home]     [>>> Navigate Tree >>> Show All]     [Played List]

###  v4.1.12 Change: Blinking dash in Ytd-lp menu options -Download Default -Download Choose -Self Destruct changed to ~

          Change: Clipboard was saved when entering Yt-dlp >>> Download List and restored on quit even if the clipboard
                  was cleared while in Yt-dlp >>> Download List -Default List. Now the clipboard isn't restored if cleared.

          Fix: The default playlist could be deleted.
          Message: The default playlist list can't be deleted. It can only be cleared . . .
    
###  v4.1.09 Change: Clipboard is no longer cleared when entering or quitting -Default List in Yt-dlp >>> Download List.

###  v4.1.08 Removed one line that was accidently pasted with last update.

###  v4.1.07 Add: No execute if not a number in: -Set User list located in Yt-dlp Menu >>> Download List

###  v4.1.06 Updated more options to prevent script errors if entry isn't a number.
         
          Add: No execute if not a number in: -Remove Line in View Playlist
          Add: No execute if not a number in: -Change Playlist -Delete Playlist in View Playlist >>> Change Playlist          

###  v4.1.05 Update in Yt-dlp >>> Download List

          Add: No execute if entry is not a number in: -View List -View Log -Delete User List -Add to Queue

          Fix: Spacing at option -View List

###  v4.1.04 Change: Dashes would blink when entering Yt-dlp Menu >>> Download List with a valid url in the clipboard.

###  v4.1.03 Change: Yt-dlp Menu >>> Download List display of user download lists.

          Old display: line number -- /path/filename
          New display: line number -- filename (with videoinfox-dl- removed from the beginning of the filename.)
          Note: The path of a user list will be displayed when a user list is set.

          Fix: Videoinfox -a gui notification would display when the clipboard was empty or didn't start with http
              MESSAGE: Clipboard content didn't start with http (message will also display if the clipboard is empty)

          Fix: Videoinfox -l gui notification would display when the clipboard was empty or didn't start with http
              MESSAGE: Clipboard content didn't start with http (message will also display if the clipboard is empty)

          Add: Line to Download List Help - The Download List Display Is Sorted Recursively By Directory. Not By Filename.


###  v4.1.00 No more copying screen results to interact with Videoinfox. All Keyboard driven.

         Change: More Options >>> Find Directory
                 No more copying the directory to the clipboard. Enter Line Number.

         Add: Find Directory added to Navigate Tree

         Edit: Help

         Note: Clipboard copy is only needed when copying video urls for immediate
               download or to add the url to a download list in Videoinfox or a keyboard shortcut.
               Stay in the web browser and use: (default) videoinfox -a or (user) videoinfox -l


###  v4.0.01 Download List Help edit.

###  v4.0.00 No more copy to clipboard for options in YT-DLP >>> DOWNLOAD LIST.
         
         Enter line number for all options in YT-DLP >>> DOWNLOAD LIST.

         Note: The only place left that needs converted over to selection by number is 
         MORE OPTIONS >>> FIND DIRECTORY.

<br />



![Code Stats](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/code-stats.png)


