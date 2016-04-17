# learningjQuery

## Overview

We're going to use jQuery to add some functionality to our order form on our LadyDevs Restaraunt website, and implement plugins to make our site look nice. Be sure to look through the examples in the linked documentation and try to figure it out on your own!

## Using jQuery to Manipulate our form


First, you'll need to include links to the jQuery library and your scripts files on the index.html. Remember, order matters! You'll be adding jQuery code to your my-scripts.js file. 
[hint](https://api.jquery.com/ready/)


1. Make clicking the "valiate" button change the input text color to red. [hint](http://api.jquery.com/css/)
2. Make clicking the "show error message" button append the following warning text to the .warning div: "These fields are required to complete order form". [hint](http://api.jquery.com/append/)
3. Make clicking the "show brunch" button show the hidden brunch div. [hint](http://api.jquery.com/show/)
4. Make clicking the "hide brunch" button hide the now showing brunch div. [hint](http://api.jquery.com/hide/)
5. BONUS CHALLENGE: Make clicking the "order ready" button get the value from the item box and display it at the top of the page inside an 'h1' tag. 

## Adding Plugins

We're going to add a [slider](http://bxslider.com/) to our page to showcase our amazing brunch items. Checkout the "add-slider" branch from this repo, we'll do our work in there. Feel free to look through the answers to the previous tasks as well. 

1. Add the required files for [BX Slider](http://bxslider.com/) to your index.html
2. Call the BX Slider on your slider element. 
3. Change the mode of the slider to 'vertical'. (http://bxslider.com/examples/vertical-slideshow "hint")
4. Add captions to your images. (http://bxslider.com/options "hint")