# NodeJS Authentication App
> A complete authentication app with login, logout, register, forget password, email verification(for added security), and access control. Can be used as starter for other Node.JS applications. using Node.js, Express, Passport, JWT, Mongoose, and more. 



login

![nr1](https://github.com/Speed46/nodejs-authorization/assets/101384882/87d1fc34-680e-4622-aa6a-c130882d2f6b)

register new user 

![nr6](https://github.com/Speed46/nodejs-authorization/assets/101384882/6329c7dc-9fe3-4706-b25f-7aa6fadbddd4)

authorization link sent to mail

![n2](https://github.com/Speed46/nodejs-authorization/assets/101384882/cf79bf1f-46e4-48d4-a577-e56b4b7abd34)

email verified redirect

![image](https://github.com/Speed46/nodejs-authorization/assets/101384882/34f05bb3-326b-48d1-9d22-0fac3cc34ece)


dashboard

![nr9](https://github.com/Speed46/nodejs-authorization/assets/101384882/5958b730-ef93-4a22-8369-d488d6a24d57)

unknown email signup

![nr7](https://github.com/Speed46/nodejs-authorization/assets/101384882/bddd4a83-4c2b-4055-843c-babbffc7ee60)

forgot password

![nr10](https://github.com/Speed46/nodejs-authorization/assets/101384882/c12fa3c0-3f8d-4c32-a906-7c44c90ea430)

reset password

![nr5](https://github.com/Speed46/nodejs-authorization/assets/101384882/831414cb-2931-4f1c-96ee-7a6f9654ce5a)




## Technologies Used
1.  NodeJS
2.  Express
3.  EJS
4.  MongoDB
5.  Mongoose
6.  PassportJS
7.  JWT
8.  Nodemailer


## Prerequisites
- Git
- NodeJS
- CLI

## Installation`

##### Into the project directory

`cd nodejs-auth`

##### Installing NPM dependencies

`npm install`

##### Then simply start your app

`npm start`



## Folder Structure

nodejs-auth <br>
├── assets <br>
│ --- ├── secure-icon.png <br>
│ --- ├── cyber-security-icon.jpg <br>
│ --- └── css <br>
│ -------- └── bootstrap.min.css <br>
├── config <br>
│ --- ├── checkAuth.js <br>
│ --- ├── key.js <br>
│ --- └── passport.js <br>
├── config <br>
│ --- └──authController.js
├── models <br>
│ --- └── User.js <br>
├── node_modules <br>
├── routes <br>
│ --- ├── auth.js <br>
│ --- └── index.js <br>
├── views <br>
│ --- ├── dash.ejs <br>
│ --- ├── forgot.ejs <br>
│ --- ├── layout.ejs <br>
│ --- ├── login.ejs <br>
│ --- ├── messages.ejs <br>
│ --- ├── register.ejs <br>
│ --- ├── reset.ejs <br>
│ --- └── welcome.ejs <br>
├── .gitignore <br>
├── package.json <br>
├── package-lock.json <br>
├── README.md <br>
└── server.js <br>
