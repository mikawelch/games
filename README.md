# games

Games


1. Choose your own adventure

Create a normal HTML file named "adventure.html" with a script tag in the <head>
start with an alert setting up your story
i.e. "You're in a dark room. You see a door with a faint light underneath."
Prompt the user for input by offering them two choices
i.e. "Do you "open" the door or go back to "sleep"?
Save the user's input from the prompt to a variable
Make an if/else if/else statement to handle the 2 scenarios
If they chose open, if they chose sleep, or if they entered something else entirely  
INSIDE of of those blocks of code, prompt the user for input again and save that to a variable
Create another if/else if/else statement to handle this second scenario
This is a "nested" if/else
There's nothing special about nested if/elses except they are inside each other
Use console.log to log messages to users at the end of their path
See attached image for a visual aide
See adventure.html (Links to an external site.) in week 4 repo for example of nest conditionals



2. Rock/Paper/Scissors

Create an html file named "rps.html" with a script tag at the bottom of the <body> element
Place 3 images on the page using <img> tags
Put a <p> with an id of "winner" on the page
In your script tag, get references to all 3 images and the <p> using the Document Object  Model (document.getElementById, etc) and save them in variables
Randomly select an option for the computer by following the instructions in the rps.html (Links to an external site.) file of the Week4 repo in the Github organization 
Create a variable for the winner and leave it blank
Use an if/else if/else statement to determine the winner, and assign the value "YOU" or "COMPUTER" to the variable for the winner
Put the winner on the page using the .innerText property of the <p> variable  
