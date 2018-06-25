## Project Title

A Platform Game

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing 

purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites

Visual studio code

## Executing

A step by step series of examples that tell you how to get a development env running

Create a file named Index.html 

Link the javascript file in the script source such as game.js and levels.js

Also link the css file styles.css

Inside the body tag, mention the onload="runGame(GAME_LEVELS, DOMDisplay)"
  
close the body and html.

Required scaling for the game is mentioned in the file game.js, such as Height,Width, and vector list are given through the 

function, also the grid sizeis also mentioned.

Player address is treated as "@"

Coins address is treated as "o"

The Lava address is treated as "=" or "v".

The scaling also represents the background of the game.

var x represents width and var y represents height

Create a javascript file named levels.js

And mention the game values inside var GAME_LEVELS =[]

And then check if (typeof module != "undefined" && module.exports)

And give module.exports = GAME_LEVELS;

Create a css file and mention all the background colors for the game, also mention the pixel size for width, height. Type of position,Overflow and margin for the game.

The colors are represented via RGB color values.

Break down into end to end tests

Used for testing the code to be properly executed in multiple browsers, and if they are compatible or not.

## Authors

Marijn Haverbeke

## Acknowledgments

Hat tip to anyone whose code was used

Inspiration

etc
