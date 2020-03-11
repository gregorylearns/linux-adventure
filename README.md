# Linux-adventure

After getting approved for my undergrad thesis, I went and used Xubuntu 18.04 full time; making it my daily driver. 

Along the way I went and did customizations, fixes, and overall enhancement to the OS that probably no clean install could be like this.

Im making this retroactively seeing what improvements im making so that I can also replicate it if i ever decide to migrate to another distro or upgrade.(Im thinking of moving to linux mint cinnamon)

UPDATE: Im thinking of moving to KDE or MATE during the 20.04 Release or when I get a new replacement SSD for my laptop.


## Disable Bluetooth on Startup

added this line on the startup settings:

```
rfkill block bluetooth
```

inspired by this [thread](https://askubuntu.com/questions/67758/how-can-i-deactivate-bluetooth-on-system-startup).


## Nativefier

```
npm install nativefier -g
```

### Todoist

```
nativefier --name TodoistWeb "https://www.todoist.com" --tray --single-instance
```

Then add to a shortcut Super + B


## Add F4 to Nemo Open terminal

https://forums.linuxmint.com/viewtopic.php?t=227702
https://forums.linuxmint.com/viewtopic.php?f=47&t=225682



## TLP

I read somewhere in a thread where TLP is supposed to saves battery in linux.

[Project Page](https://linrunner.de/en/tlp/tlp.html)
[Github Page](https://github.com/linrunner/TLP)



## Termdown

is a python library for a CLI countdown timer. Very useful for timers.
Install using

````
$ sudo pip3 install termdown
````

## pyhostsman

Not actually installed yet but im trying to make it work to distance myself from distraction during work hours.

## OnlyOffice (Feb 2020)

WPS Office is great. However there's this annoying bug that occurs when you close any WPS Office application and they persist in the memory. So now, I've taken on using OnlyOffice as my PDF reader. OnlyOffice isn't powerful enough, or isn't very close to MS Office in handling and UI as WPS. I'll keep using WPS for my editing needs and use OnlyOffice for the PDF Reading.


## WPS Office (Dec 2019)

Somehow after installing and testing out this software, I felt complete. This completed my longing for a fully-featured Office app for the distro. Somehow the thing that was missing from the installation is a reliable office app and photoshop (Sorry LibreOffice). Even with the notebookbar and office2013 icons added to the LibreOffice installation, it still didn't suffice for me. I felt like some Docx formatting is going to be destroyed. It felt a bit inadequate.
Also, the .deb file from their website is way better than the snap package.
The snap package won't open files from NTFS partitions. I followed the snap media tutorial for enabling this, it only works for the Spreadsheet app

Download link:
https://www.wps.com/en-PH/download/

## LibreOffice Addons

Although this looked like the familiar MS Office Ribbon UI, it still didn't do for me since most of my work revolves around getting MS Documents from my friends.
![Libreoffice wiht Notebookbar and Office2013 addons installed](/images/libreoffice-notebookbar-office2013icons.png)


## Fixing slow copying speeds

I read somewhere that PCManFM didn't have this problem vs. Thunar that XFCE is installed with. I found out that I liked PCManFM, but the problem still persisted. This fixed the problem.

https://gist.github.com/2E0PGS/f63544f8abe69acc5caaa54f56efe52f

## Photoshop CS6

Install the portable version through wine. Works surprisingly well.


## ANGRYSearch

A python based, Everything(Win only) alternative. It works okay, but not as great as Everything. Man I wish Everything had a port.

## SublimeText

Download Sublime through here: https://www.sublimetext.com/docs/3/linux_repositories.html

## XFCE Tiling

![From this reddit thread of tiling.](https://raw.githubusercontent.com/gregorylearns/linux-adventure/master/images/xfce_tile.PNG)

Sorry I didn't upvote huhu.


## Linux MTP File Transfer
Not as seamless as it is in windows. I hate that it just doesnt work out of the box. I learned how to use ES File explorer FTP how to manage files. Now this (ES File Explorer) is nifty.


## Redshift GTK

I tried f.lux to work, but it doesn't. Redshift is very good and highly recommend.


## Wifi speed fix
Because im still dual booting my windows, I noticed that the wifi speed on my ubuntu was slower than the wifi speed on my windows. I found a fix online and applied it.

https://ubuntuforums.org/showthread.php?t=2364068

https://askubuntu.com/questions/830868/wifi-on-ubuntu-works-slower-than-wifi-on-windows-for-my-laptop

https://askubuntu.com/questions/939050/dual-booting-ubuntu-windows-10-wifi-on-ubuntu-is-extremely-slow

## Flameshot

Missed snipping tool on windows, found this amazing alternative. I also have it on my keyboard shortcut as PrtSc - flameshot gui -p "path/to/dir"

## Keyboard Shortcuts

Super + D - Show Desktop

Super + G - Telegram Desktop

Super + F - File Manager

Super + H - Discord

Super + T - Terminal

Super + W - Firefox

Super + Z - Whisker Menu

PrtSc - Flameshot 

Alt + K,J,L,M,',','.',U,I,O - Tile Windows


## APT-SMART

```
pip3 install apt-smart
```
From this askubuntu thread: https://askubuntu.com/questions/39922/how-do-you-select-the-fastest-mirror-from-the-command-line

Christmas Eve i'm having problem with updating a package using apt. Found out that PH Servers were 6 hours and a day behind respectively.

## Ghostwriter

Was looking for a writing package to write something distraction free. Turns out finding it was a distraction for myself to procrastinate in doing the thing I didnt want to do.


## Mousescrolling fix

I was frustrated with the inability to fine tune mouse scrolling and I found a solution with a gui using zenity. However I have found a perfect configuration that I run during startup.

```
imwheel --kill --buttons "4 5"
```

I got this fix from [here](http://www.nicknorton.net/?q=node/10).