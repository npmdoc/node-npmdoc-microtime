# npmdoc-microtime

#### api documentation for  [microtime (v2.1.3)](https://github.com/wadey/node-microtime)  [![npm package](https://img.shields.io/npm/v/npmdoc-microtime.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-microtime) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-microtime.svg)](https://travis-ci.org/npmdoc/node-npmdoc-microtime)

#### Get the current time in microseconds

[![NPM](https://nodei.co/npm/microtime.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/microtime)

- [https://npmdoc.github.io/node-npmdoc-microtime/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-microtime/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-microtime/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-microtime/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-microtime/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-microtime/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Wade Simmons",
        "url": "http://wades.im/mons"
    },
    "bugs": {
        "url": "https://github.com/wadey/node-microtime/issues"
    },
    "dependencies": {
        "bindings": "1.2.x",
        "nan": "2.6.x"
    },
    "description": "Get the current time in microseconds",
    "devDependencies": {
        "clang-format": "^1.0.38",
        "standard": "^10.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0d1307f25da0ca7fde4ab791edc8c91dd7b4e3be",
        "tarball": "https://registry.npmjs.org/microtime/-/microtime-2.1.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "d6d59786f65e1e00222dd85c4f49386852da93da",
    "gypfile": true,
    "homepage": "https://github.com/wadey/node-microtime",
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "wadey"
        }
    ],
    "name": "microtime",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/wadey/node-microtime.git"
    },
    "scripts": {
        "format": "clang-format -i src/microtime.cc",
        "install": "node-gyp rebuild",
        "lint": "standard && clang-format -output-replacements-xml src/microtime.cc | (! grep -q '<replacement ')",
        "test": "node test.js"
    },
    "version": "2.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
