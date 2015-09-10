SCOTCH CHAT
======================

##Overview

This is a demo for an article on [Scotch](https://scotch.io/tutorials/a-realtime-room-chat-app-using-node-webkit-socket-io-and-mean)

##Installation
1. `git clone` this repository and cd to `scotch-chat-main-app` directory.
2. Run `npm install` command to install dependencies.

###Slush, bower and gulp
1. `npm install -g slush gulp bower slush-wean` to install slush, gulp and bower.
2. Run `bower install` to install the bower dependencies

##Running the application
`gulp run` in the CLI will get you running and with an internet connection you will be connected to the chat server

##Building the application
`gulp build --{{platform}}` e.g. `gulp build --win` or `gulp build --linux` or `gulp build --mac` to generate an executabe file so you do not have to go through gulp process to run
