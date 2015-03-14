WELCOME TO MY PROJECT 4!!

I’ve hosted my site with github, and it can be accessed at: http://mfranzese24.github.io/ for testing purposes.
You can see my github repository at https://github.com/mfranzese24/frontend-nanodegree-mobile-portfolio to view two separate directories for each production and source code.

Please see below for some of the steps I’ve used to optimize the site:


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

1. Line 531, change so loop only runs to 50 rather than 200
2. Line 452 - 459: move variables outside for loop, using "getElementsByClassName" rather than "querySelectorAll"
3. Use backface-visibility: hidden hack in style.css to decrease paint time


