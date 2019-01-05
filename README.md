# JavaScript Drum Kit

A basic drum kit player built with vanilla Javascript

With the following features:

* When you hit the corresponding key it's goint to play the sound that's associated with that key.
* A short little css animation will take place.

[Click here for a live example](https://javascriptdrumkit.netlify.com/)

## Objectives

* [ ] Show how data attributes work
* [ ] Show a litte bit of css animation
* [ ] How to trigger sounds
* [ ] How to end animations

## Pre-Javascript

* [ ] Open Dev tools and show how the .playing css class is working
* [ ] Look into the styles.css and show the css animation rules
* [ ] Explain the html structure with the .keys and .key classes
* [ ] Explain how keyboard keycodes work. Use (keycode.info)
* [ ] What is "data" attributes? and how are we using it?
 
 ## The actual Javascript

 * [ ] Listen for 'keydown' event


## Deploy

* ✅ Deploy server with now
  * [x] Setup environment variables
    * [x] Database connection
      * process.env.MONGO_URI
  * ✅ Show mlab
  * [ ] Deploy with environment variable
    * now -e MONGO_URI=@meower-db
  * [ ] Add alias
* ✅ Deploy client folder with now
  * [ ] Set API_URL based on hostname