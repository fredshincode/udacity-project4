## Website Performance Optimization portfolio project
Page speed above 90 Project 

1. Placed javascript and script tag at the end of the body to prevent parser blocking.
2. Added "media="print"" to the print.css to prevent render blocking. 
3. Inlined style css to prevent render blocking. 

FPS 60 on pizza.html 

1. Defined .randompizzacontainer as an array variable to prevent calling document.queryselector everytime on for loop. Similarly, defined dx and newwidth to prevent the same action be called on for loop. 
2. Removed scroll calculation outside of for loop to remove unecessary calculation each time
3. Lowered the amount of pizza from 256 to 25.  Sufficiently fills the screen. 
