# node-jose-dpikalov #

[![npm license](https://flat.badgen.net/npm/license/node-jose-dpikalov)](https://npmjs.com/package/node-jose-dpikalov)
[![npm downloads](https://flat.badgen.net/npm/dm/node-jose-dpikalov)](https://npmjs.com/package/node-jose-dpikalov)


This is fork from https://github.com/cisco/node-jose

Normally, **JWE Additional Authenticated Data** includes **Encoded Protected Header** (see step 14 of https://datatracker.ietf.org/doc/html/rfc7516#section-5.1)
but this lib allows to change this behavior.

Added extra option ```excludeHeaderFromAad``` to methods ```JWE.createEncrypt(options,...)``` and ```JWE.createDecrypt(key, options)```

Usage: ```JWE.createEncrypt({ excludeHeaderFromAad: true },...)```
