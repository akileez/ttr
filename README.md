# ttr
[![NPM version][npm-image]][npm-url]
[![schoolmarm-standard-style][marm-image]][marm-url]
[![experimental][stability-image]][stability-url]
[![Downloads][downloads-image]][downloads-url]

> tiny test reporter

This is a work in progress. 

## Installation
```bash
$ npm install ttr
```

## Usage
```js
var test = require('ttr')

test('this is a test', function (t) {
  t.eq(2, 1 + 1)
  t.pass('this will always pass')
})

test('this is only a test', function (t) {
  t.fail('this will never pass')
})

test.result()
```


## API
```js

```

## Why?


## See Also
-

## License
[ISC](https://github.com/akileez/ttr/blob/master/LICENSE)

[npm-image]: https://img.shields.io/npm/v/ttr.svg?style=flat-square
[npm-url]: https://npmjs.org/package/ttr
[marm-image]: https://img.shields.io/badge/code%20style-marm-brightgreen.svg?style=flat-square
[marm-url]: https://github.com/akileez/eslint-config-marm
[stability-image]: https://img.shields.io/badge/stability-experimental-darkorange.svg?style=flat-square
[stability-url]: https://github.com/akileez/ttr
[downloads-image]: http://img.shields.io/npm/dm/ttr.svg?style=flat-square
[downloads-url]: https://npmjs.org/package/ttr
