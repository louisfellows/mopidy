Mopidy ES6 + WS
======

Mopidy library targeting ES2015 with no dependencies. Forked to add WS, allowing it to be used on a node server.

The library was made as I had some conflicts with the dependencies of mopidy.js, which this library is heavily based off of.

## Installation

`npm install mopidy-es6`

## Using the library

```js
import Mopidy from 'mopidy-es6';

var mopidy = new Mopidy('ws://localhost:6680/mopidy/ws/');
```
