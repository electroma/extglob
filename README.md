# extglob [![NPM version](https://badge.fury.io/js/extglob.svg)](http://badge.fury.io/js/extglob)

> Extended globs. extglobs add the expressive power of regular expressions to glob patterns.

## Install with [npm](npmjs.org)

```bash
npm i extglob --save
```

Used by [micromatch].

## Usage

```js
var extglob = require('extglob');
```

## Features

- `?(pattern)`: Match zero or one occurrence of the given pattern.
- `*(pattern)`: Match zero or more occurrences of the given pattern.
- `+(pattern)`: Match one or more occurrences of the given pattern.
- `@(pattern)`: Match one of the given pattern.
- `!(pattern)`: Match anything except one of the given pattern.


## Run tests

Install dev dependencies:

```bash
npm i -d && npm test
```

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/extglob/issues)

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on February 05, 2015._

[micromatch]: https://github.com/jonschlinkert/micromatch
