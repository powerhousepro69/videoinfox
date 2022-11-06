# Videoinfox v4.6.07

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

#### NEW in v4.6.00 New Option in Settings: Default Directories to Playlist


Add recursive listings from Default Dirs 1-4 to a new Playlist. Then use Playlist Find to search all Default Dirs.

#### NEW in v4.5.00 -Playlist Find added to the home screen. Text search of all playlists.


Find videos without providing the files location. More info located about Playlist Find in Home Help.

<br />
Download multiple URL User Lists simultaneously.

You have to start Download List first then run another instance of Videoinfox to start downloading the next list.
<br />

Videoinfox is a Linux shell script that feels like an app. If you enjoy watching local videos on your PC and want the ability to download video url's, you won't be disappointed. You can also make your own URL lists to download. While downloading a list, a log file will be generated for each list. The log is each http link from your list with the downloaded video filename. If the download list is aborted before completion, Yt-dlp has you covered. Just run the Download List feature again. Yt-dlp won't re-download files that you already have. Download Queue to add unlimited Videoinfox created User Download Lists
for batch processing.There is a Played List that keeps track of everything played by Play Clipboard, Last Download and Play. Create unlimited Playlists and autoplay with last video played marker. Playlist queue to load up multiple playlists.


#### ADD VIDEOS TO A PLAYLIST FROM THE FOLLOWING 7 SOURCES:

- Home Screen. Add videos from recursive search results or recursive directory listings to the loaded Playlist.

- Make Playlist on the Home Screen. Add all search results to a new Playlist.

- Navigate Tree >>> Show All. Add videos from one level deep directory listings to the loaded Playlist.

- Directory to Playlist in Navigate Tree >>> Show All. Add all videos in the current directory to a new Playlist.

- Default Directories to Playlist in Settings. Add recursive listings from Default Dirs 1-4 to a new Playlist.

- Queue to Playlist: Add the Playlist Queue to a new Playlist.

- Played List. Add videos from Played List to the loaded Playlist.
        Play, Play Clipboard, Last Download all write to the Played List.
        *** The Playlist, Play Directory and Autoplay won't write to the Played list.

#### Start Autoplay on a playlist from the beginning to the end of the list or Start Autoplay from anywhere in the list and play to the end of the list. Resume Autoplay will start with last the video that was playing on Start Autoplay quit. Resume Autoplay will also keep track of the last video that was playing on quit.

<br />

### Harnessing the power of:

Videoinfox - Over 12,000 lines of code.

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
  - File types searched for: &nbsp; .webm &nbsp; .mp4 &nbsp; .mkv &nbsp; .avi &nbsp; .divx
  - Create unlimited Playlists from: &nbsp; Recusive search results, Recursive directory listings and the Played List
  - Make Playlist on the Home Screen to save all search results as a playlist.
  - Playlist & Playlist Queue Edit options: &nbsp; Remove Line &nbsp; Remove Dupes &nbsp; Move Line &nbsp; Clear Playlist
  - Playlist & Playlist Queue Play options: &nbsp; Play &nbsp; Start Autoplay &nbsp; Resume Autoplay  
  - Directory To Playlist: &nbsp; Create a new playlist from a 1 level deep dir listing. Good for seasons of TV shows.
  - Playlist Queue to load unlimited playlists for autoplay with last played video marker.
  - Queue to Playlist: &nbsp; Save the Playlist Queue to a new Playlist.
  - Default Directories to Playlist: Add recursive listings from Default Dirs 1-4 to a new Playlist. 
  - Play Clipboard: &nbsp; Download a video url that is in the clipboard via Yt-dlp and autoplay.
  - Play Clipboard is available in: &nbsp; Home &nbsp; Played List &nbsp; Play List &nbsp; Yt-dlp Menu &nbsp; View Downloads
  - See codec, resolution and duration on the playing video.
  - Play Directory autoplay available on: &nbsp; Home Screen &nbsp; Navigate Tree &nbsp; View Downloads.
  - Set Intermission time in seconds. Change the time in seconds on video end/player quit. Initially set to 10.
  - Command Line Option: &nbsp; videoinfox -d &nbsp; Autoplay video files in the current directory with option to quit.
  - Navigate Tree with Play Directory, Play and Autoplay. Select line number to start play.
  - Video Player auto closes when the video ends. Ffplay is used by default. Any video player can be used.
  - Auto clear the video url from clipboard after the video player is closed.
  - To watch the last download after Play Clipboard cleared the link select Last Download.
  - Auto clear the clipboard of invalid video urls.
  - Press enter after your copy to the clipboard to validate clipboard content.
  - Rapid directory changing by setting default directories (4) in Settings. The 5th is the directory at last exit.
  - Default Dirs - 1 2 3 4 5  available in: Home &nbsp; Navigate Tree &nbsp; Download List &nbsp; More Options
  - Played List: &nbsp; Log everything played except for: Play Directory, Autoplay, and anything played from a Played List.
  - Duplicates auto-removed from the Played List.
  - Enter a video file with full path to get info on and/or play.
  - Auto save last find result(s) and autoload until deleted. Defaulted to never save. Change in Settings.
  - Yt-dlp integration for easy download of a single url, a list of url's or a queue of multiple url lists.
  - Download List: &nbsp; Download a list by entering line number.
  - Logging of downloaded url lists with link and downloaded filename provided by Yt-dlp. 
  - Download Queue: &nbsp; Add unlimited Videoinfox User Download Lists to the queue for download.
  - Download Default: &nbsp; Yt-dlp with no arguments. Download only. No auto play.
  - Download Choose: &nbsp; Choose video type and quality before download. Download only. No auto play.
  - Self Destruct: &nbsp; Download, auto play, delete when the player is closed.
  - Last Download in: &nbsp; Home and Yt-dlp Menu for: Play Clipboard, Download Default and Download Choose.
  - Default List: &nbsp; Keep pasting Video URL's on the fly from the clipboard to the Default List.

        Default List companion: Create a keyboard shortcut for: videoinfox -a  to add to the Default List.
  - Unlimited User Lists: Keep pasting Video URL's on the fly from the clipboard to the User Set List.

        User Set List companion: Create a keyboard shortcut for: videoinfox -l  to add to the User Set list.
  - Command Line Option: &nbsp; videoinfox -u listname &nbsp; Download any url list to the directory of the list's location.
  - Download and update Yt-dlp in Videoinfox.
  - Save current working directory on exit to load on next run.
  - Change directory by entering full path.
  - Find directory and change to it by entering the line number.
  - List video info one directory deep. Save per directory.
  - Recursive count of videos broken down by video type.
  - Recursive duration (days:hrs:min:sec) Save per directory.
  - GUI notifications.
  - More options . . .

<br />
 
### To use Play Clipboard:

 
#### Copy a video url to the clipboard then press enter to verify validity then &nbsp; p &nbsp; to download and auto play.


<br />


PLAY DIRECTORY

Autoplay directory one level deep. Option to quit on video end or player quit.

Autoplay features: &nbsp; Play Directory, Autoplay, Start Autoplay and Resume Autoplay.

![Play Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PLAY-DIRECTORY.png)


<br />
INTERMISSION SCREEN. Initially set to 10 seconds. Time can be changed in Settings.

Applies to Play Directory, Autoplay, Start Autoplay and Resume Autoplay

![Quit Play Directory](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/PD-QUIT.png)


<br />
YT-DLP MENU

Download video url in clipboard or download and autoplay with Play Clipboard

![Yt-dlp Menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/YT-DLP-MENU.png)


<br />
DOWNLOAD LIST MENU WITH DOWNLOAD QUEUE

1. Create unlimited user lists. Add video url's to the list from the clipboard without leaving the browser.
   
   Copy the url to clipboard then add video url to a user set list with the videoinfox -l keyboard shortcut.

2. Download single list or load unlimited user lists into the download queue for batch download.

![download list menu](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/DOWNLOAD-LIST.png)


<br />
DEFAULT DOWNLOAD LIST

Copy the url to clipboard then add video url to to the default list in videoinfox

or stay in your browser and add the url with the videoinfox -a keyboard shortcut.

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

DEPENDENCIES &nbsp; Any missing dependencies will be displayed.
  
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
        when you select the Yt-dlp Menu to attempt a download of Yt-dlp.
      - Everytime Yt-dlp is used to download a video url.
        Refer to Yt-dlp's site for their privacy policy. https://github.com/yt-dlp/yt-dlp



** If videoinfox is removed, the directory  ~/.config/videoinfox  will have to be manually deleted.
<br />

###  v4.6.07 Change: Home Help, Download List Help and Version History.

         The above files were written on every start. Now only written on update or delete.

         Fix: Script error from Resume Autoplay. Located in View Playlist.
              error on Resume Autoplay if Start Autoplay wasn't run at least once before Resume Autoplay.

         Fix: Script error from Resume Autoplay in View Playlist >>> Change and Queue >>> Play Queue.
              error on Resume Autoplay if Start Autoplay wasn't run at least once before Resume Autoplay.

         Fix: When deleting or clearing a playlist, last video played marker for that playlist wasn't being removed.


### v4.6.03 Change in Playlist Find.
         
         Enter with no entry shows no results. Enter . to Show All

### v4.6.02 Change: Play Clipboard doesn't blink anymore with valid url in the clipboard. The dash blinks.

### v4.6.01 Edit: Home Help >>> Create Unlimited Playlists section.

### v4.6.00 New Option in Settings: Default Directories to Playlist

         Playlist named Default Directories will be created with recursive listings from default directories 1-4
         Then Playlist Find can be used to search for videos in all 4 default directories.

         Change home screen option: z - Set ............... u - Set
         Change home screen option: b - Make Playlist ..... z - Make Playlist

         Added to Playlist Find: To show all: Press Enter with no entry.

         Added to Home Help: Default Directories to Playlist

<br />



![Code Stats](https://github.com/powerhousepro69/videoinfox/blob/main/screenshots/CODE-STATS.png)


