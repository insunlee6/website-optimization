## FEND Project 4: Website Performance Optimization portfolio project

The objective of this project was to optimize the speed of the online portfolio created by the course developer, Cameron Pittman. 

### Getting started

Original version of the project can be found here:
Link: http://cameronwp.github.io/udportfolio/
Repo: https://github.com/udacity/frontend-nanodegree-mobile-portfolio

Optimized version of the project can be found here:
Link: https://insunlee6.github.io/website-optimization/
Repo: https://github.com/insunlee6/website-optimization

If you are cloning the repo or download the zip file, open the index.html browser in the browser to see Part 1 of the project. To view Part 2, open the "views" folder and open pizza.html in the browser.

#### Part 1: Optimize PageSpeed Insights score for index.html

# Specifications
Make optimizations to index.html so that it achieves a PageSpeed score of at least 90 for Mobile and Desktop.

# Optimizations
* Compressed and resized images using [Image Optimizer](http://www.imageoptimizer.net/Home.aspx)
* Inlined minifed CSS using CSS Minifier [tool](https://cssminifier.com/)
* Added async attribute to Google Analytics and Google Fonts scripts

# PageSpeed Insights Score
* 95/100 Desktop
* 94/100 Mobile

#### Part 2: Optimize Frames per Second in pizza.html

# Specifications
Optimizations made to views/js/main.js make views/pizza.html render with a consistent frame-rate at 60fps when scrolling.
Time to resize pizzas is less than 5 ms using the pizza size slider on the views/pizza.html page.

# Optimizations
* Changed querySelector to getElementById
* Changed querySelectorAll to geElementByClassName
* Moved DOM selectors and declared variables outside of for-loops
* Reduced number of pizzas movingPizzas to 50
* Referenced this [tutorial](https://www.html5rocks.com/en/tutorials/speed/animations/) on how to improve animation performance
* Following tips found [here](https://www.sitepoint.com/introduction-to-hardware-acceleration-css-animations/), CSS attributes   were added to .mover 
* Replaced basicLeft with style.transform and style.left for their respective codes

