# Linux-adventure

After getting approved for my undergrad thesis, I had no need for my windows setup. So, I went and used Xubuntu 18.04 full time; making it my daily driver. 

Along the way I went and did customizations, fixes, and overall enhancement to the OS that probably no clean install could be like this.

I'm making this retroactively seeing what improvements im making so that I can also replicate it if i ever decide to migrate to another distro or upgrade.

TODO:

Turn Distro headers into a neat table




Table of Contents
=================

   * [Linux-adventure](#linux-adventure)
   * [Distro Hopping](#distro-hopping)
      * [Ubuntu 12.04](#ubuntu-1204)
      * [Manjaro](#manjaro)
      * [Kubuntu 16.04](#kubuntu-1604)
      * [PuppyLinux (Tahrpup)](#puppylinux-tahrpup)
      * [Xubuntu 18.04](#xubuntu-1804)
         * [Regolith(i3)](#regolithi3)
      * [KDE Neon](#kde-neon)
      * [Ubuntu Mate](#ubuntu-mate)
      * [Linux Mint Cinnamon](#linux-mint-cinnamon)
         * [Budgie](#budgie)
   * [Ricing](#ricing)
      * [GTK Themes](#gtk-themes)
      * [Icons](#icons)
   * [Fixes](#fixes)
      * [GNOME Wallpaper inconsistency](#gnome-wallpaper-inconsistency)
      * [Re-enable bluetooth](#re-enable-bluetooth)
      * [Hide firefox Bookmarks toolbar and show only when url bar is clicked](#hide-firefox-bookmarks-toolbar-and-show-only-when-url-bar-is-clicked)
      * [Disable Bluetooth on Startup](#disable-bluetooth-on-startup)
      * [Add F4 to Nemo Open terminal](#add-f4-to-nemo-open-terminal)
      * [Wifi speed fix](#wifi-speed-fix)
      * [Mousescrolling fix](#mousescrolling-fix)
      * [Fixing slow copying speeds (Xubuntu)](#fixing-slow-copying-speeds-xubuntu)
   * [Packages](#packages)
      * [Retroarch](#retroarch)
         * [Lakka](#lakka)
      * [Scrcpy](#scrcpy)
      * [Plank](#plank)
      * [Todoist for Linux](#todoist-for-linux)
      * [TLP](#tlp)
      * [Termdown](#termdown)
      * [pyhostsman](#pyhostsman)
      * [OnlyOffice (Feb 2020)](#onlyoffice-feb-2020)
      * [WPS Office (Dec 2019)](#wps-office-dec-2019)
      * [LibreOffice Addons](#libreoffice-addons)
      * [Adobe Photoshop](#adobe-photoshop)
      * [ANGRYSearch](#angrysearch)
      * [SublimeText](#sublimetext)
      * [XFCE Tiling](#xfce-tiling)
      * [Linux MTP File Transfer](#linux-mtp-file-transfer)
      * [Redshift GTK](#redshift-gtk)
      * [Flameshot](#flameshot)
      * [Keyboard Shortcuts](#keyboard-shortcuts)
      * [APT-SMART](#apt-smart)
      * [Ghostwriter](#ghostwriter)






# Distro Hopping

I was first introduced to linux during highschool. Despite being around computers my whole life, and use one practically everyday, I've never heard of linux or open source software. My high school computer lab had been shipped with **Edubuntu** and we were introduced to it. I was amazed. I was hooked on dual booting it. 

Sir Calunangan (RIP sir) introduced us to this great distribution. I thought it looked ugly. Joed and I were smug in the class using the only windows computer in the lab. We played Dota there at some point. 

I can't remember much of it rn, but I remember doing an all nighter fixing my broken grub because the internet at school was fastest in the evening. 

## Ubuntu 12.04 

I remember tinkering with ubuntu 12.04 where I was not able to access my windows partition. I remember staying up all night and eventually sleeping with exhaustion and frustration that I couldn't make it work. 

I remember during the final days of my Neo netbook, when the hinge on the monitor could not stand it. I had successfully dual booted it having a Naruto bijuu mode vs Ichigo bankai as my wallpaper in the Unity desktop.

![Naruto image](/images/naruto-ichigo-wallpaper.jpg)


## Manjaro

This was a dual boot from my first PC build. I didn't use it that much but only was a backup and to scratch an itch I had with linux.

![Manjaro2014](/images/manjaro_2014.jpg)

## Kubuntu 16.04

was a dual boot, backup OS i had on my Vaio laptop  
I remember I didn't like using the interface but that dual boot installation sure saved my ass when I broke my windows setup that one night while cramming (and procrastinating)

## PuppyLinux (Tahrpup)

My hard drive broke that one time 3rd year college. I didn't have funds to buy a hard drive. So I used puppy linux in a CD so I could boot my laptop. Saved my files on my flash drive and the cloud. It was an alright time. I lived with it for a while. It was not that bad.


## Xubuntu 18.04

UPDATE: Im thinking of moving to KDE or MATE during the 20.04 Release or when I get a new replacement SSD for my laptop.
UPDATE2: Couldn't wait for that replacement SSD. I borked my installation by interrupting a system update while it was installing.
Display broke (?)

### Regolith(i3)

I briefly tried i3. Wasn't for me.
![Regolith](/images/regolith.png)

## KDE Neon

I'm a huge fan of the performance improvements of KDE (ram usage) and I really want to be part of the community that is passionate about it. But I don't think the DE is for me. I find the customization options too overwhelming. The icons and UI elements feel a bit hacked together? Or was missing a bit of polish and finesse? 

I know I could tweak it further so that these negative stuff will be removed, but it seemed too daunting a task- I wanted to get into work.

It's a shame, KDE would have been perfect for me and my need for a non-compositing WM for WINE Photoshop.

## Ubuntu Mate

Went with MATE. I liked the customization but I didn't feel the UI was modern enough. 

## Linux Mint Cinnamon

I tried cinnamon and immediately fell in love. Cinnamon was perfect for me and my use case

A few weeks of usage however resulted in me finding out the bug that Cinnamon's WM had with WINE and photoshop. I considered it a bit of a dealbreaker.

Now I'm eyeing GNOME and will probably install GNOME whenever I get the chance of fast internet so I can update my stuff.

### Budgie

Budgie feels like Cinnamon. I like it. It solves the photoshop problem for me.

## Moving Forward

### KDE Neon

I really want to like KDE Neon since it has a wonderful community, active development, and most importantly, very sleek system usage with ram usage comparable to XFCE. But I couldn't get into the default UI without giving up. I guess I'll try to use it for maybe a week and customize it to be similar to GNOME. 

### Pop! OS 20.04

I've been hearing great things about Pop! but im concerned about the memory usage. I like GNOME. Let's see where it will take me.

### 2021-2022 Update: 

I went with KDE Neon for about a year. Now I'm on cinnamon.

## Cinnamon Changes

1. Keyboard Shortcuts

Change `Ctrl + L` to lock
Change `PrtSc` to `flameshot gui -p 'path/to/folder'`

2. Startup Applications

* Battery monitor for Low battery alerts 

```bash
#!/bin/bash

# Script to send persistent notification on low battery events
# Depends on zenity - apt install zenity
# Save script in ~/bin or ~/.local/bin and make executable.
# Add an entry to your startup applications.

# This script will update Cinnamon's backend power settings to base low battery warnings and actions on
# remaining battery percentage rather than time. It also updates the thresholds for the native notification 
# and actions to those set in the variables listed below.

# Low Battery Warning Level
LOW_BAT=20

# Critical Battery Warning Level
CRIT_BAT=13

# Critical Battery Action Level
CRIT_BAT_ACTION=10

# Main script starts here
# Check for existing instances and kill them leaving current instance running
for PID in $(pidof -o %PPID -x "${0##*/}"); do
    if [ "$PID" != $$ ]; then
        kill -9 "$PID"
    fi 
done
#Find battery
if upower -e | grep battery; then
   BATTERY=$(upower -e | grep battery)
else
   echo "Error could not find battery"
   exit 1
fi

# Update Gsettings
gsettings set org.cinnamon.settings-daemon.plugins.power use-time-for-policy false
gsettings set org.cinnamon.settings-daemon.plugins.power percentage-low "$LOW_BAT"
gsettings set org.cinnamon.settings-daemon.plugins.power percentage-critical "$CRIT_BAT";
gsettings set org.cinnamon.settings-daemon.plugins.power percentage-action "$CRIT_BAT_ACTION";

# Get Critical Battery Action from Gsettings

CRIT_ACTION=$(gsettings get org.cinnamon.settings-daemon.plugins.power critical-battery-action)
if [ "$CRIT_ACTION" == "'suspend'" ] && busctl call org.freedesktop.login1 /org/freedesktop/login1 org.freedesktop.login1.Manager CanHybridSleep | grep yes && gsettings get org.cinnamon.SessionManager prefer-hybrid-sleep; then
    CRIT_ACTION="'hybrid-sleep'"
fi

# Start loop
while true; do
STATE=$(upower -i "$BATTERY" | grep -E state|xargs|cut -d' ' -f2|sed s/%//)
if [ "$STATE" != "discharging" ]; then
    STATUS="OK"
   sleep 1m
   continue
else
   LEVEL=$(upower -i "$BATTERY" | grep -E percentage|xargs|cut -d' ' -f2|sed s/%//)
   if [ "$LEVEL" -gt "$LOW_BAT" ]; then
      STATUS="OK"
      sleep 1m
      continue
   elif [ "$LEVEL" -le "$CRIT_BAT" ] && [ "$STATUS" != "Critical" ] ; then
      zenity --warning --text="\nBattery Critically Low - $LEVEL% left.\n\nPlugin to AC as soon as possible.\n\nThe system will $CRIT_ACTION at $CRIT_BAT_ACTION%" --width=400
      STATUS="Critical"
      sleep 1m
      continue
   elif [ "$LEVEL" -le "$LOW_BAT" ] && [ "$STATUS" != "Low" ] && [ "$STATUS" != "Critical" ]; then
                zenity --warning --text="\nBattery Low - $LEVEL% left.\n\nPlugin to AC.\n\nThe system will $CRIT_ACTION at $CRIT_BAT_ACTION%" --width=400
      STATUS="Low"
      sleep 1m
      continue
   fi
fi
sleep 1m
done

```

3. Disable Bluetooth

```bash
rfkill block bluetooth
```

4. Start Syncthing

```bash
/usr/bin/syncthing serve --no-browser --logfile=default
```

## Extensions

### Transparent Panels

*Transparentize your panels when there are no any maximize windows*


## Applets

### Timer with Notifications

## Fonts

### Cantarell

Apparently I like the default fedora gnome font Cantarell. it looks clean af. Ubuntu font is great too.

# Ricing

## GTK Themes

The GTK Themes that I like are

Adwaita (and dark variants)
Nord
Adapta and Adapta-notko

## Icons

Papirus
Vimix


# Fixes

## Separate firefox profile for work

add this in keyboard shortcuts
`CTRL` + `Q`  `firefox -P grego-work`
this starts firefox with a separate profile. Good for comparmentalizing your browsing experience.



## GNOME Wallpaper inconsistency

from this omgubuntu [post](https://www.omgubuntu.co.uk/2017/04/fix-gnome-wallpaper-inconsistency):

>"See, whenever you drag an image file into the Picture overview of the GNOME Background settings pane GNOME stores a copy in ~/.cache/gnome-control-center/backgrounds/."

>The “fix” is to replace the backgrounds folder in the cache folder with a symbolic link back to the wallpapers folder that GNOME settings ignores.

```
rm -r ~/.cache/gnome-control-center/backgrounds
ln -s /path/to/wallpaper/directory ~/.cache/gnome-control-center/backgrounds

```

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


## Add F4 to Nemo Open terminal

https://forums.linuxmint.com/viewtopic.php?t=227702
https://forums.linuxmint.com/viewtopic.php?f=47&t=225682

## Wifi speed fix
Because im still dual booting my windows, I noticed that the wifi speed on my ubuntu was slower than the wifi speed on my windows. I found a fix online and applied it.

```
Create a .conf file for the "iwlwifi" driver that the kernel uses:

    "sudo nano /etc/modprobe.d/iwlwifi.conf"

Then set the 11n_disable parameter to 8

    "options iwlwifi 11n_disable=8"
    Save -> reboot.

```
https://www.reddit.com/r/archlinux/comments/677dzp/slow_intel_advancedn_6205_wifi_speed_fix/



https://ubuntuforums.org/showthread.php?t=2364068

https://askubuntu.com/questions/830868/wifi-on-ubuntu-works-slower-than-wifi-on-windows-for-my-laptop

https://askubuntu.com/questions/939050/dual-booting-ubuntu-windows-10-wifi-on-ubuntu-is-extremely-slow


## Mousescrolling fix

I was frustrated with the inability to fine tune mouse scrolling and I found a solution with a gui using zenity. However I have found a perfect configuration that I run during startup.

```
imwheel --kill --buttons "4 5"
```

I got this fix from [here](http://www.nicknorton.net/?q=node/10).

## Fixing slow copying speeds (Xubuntu)

I read somewhere that PCManFM didn't have this problem vs. Thunar that XFCE is installed with. I found out that I liked PCManFM, but the problem still persisted. This fixed the problem.

https://gist.github.com/2E0PGS/f63544f8abe69acc5caaa54f56efe52f

Linux Mint Cinnamon does not appear to have this problem.


# Packages

## Retroarch

I wanted to emulate mario kart

### Lakka

For a more-permanent tv attachment solution, i've employed lakka

http://www.lakka.tv/


## Scrcpy

*Display and control your android device*

I like it hehe


## Plank

I've taken a liking to the MacOS dock style.


## Todoist for Linux

```
npm install nativefier -g
```


```
nativefier --name TodoistWeb "https://www.todoist.com" --tray --single-instance
```

Then add to a shortcut Super + B


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

## Adobe Photoshop 

Install the portable version through wine. Works surprisingly well.

## ANGRYSearch

A python based, Everything(Win only) alternative. It works okay, but not as great as Everything. Man I wish Everything had a port.

## SublimeText

Download Sublime through here: https://www.sublimetext.com/docs/3/linux_repositories.html

## XFCE Tiling

![From this reddit thread of tiling.](https://raw.githubusercontent.com/gregorylearns/linux-adventure/master/images/xfce_tile.PNG)

Sorry I didn't upvote(i think it was archived?).


## Linux MTP File Transfer
Not as seamless as it is in windows. I hate that it just doesnt work out of the box. I learned how to use ES File explorer FTP how to manage files. Now this (ES File Explorer) is nifty.


## Redshift GTK

I tried f.lux to work, but it doesn't. Redshift is very good and highly recommend.

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

PrtSc - Flameshot (flameshot gui -p "path/to/dir")

Alt + K,J,L,M,',','.',U,I,O - Tile Windows


## APT-SMART

```
pip3 install apt-smart
```
From this askubuntu thread: https://askubuntu.com/questions/39922/how-do-you-select-the-fastest-mirror-from-the-command-line

Christmas Eve i'm having problem with updating a package using apt. Found out that PH Servers were 6 hours and a day behind respectively.

## Ghostwriter

Was looking for a writing package to write something distraction free. Turns out finding it was a distraction for myself to procrastinate in doing the thing I didnt want to do.

