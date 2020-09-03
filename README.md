# Matcha

A dating site that allows users to connect with others based on romantic
preference/interests and geo location.

## Requirements

* npm v6.13.4 : https://www.npmjs.com/get-npm
* Node v12.16.1 : https://nodejs.org/en/download/MAMP 
* MAMP : https://bitnami.com/stack/mamp

## Installation

### How to download the source code

* Navigate to https://github.com/tmuramba/matcha.git, click on clone or download
* Once you have downloaded the source code navigate to the folder Matcha
* run npm install to install all of the modules needed for this project

### How to set up
    
* Download MAMP from the bitnami website
* Open the manager-osx. Go to the Manage servers tabs and make sure mysql database is running. If not press Restart.
* Click configure, this should show details about the port.

### How to run

* Run npm run start to start the server
* navigate to localhost:3000 in your browser to open the website

## Code breakdown

* Front end technologies
    * HTML
    * CSS
    * JavaScript
    * EJS
    * Bootstrap
* Back end technologies
    * Node JS
    * Express
* Database managment systems
    * MySQL
    * phpmyadmin
    
### App Structure

* /config
    * auth.js
        * this contains code to check if the user is logged in 
    * google.js
        * this contains code that allows the user to be able log in or sign up through google
    * keys.js
        * this contains code with the passwords to the database
    * passport.js
        * this contsins code that authenticates a users account if it is valid or not
    * table.js
        * this contains code that creates tables to store the data we get from the users
* /public/scripts
    * calcAge.js
        * this contains code to calculate the age of the user  when given a date of birth
    * getDistace.js
        * this calculates the distance between users in the matching process
* /routes
    * chat.js
        * this contains code that allows users to send messages to eeach other 
    * forgot.js
        * this contains code that allows a user to recover their account if they have forgoten the password
    * index.js
        * this intializes the web application
    * matches.js
        * this contains code to allow users to be matched dued to thir intrests and location
    * others.js
        * this has some query statements for the profile pictures of the users
    * search.js
        *this allows for users to look for other ussers only if the know the other users username
    * update.js
        * this contains code to allow the user to be able to change thire details such as username password etc. 
    * verify.js
        * this contains code that allows us to verify the users by sending them a link to their email
* /views/flash
    * msg.ejs
        * this contains code for displaying errors or success messages to the user 
### Testing

https://github.com/wethinkcode-students/corrections_42_curriculum/blob/master/matcha.markingsheet.pdf I used this pdf to test my application both the test and the expected results are included
