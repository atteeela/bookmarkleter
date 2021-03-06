# Bookmarkleter

[![Build Status][build-status]][travis-ci]
[![NPM version][npm-badge]][fury-io]

You have JavaScript. You need a [bookmarklet][bookmarklet]. This does that.

### Browser tool

Create bookmarklets in your browser with a simple copy and paste.

**http://chriszarate.github.io/bookmarkleter**

### NPM module

```
npm install bookmarkleter
```

```js
var bookmarkleter = require('./bookmarkleter');
var bookmarklet = bookmarkleter(code, options);
```

### Options

All options are Boolean flags.

`urlencode`: URL-encode reserved characters: \[space\], %, ", <, >, #, @, &, ?

`anonymize`: Wrap in an [IIFE][iife] (anonymizing function).

`mangleVars`: Minify using [UglifyJS][uglify].

`jQuery`: Make sure a modern version (>= 1.7) of [jQuery][jquery] is available
for your code.

### License

This is free software. It is released to the public domain without warranty.

### Thanks

Thanks to [@jpillora][jpillora] for updates and contributions.


[build-status]: https://secure.travis-ci.org/chriszarate/bookmarkleter.svg?branch=master
[travis-ci]: http://travis-ci.org/chriszarate/bookmarkleter
[npm-badge]: https://badge.fury.io/js/bookmarkleter.svg
[fury-io]: http://badge.fury.io/js/bookmarkleter
[bookmarklet]: http://en.wikipedia.org/wiki/Bookmarklet
[iife]: http://en.wikipedia.org/wiki/Immediately-invoked_function_expression
[uglify]: https://github.com/mishoo/UglifyJS
[jquery]: http://jquery.com
[jpillora]: https://github.com/jpillora
