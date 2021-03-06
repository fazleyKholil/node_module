html_sanitize
=========

A small library providing utility methods to `escape` and `unescape` HTML entities

## Installation

  npm install html_sanitize --save

## Usage

```javascript
  var html_sanitize = require('html_sanitize')
      escape = html_sanitize.escape,
      unescape = html_sanitize.unescape;

  var html = '<h1>Hello World</h1>',
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);
```

## Tests

  npm test

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 1.1.5 Initial release
