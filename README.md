Buskey Jump
============

Playable on the [gh-pages branch](http://justinsoon.github.io/buskeyjump)

About
-----
A Doodle Jump clone for AP Comp Sci.

Use the arrow keys to navigate your ever-jumping Buskey and collect Dr. Pepper for extra points.
Push higher with the green platforms, watch out from the red, they'll be pulled from under you.
Forks will teleport you around 100 lines of code further.


Technicals
----------
Best playable on Chrome, works in FF (less FPS), fails on IE9 (getter\setters) and untested on others...
I've used the Octicons font instead of sprites for the pickups, saves bandwidth and scales better,
at the prices of more CSS3 effects.
Overall, not a lot of canvas is used, which means less performance, as the DOM gets updated often.

Credits
-------
Mr. Buskey for modeling the character.
Louis Stowasser for his awesome framework [Crafty](http://craftyjs.com).  
[Pow Studio](http://powstudios.com/content/smoke-animation-pack-1) - for the smoke jump sprite.  
Font Diner's [Chewy](http://www.google.com/webfonts/specimen/Chewy).  
And Github's @bryanveloso, @jonrohan, @jsncostello, @kneath, and @cameronmcefee for the [Octicons](https://github.com/styleguide/css/7.0) font.  

Any other assets were either photomanipulated with Photoshop.

To do:
------
* Game doesn't restart when you die, have to refresh the page.
* Split the .js, follow Crafty's boilerplate
* Scoreboard
* Level editor
