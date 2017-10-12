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
* 60% Aluminum universal switch plate
* Kailh Box Black switches (x70)
* Soldering iron and solder

### The Build

The case used was a fully aluminum 60% form factor with blockers in the bottom left and right corners which gave the board a very solid and 
premium feeling as well as a bit of custom flair in the corners. The Kailh box black switches were used as they are very smooth linear switches 
with very little key wobble. As these are linear switches they only make sound when the key bottoms out and comes back up to rest which coupled 
with a very solid board gives for a fairly quiet keyboard on par if not quieter then most standard membrane keyboards found in most offices. The 
PCB used is loaded with qmk firmware, which is an open source keyboard firmware which allows you to program your layout any way you want. This is 
especially handy in smaller form factors that are missing keys that you may still need on the odd occasion.

### Conclusion

Unraid was a breeze to setup and use, thanks to its easy to use Web GUI and __Docker__ integration. I was able to setup network shares for the family media as well as personal shares for me and my parents. Also with the help of Docker containers, I am able to easily add features to my NAS such as __Plex__ to allow streaming of all our media from anywhere at home. The intuitive Plex app used can be found on a variety of devices, such as PC, android, PS4, etc. I now have 6TB of redundant storage that can be accessed from anywhere on my network and easily stream movies, music and photos all over the house. However, do note that redundancy is not a replacement for backups, so I hope to eventually create an offsite PC for cold storage backups.
