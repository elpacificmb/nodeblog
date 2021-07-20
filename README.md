# nodeblog
A blog with Nodejs

# download node and mongodb
## nodejs
https://nodejs.org/en/
## mongodb
https://www.mongodb.com/try/download/community

## set up server
npm init -y

## install dependancies
npm i express mongoose ejs

## install dev dependancies
npm i --save-dev nodemon

## create a script in package.json
"start": "node server.js"
"dev": "nodemon server.js"

## start the server
node run dev

## install other dependancies
npm i marked slugify
npm i method-override
npm i dompurify jsdom