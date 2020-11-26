# FORKED from [mpfdavis/outputcache](https://github.com/mpfdavis/outputcache)

## With added supports for CORS

The only difference from outputcache is that ismga-outputcache uses the origin header from request in the cache key, if available.

-----

[![Version](https://img.shields.io/npm/v/ismga-outputcache.svg)](https://www.npmjs.com/package/outputcache)


## Installation
```
npm install ismga-outputcache --save
```


## Initialize

```javascript
const OutputCache = require('ismga-outputcache');
const xoc = new OutputCache({options}); //see api below
```