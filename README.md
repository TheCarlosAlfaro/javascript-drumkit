# JavaScript Drum Kit

A basic drum kit player built with vanilla Javascript

Credit goes to [Wes Bos](https://wesbos.com) for creating this amazing tutorial.

With the following features:

* When you hit the corresponding key it's goint to play the sound that's associated with that key.
* A short little css animation will take place.

[Click here for a live example](https://javascriptdrumkit.netlify.com/)

## Objectives

* [ ] Show how data attributes work
* [ ] Show a litte bit of css animation
* [ ] How to play sounds
* [ ] How to use animations

## Pre-Javascript

* [X] Open Dev tools and show how the .playing css class is working
* [X] Look into the styles.css and show the css animation rules
* [X] Explain the html structure with the .keys and .key classes
* [X] Explain how keyboard keycodes work. Use (keycode.info)
* [X] What is "data" attributes? and how are we using it?
 
 ## The actual Javascript

 * [X] Listen for 'keydown' event on window
 * [X] Demonstrate de event.keycode
 * [X] Check if theres is a sound on the page that matches the key that was pressed
 * [X] Select the corresponding audio element by using an attribute selector
 * [X] If there is no audio related to the key return
 * [X] Play audio
 * [X] Rewind audio to the start so it plays everytime you hit the key
 * [X] Select the corresponding key to add animation class
 * [X] Remove the class by using a transitionend event
 * [X] Listen to each key to when transitionend happens
 * [X] Create function to remove transition
 * [X] Pick the transform property name
 * [X] Return if event it's not equal to transform
 * [X] Remove class 'playing'
 * [X] Refactor code by creating a function called 'playSound'
