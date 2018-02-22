# Kilovolt Blog - Lab 03

**Author**: Josh West and Suzanne Richman

**Version**: 1.0.9

**UPDATES** 1.0.6 and 1.0.7, 1.0.8 and 1.0.9 were completed by Suzanne Richman 

## Overview

We want users to be able to read content easily on mobile and desktop browsers while selecting content by author or catagory, if desired and to view the blog as a multipage site (despite actually being a single page).


## Getting Started

The user would need to 
* Create index.html
* Get the icons from IcoMoon
* Get the normalize.css from github.com/necolas/normalize.css
* Search and find images of bacon, baseball, and cats
* Add filler text
* Build CSS files according to SMACSS methodology
* Include link to jQuery library (CDN)
* Create the articles as objects within an array with consistent property values
* Create a constructor function to make the article array accessible to the constructor’s method
* Use jQuery to access and clone HTML elements of the DOM and populate those elements with content from the article array
* Create forEach loops to generate new object instances and then append them to the DOM
* Create an array of objects to hold the content generation for the DOM for each object.
* Create a JS file to generate a more interactive view of the DOM (selecting authors, catagories and hiding/showing full articles as well as navigating the long page as if it was a multipage website).

## Architecture

We used IcoMoon icon font for navigation icons. We included the jQuery library. We used Chrome to analyze and inspect. Project is built on HTML, CSS,and JavaScript.

## Change Log

02-15-2018 9:50 am - Commit to add and move readme, add normalize css, and update index.html. also updated css for improved styling.

02-15-2018 10:45 am - Commit updates to articleView.js

02-15-2018 12:00 pm - Commit updates to articleView.js and article.js working on filter population and handling.

02-15-2018 12:53 pm - Commit updates to articleView.js and article.js working on filter population and handling and attempted nav. Only got filter population working, but it breaks when filter handler is commented in.

02-15-2018 9:55 pm - Fork and clone to create my own solution to the lab, with Allie's permission given earlier today in Slack.

02-17-2018  11:33 pm - Worked on and fixed layout.CSS for styling of about section. Fixed main navigation in articleView.js. Updated index.html for placement of teaser/show less. Got teaser to work, but not showing of article or show less. 

02-18-2018 2:41 pm - Finally got the teaser (readmore/show less) working correctly. excited to have all tasks and functionality working as expected for users.

02-21-2018 10:50pm - Found my lost code. Lost code didn't work as expected. Console logs not showing. Chatted with Haron on the setTeasers function, per that chat found animate and scrollTop. With tests and console logs, still not working. FOUND MISSING ")"! And now it all works. Also updated base css so images resolve more cleanly in both mobile and desktop views.

## Credits and Collaborations

* Thanks to our instructors and TAs. 
* We referenced the jQuery cheat sheet: https://oscarotero.com/jquery/
* We used a normalize.css file found here: github.com/necolas/normalize.css
* We referenced our text book: Jon Duckett - JavaScript and JQuery.