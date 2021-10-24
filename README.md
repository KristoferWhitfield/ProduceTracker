# ProduceTracker

This application allows the user to see what fruits and vegatables are in season for the current month. Then they can save it to a list
where it can be deleted at anytime.

![screenshot](https://raw.githubusercontent.com/KristoferWhitfield/ProduceTracker/main/screen.JPG)

## Hows It's Made:

Made using HTML, CSS, Javascript, Node.js, JSON, Express, EJS, MongoDB.

This project uses getMonth method to find the numerical month and enter it into a switch case conditional. Based on the month, it'll pull the the correct
produce for the month from an object and using the get method, render it in the profile.ejs. The database stores the users saved choices on another list. 

