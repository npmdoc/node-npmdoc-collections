# npmdoc-collections

#### api documentation for  [collections (v5.0.6)](http://www.collectionsjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-collections.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-collections) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-collections.svg)](https://travis-ci.org/npmdoc/node-npmdoc-collections)

#### data structures with idiomatic JavaScript collection interfaces

[![NPM](https://nodei.co/npm/collections.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/collections)

- [https://npmdoc.github.io/node-npmdoc-collections/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-collections/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-collections/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-collections/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-collections/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-collections/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "collections",
    "version": "5.0.6",
    "description": "data structures with idiomatic JavaScript collection interfaces",
    "homepage": "http://www.collectionsjs.com",
    "author": "Kris Kowal <kris@cixar.com> (http://github.com/kriskowal)",
    "contributors": [
        {
            "name": "Benoit Marchant"
        }
    ],
    "keywords": [
        "collections",
        "data structures",
        "observable",
        "list",
        "set",
        "map",
        "splay"
    ],
    "bugs": {
        "mail": "kris@cixar.com",
        "url": "http://github.com/montagejs/collections/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/montagejs/collections/master/LICENSE.md"
        }
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/montagejs/collections.git"
    },
    "dependencies": {
        "weak-map": "~1.0.x"
    },
    "devDependencies": {
        "jasmine-node": "montagestudio/jasmine-node#master",
        "istanbul": "*",
        "opener": "*"
    },
    "scripts": {
        "test": "jasmine-node spec",
        "cover": "istanbul cover node_modules/jasmine-node/bin/jasmine-node spec && istanbul report html && opener coverage/index.html"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
