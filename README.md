# burger
Burger - Node Express Handlebars

Umass Amherest Coding Bootcamp burger assignment

Overview

In this assignment, I was asked to create a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. I followed the MVC design pattern; using Node and MySQL to query and route data in the app, and Handlebars to generate the HTML.



Installation Instructions

Fork this repo and clone the forked repo to your computer. You will need node.js installed on your system.
At the command line navigate to the apps folder and run npm install, this will install the npm dependencies from the package.json file.
Install mysql on your machine, if necessary -> https://www.mysql.com/
Set up your own localhost connection. In the /config/connection.js file in this repo, update the connection settings as follows:
var connection = mysql.createConnection({
  host     : 'localhost',
  user     : <enter your user information>,
  password : <enter your password>,
  database : 'burgers_db'
});
In mysql Workbench, import schema.sql and seeds.sql from the db directory in this repo and run them to upload the db onto your localhost.
Then run node server.js the console should log the port number the app will be on (currently 3000).
Go to your browser and type http://localhost:3000/ into the address bar to bring up the app.
