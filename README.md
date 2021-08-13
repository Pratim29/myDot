Welcome to my Dotfiles. Most of the files are self explanatory and also has their own readme and comments. So, please read the manual and comments before messing with your system.

My recommendation is to use it ina a testing environment like Virtual Machine (VM) because if you break it you can simply create a new one which you can't do if you accidentally break your Primary OS.

Read the readme.md file containing in every folder. It gives a better explanation of how to use the file, what to do and what not to do, etc. 

#Proceed with Caution. Incompatibility WARNING!
To get my configs and settings just copy them to the relative paths. 
for example :-
$ git clone https://github.com/diggajupadhyay/myDot.git && cd myDot/ && cp etc/X11/xorg.conf.d/20-touchpad.conf /etc/X11/xorg.conf.d/
& do this for every path. 

For settings like crontab and rtcwake you just have to manually open text editor of your kind and paste them.
for example :-
$ cd myDot/crontab && 




