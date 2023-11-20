---
date: 1992-08-23 17
title:  "Interference Circles"
csdb: 5974
coders:
  - name: "Grabowsky"
    csdb: 9937
size: 96x192
fps: 50
tags: interference interference-spritepriority
---
![Interference Circles](/c64wrd/graffity/justintime/interference_circles.png)

Interference Circles using sprite priority.

<!--more-->

One set of the circles is drawn both into csets and sprites. The other set is drawn only to sprites. Depending on the sprite priority and whether the sprite is supposed to be behind or in front of the cset, the intersections are automatically see-through.

At least that was what they told me for years. But now I see in C64 Debugger that both sets of sprites are in front of the csets...