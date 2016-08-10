## Website Performance Optimization portfolio project
Page speed above 90 Project 

1. Placed javascript and script tag at the end of the body to prevent parser blocking.
2. Added "media="print"" to the print.css to prevent render blocking. 
3. Inlined style css to prevent render blocking. 
4. To see the pagespeed insight, go to https://developers.google.com/speed/pagespeed/insights/ and insert my website https://fredshincode.github.io/udacity-project4/ on the fill form. 

FPS 60 on pizza.html 

1. Defined .randompizzacontainer as an array variable to prevent calling document.queryselector everytime on for loop. Similarly, defined dx and newwidth to prevent the same action be called on for loop. 
2. Removed scroll calculation outside of for loop to remove unecessary calculation each time
3. Lowered the amount of pizza from 256 to 40.  Sufficiently fills the screen. 

Getting my website online. 

1. Go to github.com. 
2. Create a new repository and make a readme file. 
3. Add a new branch gh-pages and set it default. 
4. Upload my website file and go to setting to see my github page url. 

