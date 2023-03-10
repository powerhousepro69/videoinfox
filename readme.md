# Videoinfox v5.9.44

### *Where video download and play is a clipboard copy away . . .*

![Videoinfox HOME](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/videoinfox.gif)

### To install : &nbsp; &nbsp; Run the 2 lines below.
```
sudo wget https://raw.githubusercontent.com/powerhousepro69/videoinfox/main/videoinfox -O /usr/local/bin/videoinfox
```
```
sudo chmod +x /usr/local/bin/videoinfox
```

**Getting Started:** Set the Default Directories located in -Set. Enter the parent directories of your video libraries. Then run -Index Default Directories This will build a searchable recursive list of all 5 default directories for -Playlist Find. Find a video(s) with a keyword from the path or file.

#### *Videoinfox will not edit video files. It is a front-end to play videos, build playlists and download videos.*

### 100% Linux Shell Script. Videoinfox is only 1 megabyte.

Find your videos fast.  Powerful playlist building and editing.  A play queue to load up unlimited playlists
for autoplay with last video played marker to pick up where you left off. Played List that keeps track of 
everything played by Play Clipboard, Last Download and Play.  Index unlimited video libraries and find 
videos by keyword from the path or file.  Yt-dlp integration with Download list building without leaving
your web browser and a download queue to load up unlimited download lists for batch processing.  Download
entire URL playlists or pick and choose what videos to download with browse.  A download queue in browse to
add single videos from any of the playlists to batch download. 

*Videoinfox recommends using MPV to watch videos and will be set as the default video player if found.
Mpv saves play postion on quit of every video played and Videoinfox saves Playlist and Play Queue position.
Toggle on/off mpv save play position on quit and an option to erase all mpv markers.

### Hotkey navigation that is robust and efficient.

     ONE KEYPRESS FOR ALL MENU SELECTIONS. OVER 150 OPTIONS.


### File types searched for: &nbsp; .webm &nbsp; .mp4 &nbsp; .mkv &nbsp; .avi &nbsp; .divx &nbsp; .3gp

        Note:   -Show All on the Home Screen is recursive.
                -Show all in -Navigate Tree is one level deep.


### Playlist Features:

### *Create, Watch, Manage playlists and the Play Queue in View Playlist*

#### *Create*

     - Create .......... Create an empty playlist.
     - Playlist Add .... Add an individual video to the loaded playlist.
     - Make Playlist ... Save the entire video listing as a new playlist.
       
       Playlist overwrite prompt for an existing file with options:  -Create and -Make Playlist


     The following 3 areas support  -Playlist Add  and  -Make Playlist:

     * Home Screen to add videos from recursive search results or recursive directory listings.
     * Navigate Tree >>> Show All to add videos from one level deep directory listings.
     * Played List to add videos from the Played List.

       Note: Play, Play Clipboard and Last Download all write to the Played List.
             Play Directory, Autoplay, Start and Resume do not write to the Played list.


     Save the entire list as a new playlist with the following 2 options:
 
     - Make Playlist to save the Play Queue as a new playlist.
     - Default directories and all Playlists can be saved as a playlist.
       Playlist Find and search . then -Make Playlist. 


#### *Watch*  

     - Start autoplay from anywhere in the playlist. 
     - Resume to start autoplay from the last video that was playing on quit.
     - Play Queue to load up multiple playlists for autoplay with resume.
     - Play to play a single video and write it to the played list.
     

#### *Manage*

     - View Playlist

       - Move Line .............. move a video in the playlist.
       - Move Block ............. move a block of videos in the playlist.
       - Remove Line ............ remove a video from the playlist.
       - Remove Block ........... remove a block of videos from the playlist
       - Remove Dupes ........... remove duplicate videos from the playlist.
       - Clear Playlist ......... clear out the playlist.

     - Play Queue

       - Move Line .............. move a video in the play queue.
       - Move Block ............. move a block of videos in the play queue.
       - Remove Line ............ remove a video from the play queue.
       - Remove Block ........... remove a block of videos from the play queue.
       - Remove Dupes ........... remove duplicate videos from the play queue.
       - Clear Queue ............ clear out the play queue and the queue list.
  
     - Change and Queue

       - Change ................. change playlist.
       - Create ................. create empty playlist.
       - Delete ................. delete playlist.
       - Rename ................. rename playlist.
       - Save As ................ save the loaded playlist as... with file overwrite prompt.
       - Add to Queue ........... add playlist to the play queue. 

     - Queue List
 
       - Move Line * ............ move a playlist in the play queue.
       - Remove Line * .......... remove a playlist from the play queue.
       - Remove Dupes * ......... remove duplicate playlists from the play queue.
       - Rebuild Queue .......... updates play queue after one or more of the above 3 options * are run
       - Clear Queue ............ clear out the queue list and the play queue.

       videoinfox -z  Make a playlist from a recursive video listing in the current directory.
                      The Playlist will be saved in: ~/.config/videoinfox/playlists which makes
                      the playlist/index available to videoinfox's feature set.


### *Find videos by searching the text of all Playlists and the Default Directories Index*      

### Playlist Find

![Playlist Find](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAYLIST-FIND.png)

      Find videos to play or add to a playlist without needing to know the files location.
      Use a keyword from the path or filename to locate videos.

      Note: Default directories must be set up first. Then run  - Index Default Directories
            
            Indexing more directories in addition to the 5 default directories is a simple process.
            Change to a parent directory of a video library. Then -Show All on the home screen
            and select -Make Playlist

            * Duplicates are always removed from playlist find results.

<br />
VIEW PLAYLIST to Create, Watch, and Manage Playlists and the Play Queue

![Videoinfox Playlist](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAYLIST.png)


<br />
CHANGE AND QUEUE in View Playlist

![Videoinfox Change and Queue](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/CHANGEANDQUEUE.png)


<br />
PLAY QUEUE in View Playlist >>> Change and Queue

![Videoinfox Play Queue](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAYQUEUE.png)


<br />

  - Help is located on the Home screen covering most of the features. Help also in Download List and View Playlist.  
  - Auto save last search result(s) and autoload until cleared. Defaulted to never save. Change in Settings.
  - Check for update on startup and notifity if update is available. Download and update in Videoinfox.
  - Play a local file by entering the line number. Play single video or autoplay the entire list.
  - See codec, resolution and duration on the playing video.  
  - Set Intermission time in seconds. Change the time in seconds on video end/player quit. Initially set to 10.
  - Video Player auto closes when the video ends or quit(q). MPV is used by default. Any video player can be used.
  - Change directory by entering line number or by entering the path.
  - Find directory and change to it by entering the line number.
  - Directory saved on exit to load on next run.
  - GUI notifications
  - Rapid directory changing by setting default directories (5) in Settings. 6 is the directory at last exit.
  
        Default Dirs - 1 2 3 4 5 6  available in: Home, Navigate Tree, Download List & More Options

  - Played List: &nbsp; Log everything played with: &nbsp; Play, &nbsp; Play Clipboard &nbsp; and &nbsp; Last Download 
  - Info: Get codec, resolution and duration of videos. 

        More Options:

        List Directory: List video info one directory deep. Options to save/delete per directory.
        Video Count: Recursive count of videos broken down by video type.
        Video Duration: Recursive duration (days:hrs:min:sec) Options to save/delete per directory.

### Play Clipboard 

        Download a video url that is in the clipboard via Yt-dlp and autoplay.
        Play Clipboard is available in: Home, Played List, View Playlist, Yt-dlp Menu & View Downloads
        The video url is cleared from clipboard after the video player is closed.
        To watch the last download after Play Clipboard cleared the link, select Last Download.
        Any invalid video urls are costantly cleared from the Clipboard.

         Note: A local video file with full path can be copied to the clipboard for play.
               No quotes for files with spaces.
               
         To use Play Clipboard:
         Copy a video url to the clipboard then press enter to verify validity.
         Then  p   to download and autoplay.

<br />
PLAY DIRECTORY

Autoplay directory one level deep. Option to quit on video end or player quit. *Videoinfox autoplay features: &nbsp; Play Directory, Autoplay, Start and Resume*

![Play Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAY-DIRECTORY.png)

<br />
INTERMISSION SCREEN. Initially set to 10 seconds. Time can be changed in Settings. Applies to Play Directory, Autoplay, Start, and Resume

![Quit Play Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PD-QUIT.png)

#### Yt-dlp integration: Download a single url, a list of url's, a queue of multiple url lists and URL Playlists.
    
        BUILD DOWNLOAD LISTS WITHOUT LEAVING YOUR BROWSER.         

        Download and update Yt-dlp in Videoinfox.

        Download Only: Yt-dlp with no arguments. Download clipboard only. No autoplay.
        Download Choose: Choose video type and quality before download. Download only. No autoplay.
        Self Destruct: Download, auto play, delete when the player is closed.
        Last Download: Play last download.

        Download List: Download a list by entering line number.
        Logging of downloaded url lists with link and downloaded filename provided by Yt-dlp. 
        Download Queue: Add unlimited Videoinfox User Download Lists to the queue for batch download.

        Download Channel: Download an entire playlist or browse a playlist and choose what to download.

        Command Line Option:  videoinfox -u listname
        Download any url list to the directory of the list's location.
        
        Default List: Keep pasting Video URL's on the fly from the clipboard to the Default List.
        Default List companion: Create a keyboard shortcut for: videoinfox -a
                                to past the video url to the Default List.

        User Lists: Keep pasting Video URL's on the fly from the clipboard to the User Set List.
        User Set List companion: Create a keyboard shortcut for: videoinfox -l
                                 to paste the video url to the User Set list.


<br />
YT-DLP MENU
Download video url in clipboard or download and autoplay with Play Clipboard

![Yt-dlp Menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/YT-DLP-MENU.png)

<br />
DOWNLOAD CHANNEL in the Yt-dlp Menu

![Videoinfox DL Playlist](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DOWNLOAD-PLAYLIST.png)

Download Channel: Total number of videos downloaded and videos in URL playlist are displayed for each list. The channel/playlist name are checked to find if the entry already exists to avoid a duplicate entry. Yt-dlp will check URL Playlist validity before it is added to the list. Removed playlists can be recovered with Restore. Update Playlist to download a fresh copy.  When downlading an entire playlist you can ctrl/c out of a download in progress and restart the download right from where it left off thanks to Yt-dlp's archive feature. Browse to download single videos from a playlist and a
download queue to add single videos from any of the playlists for batch download.

BROWSE in Download Channel. Download single videos from the playlist or add videos to the queue.
![Videoinfox DL Playlist](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/BROWSE-DPL.png)

<br />
DOWNLOAD LIST MENU WITH DOWNLOAD QUEUE

1. Create unlimited user lists. Add video url's to the list from the clipboard without leaving the browser. Copy the url to clipboard then add video url to a user set list with the videoinfox -l keyboard shortcut.

2. Download single list or load unlimited user lists into the download queue for batch download.

![download list menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DOWNLOAD-LIST.png)


<br />
DEFAULT LIST

Copy the url to clipboard then add video url to to the default list in videoinfox or stay in your browser and add the url with the videoinfox -a keyboard shortcut.

![Videoinfox download list help](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DEFAULT-LIST.png)


<br />
NAVIGATE TREE

![Navigate Tree](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/NAVIGATE-TREE.png)

<br />
NAVIGATE TREE >>> SHOW ALL one directory deep listing with Play, Autoplay, Playlist Add and Make Playlist

![NT Show All](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/NT-SHOW-ALL.png)

<br />
FIND DIRECTORY

![Videoinfox Find Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/FIND-DIRECTORY.png)

<br />
FIND VIDEOS TO Play, Autoplay, Playlist Add or Make Playlist with all search results.

![Videoinfox Find](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/FIND.png)

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
COMMAND LINE OPTIONS: &nbsp; videoinfox -h

![videoinfox -h](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/VIDEOINFOX-H.png)

<br />
   
#### Dependencies:   
 
- xclip &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;copy and paste feature.  xclip only works with Xsession  
- ffmpeg &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;extrat duration in &nbsp; (hrs:min:sec) &nbsp; format
- ffprobe &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;extract codec, resolution and duration in floating seconds format  &nbsp; (x.xxxxxx)
- ffplay &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; play video                                        
- bc &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; floating point math
- notify-send  &nbsp; &nbsp; &nbsp; display gui notifications

<br />

YT-DLP is not on the dependeny list becuase Videoinfox will dowload it to: &nbsp; ~/.config/videoinfox &nbsp;
 All calls to yt-dlp are pointed to: &nbsp; ~/.config/videoinfox/yt-dlp &nbsp;
 There is an update option in: &nbsp; \<Set\>&nbsp; Settings to update yt-dlp &nbsp; (just the copy in ~/.config/videoinfox) &nbsp;
 I didn't want to overwrite anyones copy of: &nbsp; /user/local/bin/yt-dlp &nbsp;  &nbsp;
 Also, I wanted to make sure all new Videoinfox script installs included the most recent version of Yt-dlp
 
#### Videoinfox runs a dependency check at startup.  If any dependencies are not found, the script will exit.

Any missing dependencies will be displayed.

<br />
FIRST RUN

![Videoinfox FIRST RUN](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/FIRST-RUN.png)
<br />


#### Privacy Policy: &nbsp; Videoinfox will never collect or attempt to transmit any information on it's users.

     Internet activity will only happen under the following circumstances:

      - On First Run, Github will be contacted to download Yt-dlp.
      - On every start, Github will be contacted to download Videoinfox for Update Available Check.
      - Every time Videoinfox Update or Yt-dlp Update is selected in Settings, Github will be contacted.
      - If there isn't a copy of Yt-dlp in Videoinfox's config directory, Github will be contacted
        when you select the Yt-dlp Menu to attempt a download of Yt-dlp.
      - Every time Yt-dlp is used to download a video url.
        Refer to Yt-dlp's site for their privacy policy. https://github.com/yt-dlp/yt-dlp



** If videoinfox is removed, the directory  ~/.config/videoinfox  will have to be manually deleted.
<br />

###  v5.9.44 Fix: Had to fix some headers in Download Playlist.

###  v5.9.43 Edit: A few small edits in Home Help.

###  v5.9.42 Add: Splash screen with script name and removed checking for update display.

         💥️ The splash screen suggestion came from goochockipar@reddit  Thanks 👍️

###  v5.9.41 Change: Added 4s timeout to wget when checking for videoinfox update on startup.

###  v5.9.40 Edit: Home Help.

###  v5.9.39 Fix: -Rebuild Queue in Queue List would throw a script error if run on empty queue.

###  v5.9.38 Change: -Download Only -Download Choose -Self Destruct in Yt-dlp Menu. - changes to * on valid URL in clipboard.

         Removed white space at end of all lines. 

###  v5.9.37 Edit: Download Channel -Help. Change Directory Section.

###  v5.9.36 Fix: Disk on Home Screen. Now displays Not Set if any of the directories aren't set.

###  v5.9.35 Add: Note added to error in Download located in Download Channel with further explanation of the manual fix.

###  v5.9.34 Update: -Disk. Shows current directory video disk usage and Default Directories 1-5

         Fix: Forgot to remove Press enter to coninue... in Browse -Download

###  v5.9.32 New: -Search added to Browse to find videos in a URL playlist by keyword.

         Search results have been integrated into -Download and -Add to Queue.

         New: -All to Queue added to browse. Add the entire playlist or search results to the queue.

         Change: Download Playlist renamed to Download Channel.
         Edit: Home help for the renamed feature.

         Change: Channel link removed from heads up display in Download Channel. It is located in Info.

         Change: Moved optons around in Browse.

         Change: 2 option letters swapped in Yt-dlp -Download List: z-Download Queue and b-Clear User Set List.

         Fix: Auto remove duplicates in Download Queue in Browse.

         Fix: Script errors in Download Channel when list was empty or the last item was deleted.

         Fix: Clear All in Download Channel -Restore wasn't clearing out the .nfo and .pl files.


### Harnessing the power of:

Videoinfox - Over 17,000 lines of code.

Xclip - Interact with the clipboard.

Yt-dlp - Download video urls.

MPV or FFplay - Play videos.

FFmpeg - Get duration in hh:min:sec

FFprobe - Get codec, resolution & duration in seconds.


![Code Stats](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/CODE-STATS.png)

