# My Dev Notes, yo!

## Add a JS component

- Install using bower
- Reference in config.yml (it'll be in bower_components)


## Bugs and Fixes


 ## 2017-12-09 (Waypoints)
The waypoints jquery plugin wouldn’t work when I tried to declare an offset (uit always happend in the middle of the page instead of the bottom). It was <main> main had a display: block; that was related to normalize or something. Setting the tagret elemnts to display: inline; FIXED IT!!!

## 2017-04-07 Dropdown menu didn’t work on mobile
This was a known issue (or something close to this was happening) so I used this solution...just downloaded the latest foundation.js
