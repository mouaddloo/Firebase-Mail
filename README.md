# Firebase Mail #

Firebase mail, it is a mini school project consists of realizing a box of emails with the tendency computer by creating the project with Firebase and ECMAScript 6.

## Getting Started ##

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites ##

To use the project,you need to install

* ECMAScript 6 config (Babel + Webpack) : 
  http://ccoenraets.github.io/es6-tutorial/setup-babel/
* Firebase Tools : 
  https://firebase.google.com/docs/web/setup



## Running the tests ##

command line,to make ecmascript6 from java script
 
```
#!command

npm run babel
```
command line,to hosting and testing site in the internet

```
#!command

firebase deploy
```

## Built With ##

* [Firebase](https://firebase.google.com/) 
* [npm](https://docs.npmjs.com/) 
* [ECMAScript 6](http://es6-features.org/#Constants) 
* [Bootstrap](http://getbootstrap.com/) 

NB : this project built with 0% of PHP And 0% of JQUERY(*I used jquery of bootstrap for Modal)

## Firebase integration ##

### firebase include ###

```
#!HTML


<script src="https://www.gstatic.com/firebasejs/3.6.5/firebase.js"></script>
<script src="https://www.gstatic.com/firebasejs/3.6.2/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/3.6.2/firebase-auth.js"></script>
<script src="https://www.gstatic.com/firebasejs/3.6.2/firebase-database.js"></script>
```

### firebase config ###


```
#!javascript

var config = {
          apiKey: "AIzaSyA1c-aXzEQ67SFORIW8rK0bTrNgcNraXqQ",
          authDomain: "message-6c6ab.firebaseapp.com",
          databaseURL: "https://message-6c6ab.firebaseio.com",
          storageBucket: "message-6c6ab.appspot.com",
          messagingSenderId: "613677558045"
};
```

## Firebase Message API ##


```
#!javascript

FB.send = function (from) : for send a mail 
FB.resend = function (from) : for update a mail
FB.inbox = function (usermail) : for show received message 
FB.sentmail = function (usermail) : for show sended message 
```

## Author ##

Mouad DLOO 

## License ##

Open source
