# Steps to run Hello world program in nodemon
```
cd your/dirPath/
```
```
npm init
```
```
npm i express
```
Create index.js
```
npm i nodemon -g
```
Run the hello world program file with nodemon:
```
var express = require('express');
var app = express();

app.get('/', function(req, res){
   res.send("Hello Kelzang!");
});

app.listen(3000);
```
```
nodemon index.js
```
