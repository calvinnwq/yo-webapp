## About ##

Just a basic webapp using [yeoman](http://yeoman.io/) with:

* [generator-webapp](https://github.com/yeoman/generator-webapp#readme) as the scaffolding
* [grunt-cli](http://gruntjs.com/) as the build system
* [bower](http://bower.io/) as the package manager


## Dependencies ##

Requires NodeJS. Can be installed with Homebrew

    brew install node

Requires the following dependencies

* yo
* bower
* grunt-cli
* generator-webapp

Run the following to install the dependencies using npm:

    npm install -g yo bower grunt-cli generator-webapp


## Get Started ##

Run the following:

    npm install & bower install


## Start Development Server ##

This command starts a web server on localhost:9000. It injects a web socket
connection to watch updates of source files and trigger reloading the web
page if updated.

    grunt serve