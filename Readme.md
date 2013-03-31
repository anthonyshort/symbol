
# symbol

  Polyfill for ES6 symbols for ES5 browsers. Originally written by [Andrea Giammarchi](http://webreflection.blogspot.com.au/2013/03/simulating-es6-symbols-in-es5.html). I just made it into a Component so I can use it easily.

## Installation

    $ component install anthonyshort/symbol

## API

    var Symbol = require('symbol');
    var data = {};
    var hidden = new Symbol();
    data[hidden] = "Secret files";
    console.log(data); // {}
    console.log(data[hidden]); // "Secret files";

## License

  MIT
