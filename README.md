# gimme-lyrics
A small library allow a user to get the lyrics to just about any song from http://www.lyrics.com

## Notice 
I wrote this module in order to learn more about making a node module, publishing to npm, and about web scraping, along with other things you can do with Node.js. This module is slower than other modules, and if speed is your priority, use https://www.npmjs.com/package/lyrics-fetcher. As for accuracy and more content, it is unclear which site is better.

## Installation

> npm install gimme-lyrics --save

## Usage
```javascript
var lyrics = require('gimme-lyrics');

lyrics.getLyrics('Drake', 'Hotline Bling', function(err, lyrics) {
  console.log(err || lyrics);
});
```

## Tests

> npm test

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality.

## Release History

* 0.1.0 Initial release
