`TO get started -->`
1. npm init a file 
2. npm i express
3. work on js file

`To start working with EXPRESS.js`
const express = require('express');
const bodyParser = require('body-parser');
const app = express();
const PORT = 3000;

`CRUD - get post delete update`
app.{get/post/delete}('url', fn)

`app.listen to start the server and have it listen for incoming requests on a specified port`
app.listen(PORT, ()=> {
    console.log("Server started on PORT", PORT);
});

