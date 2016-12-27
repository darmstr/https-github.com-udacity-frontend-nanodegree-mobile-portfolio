# Website Performance Optimization portfolio project

## Steps to run the site
* Go to the Github hosted page https://darmstr.github.io/mobile-portfolio/
* Site should be up and running
* If the Github hosted page doesn't work you can download the project files from the Github repository and open index.html

## Optimizations made to the site
* index.html images optimized, assets minified, and render blocking assets deferred.
* Scrolltop calculation put into a variable so the it doesn't have to be recalculated in the loop.  pizza.html scrolling down to 2ms or less
* main.js no longer iterates individually between pizza containers. Resizes in 3ms or less regularly.

