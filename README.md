# twitter-splitter

[![Build Status](https://travis-ci.org/pnevares/twitter-splitter.svg?branch=master)](https://travis-ci.org/pnevares/twitter-splitter)

Split your text into Twitter-friendly pieces

Usage:
```js
const twitterSplitter = require("twitter-splitter");

const text = twitterSplitter("This is a short tweet with a very short character limit", 25, "...");

console.log(text);

/*
[ 'This is a short tweet...',
  '...with a very short...',
  '...character limit' ]
*/
```
