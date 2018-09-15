# A Responsive CSS Grid Layout using just 2 lines of CSS!
## A simple responsive grid layout using NFL team logos

I can't believe how easy Grid makes it to create responsive layouts without @media queries. This was a quick project to test drive it, and to display all the NFL team logos in a simple grid using CSS Grid. 

The grid is created using **Just 2 lines of CSS!**

```
  	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
```

OK, there's a third line `grid-gap:0` but this isn't doing any of the heavy lifting! 


