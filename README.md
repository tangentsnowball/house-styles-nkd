TS House styles NKD
====================

A bare-bones version of Tangent Snowball's house styles repository for rapid prototyping  

This repository is based on the [TS House Styles](https://github.com/tangentsnowball/house-styles)


Use of Grunt
------------  

There is a standard Grunt installation within this repository to make rapid prototyping much quicker for the house styles. All you need to do is:  
* Install Node & Grunt (http://gruntjs.com/getting-started)  
* Run `npm install`  
This will install all the Grunt dependences (The node_modules folder that is generated when you run this command should be created on a case-by-case basis and not pushed to a repository)  
* Run `grunt`  
  
This will open up a tab in your browser, running a server at `localhost:9000`. It will also be watching for any changes to the HTML, JS, and LESS files and will:  
* Compile & compress CSS files  
* Reload the page