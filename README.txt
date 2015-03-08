Steps taken to Optimize index.html

OPTIMIZE IMAGES:
	1. resize/compress pizzeria.jpg
	2. compress profilepic.jpg

AVOID RENDER BLOCKING:
	1. use async for analytics js file: http://www.google-analytics.com/analytics.js
	2. add media query to print.css
	3. Inline CSS
	4. Inline Google Fonts

*****

Steps taken for FPS project - main.js

1. Line 527, change so loop only runs to 50 rather than 200
2. Line 451, add var for pizzaContainer to avoid running document.querySelectorAll multiple times
	- Move all other new variables outside of "for" loop
3. LIne 509, move variables out of for loop


