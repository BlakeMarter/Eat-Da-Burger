# __Eat-Da-Burger__

## __Table of Contents__
* Overview
* Technologies
* Local Installation
* Future changes

## __Overview__
Are you hungry for a delicious burger?! Eat! Da! Burger!

Eat-da-burger is an app that lets you create any delicious burger that you would like, and devour it! Add a burger to the list, which adds it to the mySql database. Click the "Devour it!" button, and the burger gets added to the devour list, and changes the value of the burger from devour to devoured in the database. 

## __Technologies__
* HTML
* JavaScript
* JQuery
* MySQL
* Express
* Express Handlebars
* Node.js
* #### __NPM Requirements__
  - express
  - path
  - body-parser
   ```
   var express = require("express");
   var path = require("path");
   var exphbs = require("express-handlebars");
   var bodyParser = require("body-parser");
   ```

* Use of the MVC data structure.
  ```
  .
  ├── config
  │   ├── connection.js
  │   └── orm.js
  │ 
  ├── controllers
  │   └── burgers_controller.js
  │
  ├── db
  │   ├── schema.sql
  │   └── seeds.sql 
  │
  ├── models
  │   └── burger.js
  │ 
  ├── node_modules
  │ 
  ├── package.json
  │
  ├── public
  │   |── assets
  │   |    ├── css
  │   |        └── burger_style.css
  │   └── images
  │       └── burgericon.png
  │   
  │
  ├── server.js
  │
  └── views
      ├── index.handlebars
      └── layouts
          └── main.handlebars
  ```

## __Local Installation__
* #### __Step 1: Git Clone__
    Clone the Eat-Da-Burger App to your local computer by opening your terminal, navigating to the folder you want to store it in and input:
    ```
    git clone https://github.com/BlakeMarter/Eat-Da-Burger.git
    ```
    The Eat-Da-Burger App and its files should now be in your project folder.


 * #### __Step 2: Install Reaquired NPM's__
  
      - Navigate to the correct JS file in your terminal and input `npm install` or `npm i`.

## __Demo__

You can check out the demo on heroku!


 https://floating-stream-66938.herokuapp.com/
