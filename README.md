## Website Performance Optimization portfolio project

## Part 1: Optimize PageSpeed Insights

* The site is available on [github pages](https://keirsweeney.github.io/frontend-nanodegree-mobile-portfolio/index.html)
* And the [pizza page] too(https://keirsweeney.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html)
* Optimised all images using tinyjpg.com
* CSS minified with https://cssminifier.com/
* Added permatters.js inline in script tags

I used tinyjpg to optimise the images and remove bulk. Minified css using cssminifier and also added permatters.js inline to help with the load.


## Part 2: Optimize FPS for the pizza.html

* Define reusable variables in updatePositions, and also use getElementsByClassName. I added pizzas as a var and again using the getElementsByClassName I optimised the changePizzaSizes.
* Changed windowWidth variable to use getElementById rather than queryselector. Query selecting can be really heavy. Removed creating two variables from for loop 
* Using DRY principles where I could
* To add I could minify the JS too but then it would make it hard to see the changes made and removes readability.

For FPS counter I used this link to learn from :) [Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).  