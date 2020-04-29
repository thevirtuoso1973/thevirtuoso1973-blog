---
title: "Randomly Generating Maze Game"
date: 2019-08-03
draft: false
---

Uses a backtracking algo to generate new mazes each time the space bar is pressed.

**Space: New maze | Arrow keys: Move | Goal: Green triangle**

_Note: Requires JavaScript._

<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.9.0/p5.min.js"></script>
<div id="mazeCanvas"></div>
<script src="/js/maze.js"></script><br>

<div style="width:100%; text-align: center;">
<div style="display: inline-block;"><button type="button" onclick="simulateKey('UP_ARROW')">Up</button></div>
</div>
<div style="width:100%; text-align: center;">
<div style="display: inline-block;"><button type="button" onclick="simulateKey('LEFT_ARROW')">Left</button></div>
<div style="display: inline-block;"><button type="button" onclick="simulateKey('RIGHT_ARROW')">Right</button></div>
</div>
<div style="width:100%; text-align: center;">
<div style="display: inline-block;"><button type="button" onclick="simulateKey('DOWN_ARROW')">Down</button></div>
</div>
<br>
<div style="width:100%; text-align: center;">
<div style="display: inline-block;"><button type="button" onclick="simulateKey('SPACEBAR')">New Maze</button></div>
</div>
