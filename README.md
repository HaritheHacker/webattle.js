# webattle.js

## What up

webattle.js is a sample multiplayer game created with Node.jsm HTML5 and related buzzwords.

## Big Plan

Create massive multiplayer much fun game using native browser technologies so it works on many different devices without a need to install anything.

## Dependencies

* connect - for serving files from server to client (bascially, just index.html for now)
* socket.io - for flawless client-server communication 
* BISON - for efficient serialization
* browserify - for serving same js files for both server and client side
* sprite.js - for rendering graphics

TODO: links to all libraries. For now jfgi, please.

## Trying out

If you already have git, node.js and npm

    git clone https://github.com/medwezys/webattle.js webattle
    cd webattle
    npm install
    node server.js

Point your browser to http://localhost:3000 

## Live Demo

Coming soon

## Changelog

0.0.1 Use proper package management. Thanks Saulius Grigaliunas.

0.0.0 First commit, each connected player gets to control little crappy guy in the screen. All players can see each other crappy little men!

