---
date: 1992-08-23 15
title:  "Ball Shaped Scroll Projector"
csdb: 5974
coders:
  - name: "Grabowsky"
    csdb: 9937
size: 63x63
fps: 50
tags: scroller scroller-hires scroller-distortion
---
![Ball Shaped Scroll Projector](/c64wrd/graffity/justintime/ball_shaped_scroll_projector.png)

Very high resolution scroller which distorts the runes onto a globes which moves XY over a scrolltext.

<!--more-->

Because the resolution is very high and calculation takes a long time, it precalculates 32 phases as the ball moves up/down. This saves time when the ball is closer to the top/bottom point, and in average it is just fast enough.