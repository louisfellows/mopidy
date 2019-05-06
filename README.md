Mopidy ES6 + WS
======

Forked to add WS as a dependancy, allowing it to be used on a node server. All credit for 99.99999% of the work on this project should go to the original author.

The library was made as I had some conflicts with the dependencies of mopidy.js, which this library is heavily based off of.

## Installation

`npm install mopidy-es6`

## Using the library

```js
import Mopidy from 'mopidy-es6';

var mopidy = new Mopidy('ws://localhost:6680/mopidy/ws/');
```
