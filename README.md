Simple - Conky theme
=================================

My simple conky setup, basic design that looks better on dark wallpapers.

![Simple - Conky theme](https://github.com/andeon/conky-simple/blob/master/Simple/Simple.jpg)



Author & License
-----------------
Created by Anderson Prado (AndeOn)

Licensed under the GNU GENERAL PUBLIC LICENSE, Version 2

Installation
------------
1. Copy the folder "Simple" into the ~/.conky (Hidden folder on home directory)

Ubuntu and derivatives
-----
Conky Manager is a graphical front-end for managing Conky config files. It provides options to start/stop, browse and edit Conky themes installed on the system. 

If you are using Ubuntu or its derivatives (like Xubuntu, Linux Mint, etc) you can install it from the Launchpad PPA.

`sudo apt-add-repository -y ppa:teejee2008/ppa`

`sudo apt-get update`

`sudo apt-get install conky-manager`

Links
-----

Conky: https://github.com/brndnmtthws/conky

Conky Manager: http://www.teejeetech.in/p/conky-manager.html

Notes
-----
- Optimized to work with wireless connection. The network setting may not suit for your environment. Run `ifconfig` to get the name of device that you are currenty using, then change `wlan0` to it. If it's ethernet put `#` in front the line 159 "signal strength" to comment.

- Conky 1.10.1 have issue with `$pre_exec` variable (I remove  the auto detect "lsb_release" to fix). Check here: https://github.com/brndnmtthws/conky/issues/62 

- own_window_type not work properly in some Desktop Environment, change it if necessary. Options:  (normal, desktop, dock, panel or override)

