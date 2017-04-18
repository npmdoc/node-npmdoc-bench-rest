# npmdoc-bench-rest

#### api documentation for  [bench-rest (v1.2.4)](https://github.com/jeffbski/bench-rest#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-bench-rest.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bench-rest) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bench-rest.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bench-rest)

#### bench-rest - benchmark REST (HTTP/HTTPS) API's. Node.js client module for easy load testing / benchmarking REST API' using a simple structure/DSL can create REST flows with setup and teardown and returns (measured) metrics.

[![NPM](https://nodei.co/npm/bench-rest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bench-rest)

- [https://npmdoc.github.io/node-npmdoc-bench-rest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bench-rest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bench-rest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bench-rest/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bench-rest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bench-rest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeff Barczewski"
    },
    "bin": {
        "bench-rest": "bin/bench-rest"
    },
    "bugs": {
        "url": "http://github.com/jeffbski/bench-rest/issues"
    },
    "dependencies": {
        "async": "^2.0.1",
        "commander": "^2.9.0",
        "measured": "^1.0.2",
        "progress2": "~0.1.1",
        "request": "^2.75.0"
    },
    "description": "bench-rest - benchmark REST (HTTP/HTTPS) API's. Node.js client module for easy load testing / benchmarking REST API' using a simple structure/DSL can create REST flows with setup and teardown and returns (measured) metrics.",
    "devDependencies": {
        "accum": "^0.3.6",
        "chai": "^3.4.0",
        "chai-stack": "~1.3.1",
        "hapi": "^15.1.1",
        "mocha": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3bd19375e101a734e3bb3e91bbfc9f8a6d1b9fc4",
        "tarball": "https://registry.npmjs.org/bench-rest/-/bench-rest-1.2.4.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "895db60ca8ec1a229cc0f32c555e6e3b0b3f887b",
    "homepage": "https://github.com/jeffbski/bench-rest#readme",
    "keywords": [
        "benchmarking",
        "benchmark",
        "bench",
        "REST",
        "http",
        "https",
        "metrics",
        "measured",
        "async",
        "request",
        "load testing",
        "client",
        "DSL"
    ],
    "license": "MIT",
    "main": "lib/bench-rest",
    "maintainers": [
        {
            "name": "jeffbski"
        }
    ],
    "name": "bench-rest",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/jeffbski/bench-rest.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha ./test/*.mocha.js"
    },
    "version": "1.2.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
