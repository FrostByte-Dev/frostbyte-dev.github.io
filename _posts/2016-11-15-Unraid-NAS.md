---
layout: post
title: Unraid NAS
author: Jacques Levasseur
date: 2016-11-15
description: For this project, I built myself a NAS for storing my family's media library (movies, music
tags:
- projects
image: /assets/images/wd_red_6tb.jpg
---

To Improve the family movie viewing experience, I built myself a NAS for storing my family's media library (movies, music, photos). This also provided me with redundant storage for my own personal files. Seeing as prebuilt NAS devices tend to be either highly underpowered or extremely expensive, I decided to recycle and repurpose some parts I had to save on costs.

### Materials

The materials and software I used for this project included:

* NZXT Phantom 410 Mid Tower case
* Intel Pentium G3825
* G.Skill Ripjaws X 16GB (2x8GB)
* Corsair 450w power supply
* 3 X 3TB WD Red drive
* 4GB USB drive
* Unraid OS (Basic plan)

### The Build

The components were all selected with cost savings in mind thus I repurposed as many things as I could find. I included some cost efficient parts such as a Pentium processor, that would be strong enough for serving files to all members of my family. The OS I decided to use was __Unraid__ as its redundancy implementation allows for a variety of differently sized drives, and for easy storage capacity expansion in the future. This OS fitted my needs perfectly.

### Conclusion

Unraid was a breeze to setup and use, thanks to its easy to use Web GUI and __Docker__ integration. I was able to setup network shares for the family media as well as personal shares for me and my parents. Also with the help of Docker containers, I am able to easily add features to my NAS such as __Plex__ to allow streaming of all our media from anywhere at home. The intuitive Plex app used can be found on a variety of devices, such as PC, android, PS4, etc. I now have 6TB of redundant storage that can be accessed from anywhere on my network and easily stream movies, music and photos all over the house. However, do note that redundancy is not a replacement for backups, so I hope to eventually create an offsite PC for cold storage backups.
