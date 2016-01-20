imdb
====
![npm](https://img.shields.io/npm/v/imdb.svg)
![downloads](https://img.shields.io/npm/dt/imdb.svg)

> "They told me I couldn't do it. So that's why I did it." - Anonymous

An IMDB API for getting information on your favourite movies!

## Installing
Install via [npm](https://npmjs.com)

    $ npm install imdb

## Running / Building
To run the example:

    $ npm install
    $ node example/movie.js
    
## API / Usage

Provide the IMDB ID and go! Also see the examples folder for inspiration!

```javascript
var imdb = require('imdb');

imdb('tt3659388', function(err, data) {
    if(err)
        throw err;

    console.log(data);
});
```