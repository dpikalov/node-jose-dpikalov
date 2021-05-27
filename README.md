# node-jose-dpikalov #

This is fork from https://github.com/cisco/node-jose

Normally, **JWE Additional Authenticated Data** includes **Encoded Protected Header** (see step 14 of https://datatracker.ietf.org/doc/html/rfc7516#section-5.1)
but this lib allows to change this behavior.

Added extra option ```excludeHeaderFromAad``` to methods ```JWE.createEncrypt(options,...)``` and ```JWE.createDecrypt(key, options)```
