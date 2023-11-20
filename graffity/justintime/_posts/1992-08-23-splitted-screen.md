---
date: 1992-08-23 14
title:  "Splitted Screen"
csdb: 5974
coders:
  - name: "Cheesion"
    csdb: 391
size: 320x83
fps: 50
tags: splittedscreen splittedscreen-fli splittedscreen-fpd
---
![Splitted Screen](/c64wrd/graffity/justintime/splitted_screen.png)

A hires FPD routine on the left and a multi FLI picture on the right.

<!--more-->

The FPD is done with cset changes, 6 characters are covered with sprites around the split to hide VIC garbage, the FPD effect is drawn into the sprites. The hires/multi change is done with $d800.