---
layout: post
title: Mechanical Keyboards
author: Jacques Levasseur
date: 2017-10-12
description: To improve the home entertainment experience, I built myself a NAS for storing my family's media
tags:
- projects
image: /assets/images/wd_red_6tb.jpg
---

To get the best typing experience possible, I decided to delve into the wide world of custom mechanical keyboards. In order to save space on my 
desk I settled on a 60% form factor as this provided all the keys I need for my day to day use. To ensure I would not be bothering anyone I decided 
to look for switches with the lowest sound feedback. 

### Materials

The materials I used for this project included:

* 60% Aluminum keyboard case
* 60% PCB
* 60% Aluminum switch plate
* Kailh Box Black switches (x70)
* Soldering iron and solder

### The Build

The components were all selected with cost savings in mind thus I repurposed as many things as I could find. I included some cost efficient parts such as a Pentium processor, that would be strong enough for serving files to all members of my family. The OS I decided to use was __Unraid__ as its redundancy implementation allows for a variety of differently sized drives, and for easy storage capacity expansion in the future. This OS fitted my needs perfectly.

### Conclusion

Unraid was a breeze to setup and use, thanks to its easy to use Web GUI and __Docker__ integration. I was able to setup network shares for the family media as well as personal shares for me and my parents. Also with the help of Docker containers, I am able to easily add features to my NAS such as __Plex__ to allow streaming of all our media from anywhere at home. The intuitive Plex app used can be found on a variety of devices, such as PC, android, PS4, etc. I now have 6TB of redundant storage that can be accessed from anywhere on my network and easily stream movies, music and photos all over the house. However, do note that redundancy is not a replacement for backups, so I hope to eventually create an offsite PC for cold storage backups.
