# Eat Da Burger!

<h1>Description</h1>

Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.

<h3>Getting Started</h3>

<h3>Technologies Used:</h3>
1.MySQL
2.Node .js
3.Express
4.Handlebars
5.ORM


<h1>Code Explanation</h1>

- Our main file, which houses most of the dependencies that we'll be using and the initial server set-up, is server.js

- We set up and populate our database with schema.js and seeds.js

- Then, we create our connection to the database in connection.js

- We develop our ORM to run simpler methods to query database (read, write, and update)
Our controller takes in the data response from the queries, and then routes and renders it via Handlebars, resulting in a fully functional app

- We have our GET request, which retrieves burgers; POST request, which adds burgers; and PUT request, which updates the status of burgers from not devoured to devoured