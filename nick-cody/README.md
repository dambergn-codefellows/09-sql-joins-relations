# Lab09 - SQL Joins Relations

**Author**: Nick, Cody
**Version**: 9.3.1 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->
This application displays data contained in a JSON file and allows the user to sort through them by author or category.  They also have the ability to add new articles that are stored in a PostgreSQL database.
## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
Clone the github repository to the location in which you would like to run the web server from.  Install the nodejs runtime environment for your OS.  Then install all NPM dependencies required by the server.  Then install the PostgreSQL server package and create a default database in which the server can use to store new articles.  In the server make sure the conString field reflects the name of the database you created.  Also take note of the port that has is in use for the server, You may change it to whatever you like if you wish.  Through the termial navigate to the folder that contains the server.js file.  Then execute with "nodejs server.js" without quotes.  Once the server starts it will tell you which port the server is running on.  Then from a web browser go to localhost:port replace the word port with the number port the server is listening on.
## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
PostgreSQL, Nodejs, NPM modules (pg, fs, express, body-parser, "optional: nodemon").
## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:
12-30-2017 3:00pm - Server can now access PostgreSQL database to sort JSON data and can store new article data.


## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
