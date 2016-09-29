
# Transfer Chinese language json file between simple and traditional.


## Install

```sh
$ npm install --save simple-traditional-chinese
```


## Usage

```js
// load the simple to traditional module
var traditionlize = require("./traditionlize");

// load the traditional to simple module
var simplify = require("./simplify");

// transfer simple to traditional language json file
// and then there will be a file named tra_simple-language.json file
traditionlize("simple-language.json");

// transfer simple to traditional language json file
// and then there will be a file named sim_traditional-language.json file
simplify("traditional-language.json");
```


## Author

[justforuse](http://justforuse.github.io/)