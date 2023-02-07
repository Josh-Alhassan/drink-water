# Project Title: Drink Water
This project is aimed at tracking glasses of water, and I have a goal of 2 meters. This project is aimed at exercising my knowledge of the JavaScript DOM manipulation.

## Technology
This project is built purely with HTML, CSS, and JavaScript.

## Thought Process

### HTML
What I did first was to create a single heading 1 with the content of **"Drink Water"**. Also created a heading 3 with a content of **"Goal: 2 Liters"**.

Next, I created a parent div with a class name of "cup", a nested child div with a class and id of "remained". This div contained a span tag which houses the number of liters remaining, and a small html tag with the content "remained".

Furthermore, I created another parent div with 8 nested direct divs to represent each smaller cup.

### CSS
I imported a "Montserrat" from google font api, then applied basic css styling to all target html classes and tags. I used ":root" to store re-used CSS properties in a variable.

### JavaScript
Firstly, I selected all the DOM elements. I Looped through the cups elements using a forEach loop and added an event listener. I created a function called "highLightCup" which accepts an argument of current index. A conditional logic was coded in the function's body. If the number of small cups are full and the next cup is not full, the current index of the small cup element should be decreased by one.

I looped through the smallCups elements using a forEach which accepts a callback function with parameters; current inex and a cup element. If the current cup index is less than the highlted cup index it should fill the cup, else it should empty the cup.

A function "updateBigCup was created to determine the measurement of water needed to fill the overall big cup with the number of liters remaining and percentage level of water.

### Project Link
This project is hosted on netlify.
