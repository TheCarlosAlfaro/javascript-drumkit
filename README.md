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

* [ ] Open Dev tools and show how the .playing css class is working
* [ ] Look into the styles.css and show the css animation rules
* [ ] Explain the html structure with the .keys and .key classes
* [ ] Explain how keyboard keycodes work. Use (keycode.info)
* [ ] What is "data" attributes? and how are we using it?
 
 ## The actual Javascript

 * [ ] Listen for 'keydown' event on window
 * [ ] Demonstrate de event.keycode
 * [ ] Check if theres is a sound on the page that matches the key that was pressed
 * [ ] Select the corresponding audio element by using an attribute selector
 * [ ] If there is no audio related to the key return
 * [ ] Play audio
 * [ ] Rewind audio to the start so it plays everytime you hit the key
 * [ ] Select the corresponding key to add animation class
 * [ ] Remove the class by using a transitionend event
 * [ ] Listen to each key to when transitionend happens
 * [ ] Create function to remove transition
 * [ ] Pick the transform property name
 * [ ] Return if event it's not equal to transform
 * [ ] Remove class 'playing'
 * [ ] Refactor code by creating a function called 'playSound'
