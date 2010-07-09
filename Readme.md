
# EJS

Embedded JavaScript templates.

## Installation

    $ npm install ejs

## Features

  * Complies with the [Express](http://expressjs.com) view system
  * Static caching of intermediate JavaScript
  * Escapes html by default with `<%= code %>`
  * Unescaped buffering with `<%- code %>`

## Usage

    ejs.compile(str, options);
    // => Function

    ejs.render(str, options);
    // => str