# bgPreload.js
preload script for background images

#What does it do
This script looks for elements with the class preload (these elements should contain CSS background images) - it then adds them to the dom and listens for the load event on each. Once complete, it triggers a callback function that you pass it. 
