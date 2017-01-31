# 100 Days Of Code - Log

### Day 1: January 3, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress**: Toggle color of cells onClick

**Intro:** I'd already laid out the design of this project before Christmas, but took some time off for the holidays, and decided to wait to work out the JS until after the New Year.

**Thoughts:** Today, I worked on the changeColor function to toggle the color of the cells onClick. Also, pushing the cells into an array, so I can develop the patterns required in the Game of Life.

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 2: January 4, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** Worked on a function to develop the patterns...

**Thoughts:** Have some research to do and YouTube videos to watch, but I attempted to add a group of cells into a 2d array so I could then check if they're alive/dead....

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 3: January 5, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** Refactored the code for board generation, worked on logic for game play.

**Thoughts:** Just taking it step by step, watched some YouTube videos how to code the Game of Life, worked on writing the logic for game play.  Happy to have been able to find a better way to generate the game board with a for-loop, instead of declaring each TableRow component and each Cell component.  Makes for a lot less code!  More reading and studying to do :)

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 4: January 6, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** More work on logic for game play.

**Thoughts:** More studying and trying a few things out.....just working on it :)

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 5: January 7, 2017

**Project:** Repose Ranch web-site

**Today's Progress:** Just a few minor updates to my family's farm website

**Thoughts:** Made a few changes on [reposeranch.us](http://www.reposeranch.us), fix margins, better mobile-friendliness, etc.....

**Link to work:** [Repose Ranch](http://www.reposeranch.us)


### Day 6: January 9, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** Laid out if/else statements to check the status of the neighbors of a cell, if cell is alive or dead, minor refactoring, setInterval/clearInterval functions built inside React.js component.

**Thoughts:** Feel pretty good about what I got done today....definately a work in progress :) Certainly not perfect or working fully yet...but hoping to get it up and working really soon!

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 7, Day 8: January 10 and January 11, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** Debugging....and more work on game logic.

**Thoughts:** Found some things that didn't work correctly, so I am reworking some of the code :)

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 9: January 12, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** Getting the coordinates for each cell; reworked table, td and tr 

**Thoughts:** Discovered I wasn't getting the coordinates for each cell properly, but hopefully I have that fixed today :)  Also, worked on checking if the neighbors were alive or dead, pushing coordinates for the neighbors into the neighbors array, and reworked how I was rendering the table, tr, and td so I could get the coordinates for each cell easier.

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 10, 11, 12, & 13: January 13-16, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** More work on cells and rows, getting the index of each cell, refactoring checkNeighbors function...lots of refining and refactoring where I had some messy code :)

**Thoughts:** Since I have 58 rows, and 58 cells in each row to start with, I've got to find a way to get the current cell.  So far, I'm getting close :)  Still learning....as it seems I'm trying to get the index of the cell maybe out of scope?  A work in progress.

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 14: January 17, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress and Thoughts:** Finally getting proper indexes from current cell, created an object that holds the options for each cell, finished refactoring checkNeighbors function, checked that setInterval and clearInterval functions
run properly.....now on to the start, pause, reset, clear, and automated play functions! Very accomplished day :)

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 15: January 18, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** Looping through and randomly set cells to alive/dead, start/pause/reset/clear functions working, three different board sizes, three different speeds for iteration, generations working....

**Thoughts:** Another very productive day! Very happy with my progress. Only issue is after is randomly sets the first cells, it loops one time and then turns all the cells state to live!  Don't know why, but maybe I've got to get more specific on my checkNeighbors function or something..... some minor quirk I suppose :)  Also, I dove into a little Flux/Reflux today and tried a bit of it out in this project.  I wasn't sure if it was helping me or not and I needed to test some other pieces of the code, so I commented it out for a moment :)

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 16- 20: January 19 - 24, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress & Thoughts:** Not much in the way of progress today.... just trying to figure out why, after one loop (one generation) of the game, all the cells states are alive??? I've been playing with checking the current cell, checking the neighbors, and haven't narrowed it down yet....will have to research more tomorrow and look at it with fresh eyes.

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 21: January 25, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress & Thoughts:** I determined that my initial state of the cells was getting converted to true instead of false, therefore they were on when they weren't supposed to be....also, my 'if' statements were conflicting and causing some trouble with the running of the game.  I'm sooooo close!!!  My only issue now is that if a cells neighbors are less than 2, it turns all the cells off...making the whole board black :(  Yet, if I change it to cell.neighbors === 2, then the game runs except I get these single living cells hanging around.  More to work on tomorrow....

**Link to work:** [The Game of Life](http://codepen.io/CandiW/pen/MbaGZz)


### Day 22: January 26, 2017

**Project:** Free Code Camp Project - The Game of Life in React.js and SASS

**Today's Progress:** It's finally finished!

**Thoughts:** So happy I finally finished the Game of Life!  It was a simple mistake of an order of function calls that was causing issues for me in the last week.  Now on to the next project!

**Link to work:** [The Game of Life](http://codepen.io/CandiW/full/MbaGZz/)


### Day 23: January 31, 2017

**Project:** Learning D3.js

**Today's Progress:** Just started watching some tutorial videos on YouTube....and following along with the code in CodePen.

**Thoughts:** So far, it seems just as simple as I thought it would be! I watched a couple videos and it was really helpful for me who's just getting started :)  Links to the videos are below:

**YouTube video links:** [D3.js Intro](https://youtu.be/n5NcCoa9dDU) & [Select & Append in D3.js](https://youtu.be/qIIKw2RFNlU)

**Link to work:** [D3.js tutorial example 1](http://codepen.io/CandiW/pen/xgYWrd)
