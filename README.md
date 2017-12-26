# chat-app

chat-app is template for chat application that use firebase cloud messaging as its core feature.
This template is easy to use in a website because the id of sender and receiver is needed in the url

### how to use

This chat application use node.js as the main backend language and angular.js for the front-end 
main language. There are four main folder in the app: chat-angular, chat-mongo, firebase-mongo,
and chat-service/firebase-server. 

### Install dependencies

Run `npm install` on each of the folder to install dependencies

### Run the chat-app

1. run `npm start` for chat-angular folder 

2. run `node app.js` for chat-service/firebase-server folder

3. run `node index.js` for the rest

then you can run them in chrome and firefox to start chatting. The sender in one browser
will be the receiver in the other browser and vice versa

example of URL

  Firefox: http://localhost:8000/index2.html?sender_id=1&receiver_id=2
  
  Chrome: http://localhost:8000/index2.html?sender_id=2&receiver_id=1
