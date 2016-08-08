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
If you are using Ubuntu or its derivatives (like Xubuntu, Linux Mint, etc) you can install it from the Launchpad PPA.

Conky Manager is a graphical front-end for managing Conky config files. It provides options to start/stop, browse and edit Conky themes installed on the system. 

`sudo apt-add-repository -y ppa:teejee2008/ppa`

`sudo apt-get update`

`sudo apt-get install conky-manager`

Links
-----

Conky: https://github.com/brndnmtthws/conky

Conky Manager: http://www.teejeetech.in/p/conky-manager.html

Notes
-----
- Optimized to work with wireless connection. Edit the file and change variable wlan0 to eth0 and put # in front the line 159 "signal strength" to comment.

- Conky 2.0 have issue with $pre_exec variable check here: https://github.com/brndnmtthws/conky/issues/62

- own_window_type not work properly in some Desktop environment, change it if necessary. Options:  (normal, desktop, dock, panel or override)

