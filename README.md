Mobile Portfolio

To open the portfolio, open up the index.html in a browser.  The other pages are
 linked from index.html.

Portfolio Optimizations

In the file main.js for pizza.html, I took the document.body.ScrollTop and 
document.querySelectorAll out of the loop as it too expensive to run every time 
the loop is entered as well as take out the equations that did not have to be 
computed inside of loops.  In respect to those two changes in code, page 
rendered and refreshed quicker.

As for the index.html, I got a 96/100 from Pagespeed Insights.
To do get this rating, I inlined the css from style.css and kept the print.css 
from being read unless the website was being printed.  I also added async calls
 for the scripts, optimized the images and compressed the html to minimize the 
 size of the html file.  But as one of the pictures is used on another page, I 
 optimized one but kept the other a little larger for the pizza.html page.


https://developers.google.com/web/fundamentals/performance/
https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html 
