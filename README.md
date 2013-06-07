# Yeoman-Angular-Haml

This seed project uses Yeoman with Angular and HAML. It's just 'yo angular' with CoffeeScript and HAML instead of JavaScript and HTML. See commit history for changes to Gruntfile.js for grunt-haml.

See also: [generator-angular](https://github.com/yeoman/generator-angular)

## Assumptions

* brew
* nodejs
* chrome

## Installation

First make sure brew is current:
      
    brew update

And same for nodejs
    
    brew upgrade node

Install yeoman:

    npm install -g grunt-cli bower

Install dependencies:
    
    cd yeoman-angular-haml
    npm install
    bower install

## Test (Karma)

    grunt test

## Run

Launch the server:

    grunt server


Edit app/view/main.html.haml and watch the LiveReload goodness!




