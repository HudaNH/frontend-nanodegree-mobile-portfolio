## Website Performance Optimization portfolio project


## Description
The task here was to optimize a mobile web app in order to make it load faster, reduce download speed and data traffic. Another issue that the project had originally, was the slow screen scroll speed and changing pizza size function.
 

## Installation
 

### Using git
1. Click "Clone in Desktop" 
2. Open git bash
3. git clone the url from git bash.
4. Open the folder.
5. pen index.html on your preferred browser.
 
### Using a zip file

1. Click "Download ZIP" and unzip the file.
2. Open the folder.
3. Open index.html on your preferred browser.

## Optimizations
 
### index.html
1. inlined css
2. usage of async for js that does not modify dom
3. minify css/js/html assets
 
### pizza.html
1. minify css/js/html assets
 
### main.js
1. factored out loop variables for offsetWidth in changePizzaSizes and size that were being calc'd over and over.
2. changed document.querySelectorAll to document.getElementsByClassName in the function changePizzaSizes.
3. in updatePosotions function, factored out for loop for phase calculation.
4. reduced number of pizzas created on init.