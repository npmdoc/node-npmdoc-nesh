# npmdoc-nesh

#### api documentation for  [nesh (v1.7.0)](http://danielgtaylor.github.io/nesh/)  [![npm package](https://img.shields.io/npm/v/npmdoc-nesh.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nesh) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nesh.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nesh)

#### An enhanced, extensible shell for Node.js

[![NPM](https://nodei.co/npm/nesh.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nesh)

- [https://npmdoc.github.io/node-npmdoc-nesh/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nesh/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nesh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nesh/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nesh/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nesh/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel G. Taylor",
        "url": "http://programmer-art.org/"
    },
    "bin": {
        "nesh": "./bin/nesh.js"
    },
    "bugs": {
        "url": "https://github.com/danielgtaylor/nesh/issues"
    },
    "dependencies": {
        "babel-core": "^5.4.7",
        "colors": "^1.1.0",
        "intdoc": "^1.2.0",
        "lodash-node": "^3.9.3",
        "optimist": ">=0.3.5 <1",
        "semver": "^4.3.6",
        "underscore": ">=1.4 <2"
    },
    "description": "An enhanced, extensible shell for Node.js",
    "devDependencies": {
        "coffee-script": ">=1.7 <2",
        "mocha": "^2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "ecf8a3d8cb89d25db2e633996c383d763975f9f0",
        "tarball": "https://registry.npmjs.org/nesh/-/nesh-1.7.0.tgz"
    },
    "engines": {
        "node": ">=0.8.19"
    },
    "gitHead": "6f7b53e03d8a2fb518d1763c2fe887352bdb1476",
    "homepage": "http://danielgtaylor.github.io/nesh/",
    "keywords": [
        "script",
        "interactive",
        "shell",
        "interpreter",
        "extend",
        "enhance",
        "enhanced",
        "embed",
        "embedding",
        "coffee",
        "plugin",
        "learn",
        "try"
    ],
    "license": "MIT",
    "main": "lib/nesh.js",
    "maintainers": [
        {
            "name": "danielgtaylor"
        }
    ],
    "name": "nesh",
    "optionalDependencies": {},
    "peerDependencies": {
        "coffee-script": ">=1.6.2 <2"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danielgtaylor/nesh.git"
    },
    "scripts": {
        "prepublish": "./node_modules/coffee-script/bin/cake build",
        "pretest": "./node_modules/coffee-script/bin/cake build",
        "test": "./node_modules/coffee-script/bin/cake test"
    },
    "version": "1.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
