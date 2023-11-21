# calculate-fast

> Returns number from calculation.


## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install calculate-fast
```

## Important

Currently supports only two numbers, which need to be positive, first being number smaller than 1000, and second being smaller than 200, and 4 equations, +  -  /  *

## Usage

You need to pass two numbers, and operator to function "CalculateFast()", if given something wrong, it will return 'false'

```js
const even = require('calculate-fast')

console.log(CalculateFast(1, 11, "+")) //=> "12"
console.log(CalculateFast(203, 198, "-")) //=> "5"
console.log(CalculateFast(6, 20, "*")) //=> "120"
console.log(CalculateFast(200, 2, "/")) //=> "100"
console.log(CalculateFast(999, 0, "/")) //=> false
```

### Author

**lasgra**

* [GitHub Profile](https://github.com/lasgra)
***