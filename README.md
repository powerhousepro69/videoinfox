Videoinfo x v1.83


>>>>>>>>>>> HOME SCREEN <<<<<<<<<<<

Directory: /mnt/MEDIA1/MOVIES
Clipboard: v1.83

==================================================================================================================
 Videoinfo x v1.83 >>> HOME
==================================================================================================================

 1 - List Directory       4 - Video Count          p - Play Clipboard     f - FIND                       e - Exit
 2 - Change Directory     5 - Video Duration       v - Played List        y - YT-DLP                     d - Set
 3 - Find Directory       6 - Enter Video File     s - Saved Finds        x - Clear Clipboard            h - Help

 Enter Option: 




>>>>>>>>>>> FIND RESULTS SCREEN <<<<<<<<<<<

/mnt/MEDIA1/MOVIES/Terminator 2 Judgment Day 1991.mp4
/mnt/MEDIA1/MOVIES/National Lampoons Christmas Vacation.mp4
/mnt/MEDIA1/MOVIES/Step Brothers.UNRATED.2008.1080p.BluRay.H264.ACC.5.1.BADASSMEDIA.mp4
/mnt/MEDIA1/MOVIES/A.Walk.Among.the.Tombstones.2014.1080p.BluRay.x264.YIFY.mp4
/mnt/MEDIA1/MOVIES/The Pelican Brief 1993 720p BRRip x264-PLAYNOW.mp4

Total files found: 139
Found Date: 2022-04-07 00:04:13
Found in: /mnt/MEDIA1/MOVIES
Find Entry: *

Directory: /mnt/MEDIA1/MOVIES

Copy 1 above Find to the Clipboard then info or play

===================================================================================================================
 Videoinfo x v1.83 >>> FIND RESULTS
 Clipboard: 
===================================================================================================================

 f - Find     v - Played List     s - Saved Finds     x - Clear Clipboard     C - Clear Find Results      q - Quit
 i - Info
 p - Play                                                                                                 t - Tips

 Enter Option: 



>>>>>>>>>>> YT-DLP <<<<<<<<<<<

 Working Directory: /mnt/MEDIA1/yt_download

===================================================================================================================
 Videoinfo x v1.83 >>> YT-DLP MENU                                          yt-dlp Version Installed: 2022.03.08.1

 Video url needs to already be in the clipboard.  Then <ENTER> to verify copied url  Then Download or Play

 Clipboard: /mnt/MEDIA1/yt_download

 Download Directory: /mnt/MEDIA1/yt_download
===================================================================================================================

 d - Download Video     v - View Downloads     s - Set Download Directory     c - Check Yt-dlp Update     q - Quit

 p - Play Video (download, watch, delete)

 Enter Option: 

  
  
  
Dependencies:   
 
- xclip needed for autopaste feature.  xclip only works with Xsession
  
- ffmpeg is used to extrat Duration in <hrs:min:sec> format
  - ffprobe is used to extract Codec, Resolution and Duration in floating seconds format (x.xxxxxx)
  - ffplay is used in option pto play the video that is in the clipboard.                                        
  
- bc (already installed on most disrtros)  needed to do floating point math in <options 1 & 7>
  
- notify-send (already installed on most disrtros) needed to display gui notifications.

 
*** Videoinfo runs a dependency check at startup.  
*** If any dependencies are Not Found, the script will exit.
*** Videoinfo will display which dependencies are missing.
