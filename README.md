# Linux-adventure

After getting approved for my undergrad thesis, I went and used Xubuntu 18.04 full time; making it my daily driver. 

Along the way I went and did customizations, fixes, and overall enhancement to the OS that probably no clean install could be like this.

Im making this retroactively seeing what improvements im making so that I can also replicate it if i ever decide to migrate to another distro or upgrade.(Im thinking of moving to linux mint cinnamon)



Table of Contents
=================

   * [Linux-adventure](#linux-adventure)
      * [Distro Hopping](#distro-hopping)
         * [It was probably Ubuntu 11.04 ?](#it-was-probably-ubuntu-1104-)
         * [Manjaro](#manjaro)
         * [Kubuntu was a dual boot, backup OS i had on my Vaio laptop](#kubuntu-was-a-dual-boot-backup-os-i-had-on-my-vaio-laptop)
         * [Xubuntu 18.04](#xubuntu-1804)
         * [KDE Neon](#kde-neon)
         * [Ubuntu Mate](#ubuntu-mate)
         * [Linux Mint Cinnamon](#linux-mint-cinnamon)
      * [Re-enable bluetooth](#re-enable-bluetooth)
      * [Hide firefox Bookmarks toolbar and show only when url bar is clicked](#hide-firefox-bookmarks-toolbar-and-show-only-when-url-bar-is-clicked)
      * [Disable Bluetooth on Startup](#disable-bluetooth-on-startup)
      * [Todoist for Linux](#todoist-for-linux)
      * [Add F4 to Nemo Open terminal](#add-f4-to-nemo-open-terminal)
      * [TLP](#tlp)
      * [Termdown](#termdown)
      * [pyhostsman](#pyhostsman)
      * [OnlyOffice (Feb 2020)](#onlyoffice-feb-2020)
      * [WPS Office (Dec 2019)](#wps-office-dec-2019)
      * [LibreOffice Addons](#libreoffice-addons)
      * [Fixing slow copying speeds (Xubuntu)](#fixing-slow-copying-speeds-xubuntu)
      * [Adobe Photoshop](#adobe-photoshop)
      * [ANGRYSearch](#angrysearch)
      * [SublimeText](#sublimetext)
      * [XFCE Tiling](#xfce-tiling)
      * [Linux MTP File Transfer](#linux-mtp-file-transfer)
      * [Redshift GTK](#redshift-gtk)
      * [Wifi speed fix](#wifi-speed-fix)
      * [Flameshot](#flameshot)
      * [Keyboard Shortcuts](#keyboard-shortcuts)
      * [APT-SMART](#apt-smart)
      * [Ghostwriter](#ghostwriter)
      * [Mousescrolling fix](#mousescrolling-fix)









## Distro Hopping

I was first introduced to linux during highschool. Despite being around computers my whole life, and use one practically everyday, I've never heard of linux or open source software. My high school computer lab had been shipped with edubuntu and we were introduced to it. I was amazed. I was hooked on dual booting it. 

I can't remember much of it rn, but I remember doing an all nighter fixing my broken grub because the internet at school was fastest in the evening. 

### It was probably Ubuntu 11.04 ?


### Manjaro


### Kubuntu was a dual boot, backup OS i had on my Vaio laptop

### Xubuntu 18.04

UPDATE: Im thinking of moving to KDE or MATE during the 20.04 Release or when I get a new replacement SSD for my laptop.

### KDE Neon

### Ubuntu Mate

### Linux Mint Cinnamon


## Re-enable bluetooth

So I've apparently soft-blocked my bluetooth and 
```
rfkill unblock bluetooth
```
does not work.

From [askubuntu](https://askubuntu.com/questions/688090/cannot-unblock-soft-blocked-bluetooth)
```
rfkill unblock bluetooth
systemctl enable bluetooth.service
systemctl start bluetooth.service
```
It worked after this

## Hide firefox Bookmarks toolbar and show only when url bar is clicked

Tutorial from here
https://superuser.com/questions/1283874/how-to-show-bookmarks-toolbar-only-on-new-tabs-in-firefox

basically it's to add this line of code to your userChrome.css file
```
#nav-bar:not(:focus-within) + #PersonalToolbar:not(:hover):not(:focus-within):not([customizing]) { visibility: collapse; }
```


## Disable Bluetooth on Startup

added this line on the startup settings:

```
rfkill block bluetooth
```

inspired by this [thread](https://askubuntu.com/questions/67758/how-can-i-deactivate-bluetooth-on-system-startup).


## Todoist for Linux

```
npm install nativefier -g
```


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


## Fixing slow copying speeds (Xubuntu)

I read somewhere that PCManFM didn't have this problem vs. Thunar that XFCE is installed with. I found out that I liked PCManFM, but the problem still persisted. This fixed the problem.

https://gist.github.com/2E0PGS/f63544f8abe69acc5caaa54f56efe52f

Linux Mint Cinnamon does not appear to have this problem.

## Adobe Photoshop 

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