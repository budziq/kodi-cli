kodi-cli
========

Kodi/XBMC bash script to send Kodi commands using JSON RPC. It also allows sending youtube videos to XBMC.

#Usage

`kodi-cli [-p|i|h|s|m|y youtube URL/ID|t 'popup text'|x 'text to send'|v volume]`

#Arguments
```
-p Play/Pause the current played video
-s Stop the current played video
-m Toggle audio mute
-v Set volume in the range 0-100
-y play youtube video. Use either URL/ID (of video)
-o play youtube video directly on Kodi. Use the name of video.
-i interactive navigation mode. Accept keyboard keys of Up, Down, Left, Right, Back, Context menu and information
-x 'text to send'
-t 'show popup with text'
-h displaying this help message
```

#Dependencies
* curl(1) is used to make actual JSON RPC requests
* for the "-o" option to work you'll need to install [mps-youtube](https://github.com/np1/mps-youtube)
