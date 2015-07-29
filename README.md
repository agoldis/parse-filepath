# parse-filepath [![NPM version](https://badge.fury.io/js/parse-filepath.svg)](http://badge.fury.io/js/parse-filepath)

> Parse a filepath into an object. Falls back on the native node.js `path.parse` method if it exists.

## Install with [npm](npmjs.org)

```bash
npm i parse-filepath --save
```

## Usage

```js
var parsePath = require('parse-filepath');
parsePath('foo/bar/baz/index.html');
```

Returns:

```js
{ path: 'foo/bar/baz/index.html',
  isAbsolute: false,
  absolute: '/Users/jonschlinkert/dev/parse-filepath/foo/bar/baz/index.html',
  root: '',
  dirname: 'foo/bar/baz',
  basename: 'index.html',
  extname: '.html',
  name: 'index' }
```

## Related projects
* [is-absolute](https://github.com/jonschlinkert/is-absolute): Return true if a file path is absolute.
* [is-relative](https://github.com/jonschlinkert/is-relative): Returns `true` if the path appears to be relative.
* [cwd](https://github.com/jonschlinkert/cwd): Easily get the CWD (current working directory) of a project based on package.json, optionally starting from a given path. (Node.js/javascript util)
* [global-prefix](https://github.com/jonschlinkert/global-prefix): Get the npm global path prefix.
* [relative](https://github.com/jonschlinkert/relative#readme): Get the relative filepath from path A to path B. Calculates from file-to-directory, file-to-file, directory-to-file, and directory-to-directory.

## Running tests
Install dev dependencies.

```bash
npm i -d && npm test
```


## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/parse-filepath/issues)


## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright © 2014-2015 [Jon Schlinkert](https://github.com/jonschlinkert)
Released under the [MIT](https://github.com/https://github.com/jonschlinkert/parse-filepath/blob/master/LICENSE) license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on July 29, 2015._
