rpi_video_web_control
=====================

Web video stream with camera control for Raspberry Pi with camera module

Installation:
* install ffmpeg, raspivid, crtmpserver etc. according to guide at http://www.raspberrypi.org/phpBB3/viewtopic.php?f=43&t=45368
* install lighttpd or other www server capable of running cgi script, allow python cgi scripts execution from www root dir
* unpack rpividwebcontrol.tar.gz into / dir including file permissions (cd / && tar -xpzf rpividwebcontrol.tar.gz)

Warning:
* the pages and cgi script has been coded with **no effort to make it secure, use it in local environment only** !!!
