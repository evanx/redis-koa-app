
# redis-koa-app-rpf

Redis Koa2 application archetype.

Named in honour of https://en.wikipedia.org/wiki/Richard_Feynman 

## Usage

The `lib/index.js` entry-point uses the `redis-koa-app-rpf` application archetype.
```
require('redis-koa-app-rpf')(require('./spec'), require('./main'));
```
where we extract the `config` from `process.env` according to the `spec` and invoke our `main` function.

## Related projects

The following projects reuse this application archetype:

https://github.com/evanx/geo-cache

<hr>

https://twitter.com/@evanxsummers

