dhash (difference hash)
=========

[![NPM version][npm-image]][npm-url]
[![Build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![Dependency Status][david-image]][david-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

dHash - image hash implementation for node

### Install

```
npm install dhash-image
```

### Usage

```

var dhash = require('dhash-image');

dhash('/path/to/image', function(err, hash){
	// Do something with hash hex-string...
});

// Optional last argument for hash size in bytes (Default: 8)

```

[gitter-image]: https://badges.gitter.im/mgmtio/dhash-image.png
[gitter-url]: https://gitter.im/mgmtio/dhash-image
[npm-image]: https://img.shields.io/npm/v/dhash-image.svg?style=flat-square
[npm-url]: https://npmjs.org/package/dhash-image
[github-tag]: http://img.shields.io/github/tag/mgmtio/dhash-image.svg?style=flat-square
[github-url]: https://github.com/mgmtio/dhash-image/tags
[travis-image]: https://img.shields.io/travis/mgmtio/dhash-image.svg?style=flat-square
[travis-url]: https://travis-ci.org/mgmtio/dhash-image
[coveralls-image]: https://img.shields.io/coveralls/mgmtio/dhash-image.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/mgmtio/dhash-image
[david-image]: http://img.shields.io/david/mgmtio/dhash-image.svg?style=flat-square
[david-url]: https://david-dm.org/mgmtio/dhash-image
[license-image]: http://img.shields.io/npm/l/dhash-image.svg?style=flat-square
[license-url]: LICENSE
[downloads-image]: http://img.shields.io/npm/dm/dhash-image.svg?style=flat-square
[downloads-url]: https://npmjs.org/package/dhash-image
