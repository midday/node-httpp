node-httpp is the part of HTTPP, that stands for HTTP over UDP and bring Web in P2P style against client/central-server.

It consists of three modules: udt.js, httpp.js, httpps.js, that keeps the same api like net.js/http.js/https.js.

It's simple to use node-httpp:
1. replace net with udt, http with httpp, https with httpps when require net/http/httpps modules.
2. well done.

To build it manually, clone the repository and checkout v0.8-httpp branch firstly, then do steps as below.

Evented I/O for V8 javascript. [![Build Status](https://secure.travis-ci.org/joyent/node.png)](http://travis-ci.org/joyent/node)
===

### To build:

Prerequisites (Unix only):

    * Python 2.6 or 2.7
    * GNU Make 3.81 or newer
    * libexecinfo (FreeBSD and OpenBSD only)

Unix/Macintosh:

    ./configure
    make
    make install

Windows:

    vcbuild.bat

### To run the tests:

Unix/Macintosh:

    make test

Windows:

    vcbuild.bat test

### To build the documentation:

    make doc

### To read the documentation:

    man doc/node.1

Resources for Newcomers
---
  - [The Wiki](https://github.com/joyent/node/wiki)
  - [nodejs.org](http://nodejs.org/)
  - [how to install node.js and npm (node package manager)](http://joyeur.com/2010/12/10/installing-node-and-npm/)
  - [list of modules](https://github.com/joyent/node/wiki/modules)
  - [searching the npm registry](http://search.npmjs.org/)
  - [list of companies and projects using node](https://github.com/joyent/node/wiki/Projects,-Applications,-and-Companies-Using-Node)
  - [node.js mailing list](http://groups.google.com/group/nodejs)
  - irc chatroom, [#node.js on freenode.net](http://webchat.freenode.net?channels=node.js&uio=d4)
  - [community](https://github.com/joyent/node/wiki/Community)
  - [contributing](https://github.com/joyent/node/wiki/Contributing)
  - [big list of all the helpful wiki pages](https://github.com/joyent/node/wiki/_pages)
