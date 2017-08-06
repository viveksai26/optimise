## Website Performance Optimization portfolio project

##Changes made in index.html
1.Removed google fonts
2.inline css
3.async analytics.js
4.added media = print for print.css

##Changes made in main.js for pizza.html
1.function changepizzasize has been modified to a simplier function and dx calculation function is removed.
2.In function updatepositions inside first loop document.body.scrollTop waas repeating itself inside the loop that has been shifted outside the loop. In second loop the no of moving pizzas has been reduced from 200 to 25 this causes increase in performance.
3.pizzeria.jpg image has been compressed.