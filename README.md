# Microsoft-Teams-Clone

This is a video calling app with live chat feature. The app is developed using node.js framework of Javascript. To host a video chat, a server has been created using express.js. Now, to respond to with an HTML file on the server, I used EJS(Embedded Javascript). Now, for each new user, a unique random URL will be created with the help of UUID library. A video calling app is based off Real-time communication. Users send their audio and video stream to all the other users. This is made possible with peer.js. For impementing WebRTC on the server (for communication between users and server) , I used socket.io.


# TO RUN THE PROJECT LOCALLY : 
1)Download all files 
2)Change the option of "PORT" in the script.js file from 443 to 3030 
3)Run - npm install nodemon --save-dev (install nodemon)
4)Run - npm install express (install express.js)
5)Run - npm install ejs (install ejs)
6)Run - npm install socket.io (install socket.io)
7)Run - npm install peer.js
8)Run - nodemon server.js 
9)Go to localhost to check it out.

# THE APP IS DEPLOYED ON HEROKU (ON THE FOLLOWING LINK):
https://calm-wildwood-97815.herokuapp.com/
