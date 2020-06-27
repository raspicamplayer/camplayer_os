
++ IMPORTANT NOTES ++
                        
** COMPONENTS **
                          
"CAMPLAYER OS" consist out of three main components:
    1) Camplayer: an open source and free to use camera stream player with a GPLv2 license.
       Source code can be found here https://github.com/raspicamplayer/camplayer.
    2) The OS: open source and free operating system based on Debian. 
    3) Systemhelper: Configuration tool for configuring camplayer (1) and the operating system (2).
       This part is currently closed source and proprietary.

** SECURITY **

The camera player software "Camplayer" uses RTSP/HTTP streams for playback, 
even with password protection these streams can not be considered as secure for the following reasons:
    1) RTSP/HTTP streams are not encrypted, only the login procedure is protected!
    2) Someone with physical access to this device can grab the SD card
       and read its content, including possible passwords!
       
For these reasons, CAMPLAYER OS is only intended to be used for harmless footage in protected 
and trusted home networks (domestic use). This text is not a replacement for the 
EULA (end-user license agreement), it is additional information.
