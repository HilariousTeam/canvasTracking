Tracking a video with canvas HTML5 over video tag.

This tracking try to follow video moves.
The aim is to add a text zone which can follow a move in the video context
A JSon var contains all the cuepoints of this move.

An animation is set over the video tag in a canvas div.
Every 40 miliseconds (25 frame/second), a new drawing is set on the canvas wich make the animation running.

This works, but the tracking (the animation) seems to be a bit late.