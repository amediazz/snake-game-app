# snake-game-app

This application is a snake game that uses javascript libruary `Pharser.js`
That runs on the browser

## Tabele of content:

* [Table of content](#tabele-of-content)
    * [What is Phaser.js?](#what-is-pharserjs-)
    * [Project setup](#project-setup)
    * [Game config](#game-config)
    * [Scene State and Helper Functions](#scene-state-and-helper-functions)
    

## What is pharser.js ?:
pharser js is a free javascript library for 2D games
you dont need to built a system or a game engine installer
you can start with an html file and one javascript file

pharser organize codein three steps 

- [1] load assets in `preload` 
- [2] set up images and variables in `create` 
- [3] update your gamein each frame `update`

## Project setup 
create two files index.html and main.js
[x] - `index.html` will load the pharser from the CDN
[x] - `main.js` will create the game and attached to the div 

## Game config

Snake is easiest on a grid. You choose a tile size and a number of tiles wide and high. You also define colors for the background, the snake, and the food. Then you create a Phaser game config that points to your scene functions.

The config tells Phaser to create a canvas, set its size, and use your scene functions. Phaser.AUTO selects WebGL if possible and falls back to Canvas.

## Scene State and Helper Functions

You need to store the snake’s body as grid cells, the rectangles that draw those cells, the direction of travel, the queued input, the food cell, the score, and the movement timer. A few helper functions keep the math clean.


