[Minhashing](https://en.wikipedia.org/wiki/MinHash) is an efficient similarity estimation technique that is often used to identify near-duplicate documents in large text collections. This package offers a JavaScript implementation of the minhash algorithm and an efficient [Locality Sensitive Hashing Index](https://en.wikipedia.org/wiki/Locality-sensitive_hashing) for finding similar minhashes in Node.js or web applications.

## Installation

To get started with Minhash.js, you can install the package with npm:

```bash
npm install minhash --save
```

### Example

The [sample application](https://dragongr.github.io/minhash/) uses minhash.js to compute the similarity between samle files:

![app preview](https://raw.githubusercontent.com/dragonGR/minhash/master/images/preview.png)

There is also a sample Node.js script that can be run with `node examples/index.js`.
To compile and minify minhash.min.js — `npm run build`.
