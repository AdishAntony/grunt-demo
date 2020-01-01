# grunt-demo
Grunt demo app

------------------------------------------------------
This app is to show how grunt can be used to minifying a js file.

To test :
npm test

This will execute 'grunt default' task. 
The default task will minify the index.js file and write into index.min.js file in build directory.
The default task will also run 'printSomething' task (custom task) that will print something in console log.