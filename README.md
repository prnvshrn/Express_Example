# Express_Example
We can use EJS or Jade in Express apps. I have used EJS.
## Table of Content
1. ##[General EJS syntax] (#General EJS syntax)
## General EJS syntax
For variables use <%= title %> and for using javascript <% %>
## Including another file
Create a EJS file. This can be referred by include tag, like Django Template, in the following way.
``` <% include templates/header.ejs %> ```
## Adding a new file
Flow is kind of the same as in a Django application. 
1. Create an EJS file in views and its corresponding js file in routes. 
2. In app.js, add the file as a require module and also as an app.use variable.  
3. Make sure to include EJS file in the render function of the js file.
