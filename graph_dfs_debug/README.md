##**THIS EXERCISE IS OPTIONAL FOR CS7**

##DO NOT BEGIN UNTIL YOU HAVE COMPLETED ROUTING.JS

#Help!

Hi Friend,

After learning about breadth-first-search, I decided to give depth-first-search a try. I'm pretty sure I've almost got it working, but I can't figure out the last few bugs. Can you help? I've got the following issues. I'm not sure if the order here matters, you might have to fix them in a different order than they are listed.

1.  The graph draws crazily.
2.  All the vertexes are the same color. They're supposed to match the color of the edges for each connected component.
3.  My randomize button is broken.
4.  It looks like part of the graph is getting cut off.

I'm still trying to learn this stuff, so please don't just fix the code for me. Let me know where my bugs are and what you did to fix them, so I can have an easier time watching out for them next time!

Thanks!

## App.js

    - Problem 1 - Line 139 Don't use .shift() on stacks, commented out and worked like a charm
    - Problem 2 - line 64  fix : ctx.fillstyle = color,  was: ctx.fillstyle = '#77f'; so that the color can be defined in the updateCanvasConnectedComponents() function
    - Problem 3 - line 164 this.button -> this.onButton as it is a previously named function
    - Promblem 4 -  Line 125 width on canvas was set as cavasHeight not canvasWidth
