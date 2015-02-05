## Website Performance Optimization portfolio project

To run part 1 of this project, open index.html from your browser. To run part 2 of this project, navigate to views/pizza.html

### Opitimizations for index.html

1. added "async" to google analytics
1. replaced google web fonts, due to size, with regular font call
1. Combined styes in style.css
1. Inlined CSS for page components that are above-the-fold
1. Lazy loading the CSS based on code provided by Google's PageSpeed Team
1. optimized pizzeria.jpg by reducing size and renaming to pizzeria-small.jpg, as the original was used elsewherecss
1. added media print to print style

### PageSpeed Opitimizations for pizza.html

1. resized pizzeria.jpg
1. added viewport meta tag
1. added baseline font size to body tag in style.css
1. resized pizza.png
1. Used https://marijnhaverbeke.nl/uglifyjs to minify main.js

### 60FPS and Page Scroll Opitimizations for pizza.html

* I extrapolated the static items out from updatePositions() and changePizzaSizes() from the for-loops in those functions
* I used the javascript function, requestAnimationFrame, to help attain 60FPS

### Note:

My lines of code in main.js are as follows:

1. 451 - 462
1. 507 - 535
1. 553
1. 572