Mulitroom Audio/Video Streaming Server Plugin for XBMC

The purpose of this plugin is to facilitate the implementation and framework for a True Multi-Room "Syncronized Audio"
AND Video solution for XBMC.  This is why I have chosen VLC as the program of choice for this effort. Not only does it support
just about all audio and video formats very well but it provides the inherent capability to provide client/server streaming
syncronization over the local network which means that no more "out-of-phase" audio issues for those of you that have more
than one XBMC box in your home.

This is the 2nd release of this plugin New Features Include:

- Full support for Streaming both Video and Audio
- Plugin Settings Dialogue for Initial setup of Streaming Server
- Creates a custom playercorefactory.xml file in userdata directory for tighter integration with XBMC
- Stops Media on native XBMC when activating a Client
- Notification for Client - Activate / Deactivated

To Do's:
- Source Playing dialogue/popup after activating Audio source
- Integretion of vlc.py script for native vlc control from within XBMC
- Even Tighter and Seamless operation within XBMC
- Deletion of associated source config files when removing an AV Source.

There are alot of different ways to stream audio throughout the home but THE KEY is Syncronized AUDIO!!!!

This plugin requires the following:

NiX  (Ubuntu Karmic and Lucid have been thoroughly tested)
XBMC 9.11 (Camelot) or higher
xdotool  (do:  sudo apt-get install xdotool )  No configuration is necessary
wmctrl   (do:  sudo apt-get install xdotool )  No configuration is necessary
xterm    (Should already be included in your Ubuntu dist)
vlc 1.0 or higher (do: sudo apt-get vlc vlc-plugin**)**

INSTALLATION:

After you have met the minimum dependencies mentioned above...

1)  Place/copy the plugin in your ~/.xbmc/plugins/programs
2)  Enjoy!