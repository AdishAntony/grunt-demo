# grunt-demo
Grunt demo app

------------------------------------------------------
GRUNT-The JavaScript Task Runner
This app is to show how grunt can be used to minifying a js file.

Grunt and Grunt plugins are installed and managed via npm, the Node.js package manager. Grunt 0.4.x requires stable Node.js versions >= 0.8.0.

Before setting up Grunt ensure that your npm is up-to-date by running npm update -g npm (this might require sudo on certain systems).

To test, run the command - 
npm test

This will execute 'grunt default' task. 
The default task will minify the index.js file and write into index.min.js file in build directory.
The default task will also run 'printSomething' task (custom task) that will print something in console log.