# A Responsive CSS Grid Layout using just 2 lines of CSS!
## A simple responsive grid layout using NFL team logos

I can't believe how easy Grid makes it to create responsive layouts without @media queries. This was a quick project to test drive it, and to display all the NFL team logos in a simple grid using CSS Grid. 

![CSS Grid](https://github.com/nkhil/CSS-Grid-NFL-team-logos/blob/master/CSS-GRID-SHOWCASE.png "CSS Grid NFL Logos")

The grid is created using **Just 2 lines of CSS!**

```
  	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
```

OK, there's a third line `grid-gap:0` but this isn't doing any of the heavy lifting! 

### The logos have mostly been taken from sportslogos.net and then edited on Photoshop to be uniform. Feel free to use them as you like. I'd love it if you find a use for them (for commercial or not) and dropped me a note. 
