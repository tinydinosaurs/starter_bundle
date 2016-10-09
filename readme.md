# Super simple build with npm scripts

After fiddling around with Gulp builds, I decided to try my hand at npm scripts. This repo is the result.

## Features
* Watches sass, javascript, and html files for changes
* compiles sass to css
* compiles es2015 syntax and bundles javascript files
* Serves html, reloads page on change
* Includes app folder with starter files: scripts/entry.js, styles/main.scss, index.html

## Installation
* Clone this repo into your project folder
* Remove git history with rm -rf .git
* Run npm install to grab all the node modules
* Install your own dependencies
* Set up a nice repo for yourself using the the service of your choice
* `npm run start` to start the server and watch for changes

Currently not set up for linting or testing or really doing anything other than building simple javascript applications. It also probably has a few bugs. Really, I'm just storing it here for myself, but if you accidentally stumble across this repo, feel free to take it and use it as you please. If you do take it and like it, please star it for me!

## Future Features
* Compress image files and copy them to dist folder (currently nothing happens to images at all)
* Support for linting
* Support for testing
