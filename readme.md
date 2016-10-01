1- start off by doing $ npm i
2- If everything works you should be able to exec
$ npm run grunt

3- Install Typings if not already have
$ npm install typings --save

Now that we have typings installed, and we are referencing the main.d.ts definition file that Typings generates we are ready to build our TypeScript + Express + Node.js application.

$ npm run grunt
$ npm start

Don’t forget to recompile your TypeScript code into JavaScript, or use the grunt watch command:

$ npm run grunt watch

Once your TS is compiled, restart your server.
Bash

$ npm start

Now, load http://localhost:8080