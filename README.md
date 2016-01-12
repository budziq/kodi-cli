kodi-cli
========

Kodi/XBMC bash script to send Kodi commands using JSON RPC. It also allows sending youtube videos to XBMC.

#Usage

`kodi-cli -[p|i|s|y youtbe URL/ID|t "text to send"|o "youtube title"]`

#Arguments
```
-p Play/Pause the current played video
-s Stop the current played video
-y play youtube video. Use either URL/ID (of video)
-o play youtube video directly on Kodi. Use the name of video.
-i interactive navigation mode. Accept keyboard keys of Up, Down, Left, Right, Back,
information and context menu.
-t "text to send"
```

#Dependencies
* curl(1) is used to make actual JSON RPC requests
* for the "-o" option to work you'll need to install [mps-youtube](https://github.com/np1/mps-youtube)
