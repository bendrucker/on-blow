# on-blow [![Build Status](https://travis-ci.org/bendrucker/on-blow.svg?branch=master)](https://travis-ci.org/bendrucker/on-blow) [![Greenkeeper badge](https://badges.greenkeeper.io/bendrucker/on-blow.svg)](https://greenkeeper.io/)

> EventEmitter triggered by the user blowing into their mic


## Install

```
$ npm install --save on-blow
```


## Usage

```js
var blow = require('on-blow')

blow.run()
blow.events
  .on('start', () => console.log('user blew'))
```

## See Also

* [Breathing-Detection-in-Javascript](https://github.com/Breathinglabs/JS-Breathing-Detection): Code was adapted lightly to provide a usable event interface.


## License

MIT © [Ben Drucker](http://bendrucker.me)
