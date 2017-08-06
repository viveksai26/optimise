## Website Performance Optimization portfolio project

This website has been optimised for performing at 60fps, below there are various steps that has been performed to run this website at 60fps.

There are two parts in this repository cam's profile and other one is pizza website. Cam's website can be opened using [cam's portfolio](index.html) index.html and pizza [pizza](views/pizza.html).


To check the performance of the website we need to run these files on a server, this can be accomplished by running a python server or downloading fenix server.

## Changes made in index.html
1. Removed google fonts.
2. css has been inlined for better performance.
3. Requesting analytics.js asynchronously.
4. added media attribute for print.css so that it will only be downloaded when print instruction is given.

## Changes made in main.js for pizza.html
1. function changepizzasize() has been modified to a simplier function.

2. dx calculation function is removed because this was doing so much unnecessory operations.

3. In function the updatepositions() the first loop document.body.scrollTop was repeating so this has been shifted outside the loop.
4. In second loop the no of moving pizzas has been reduced from 200 to 24 this caused an increase in performance.
3. pizzeria.jpg image has been compressed.

## Results
The following results are obtained after making the above changes index.html(90/100) and pizza.html running at 60fps.