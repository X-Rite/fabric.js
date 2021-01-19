This fork of fabric.js is needed to build a version with only the needed moduled, and including the one to support modules.

To build the package you need uglify as global:
npm install -g uglify-js

Run the following command to build the dist folder with specified modules:
node build.js modules=ALL exclude=node,easing,freedrawer,animation no-strict no-svg-export