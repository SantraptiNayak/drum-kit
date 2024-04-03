# drum-kit
The "Drum Kit" website is a musical interactive platform featuring buttons corresponding to drum sounds, allowing users to play drum beats by clicking or pressing keys. It offers a visually appealing design with dynamic animations and sound effects for an engaging user experience.


JavaScript (JS) is used in the provided code to add interactivity and dynamic behavior to the "Drum Kit" web application. Here's a breakdown of how JavaScript is utilized in the code:

# Event Listeners:
addEventListener("click", function() {...});: Adds a click event listener to each drum button. When a drum button is clicked, it triggers a function to play the corresponding sound and animate the button.
document.addEventListener("keypress", function(event) {...});: Adds a keypress event listener to the entire document. When a key is pressed, it triggers a function to play the corresponding drum sound and animate the button.

# Functions:
makeSound(key): This function takes a key/button as an argument and uses a switch statement to determine which drum sound to play based on the key/button pressed. It creates a new Audio object for each drum sound and plays it.
buttonAnimation(currentKey): This function takes the current key/button as an argument and adds a "pressed" class to the corresponding button to animate it. It then removes the "pressed" class after a short delay using setTimeout.

# Dynamic Content Manipulation:
var buttonInnerHTML = this.innerHTML;: Retrieves the inner HTML (i.e., the text content) of the clicked button, which corresponds to the drum sound key.
var activeButton = document.querySelector("." + currentKey);: Dynamically selects the button with a class matching the current key to apply the animation.

# Error Handling and Default Behavior:
default: console.log(key);: Provides a default case in the switch statement to log any unrecognized keys/buttons to the console, helping in debugging or handling unexpected inputs.

# link: https://santraptinayak.github.io/drum-kit/

# snapshot:


![1](https://github.com/SantraptiNayak/drum-kit/assets/107788748/9d956271-20c1-4023-a99e-d03398225d66)
