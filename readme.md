# array-uniq [![Build Status](https://travis-ci.org/sindresorhus/array-uniq.svg?branch=master)](https://travis-ci.org/sindresorhus/array-uniq)

> Returns a new array without duplicates

It's already pretty fast, but will be much faster when [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) becomes available in V8 (especially with large arrays).


## Install

```sh
$ npm install --save array-uniq
```


## Usage

```js
var arrayUniq = require('array-uniq');

arrayUniq([1, 1, 2, 3, 3]);
//=> [1, 2, 3]

arrayUniq(['foo', 'foo', 'bar', 'foo']);
//=> ['foo', 'bar']
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
