# npmdoc-bower-update

#### api documentation for  [bower-update (v0.2.0)](https://github.com/sapegin/bower-update)  [![npm package](https://img.shields.io/npm/v/npmdoc-bower-update.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bower-update) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bower-update.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bower-update)

#### Updates Bower components to the really latest versions.

[![NPM](https://nodei.co/npm/bower-update.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bower-update)

- [https://npmdoc.github.io/node-npmdoc-bower-update/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bower-update/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bower-update/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bower-update/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bower-update/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bower-update/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bower-update",
    "description": "Updates Bower components to the really latest versions.",
    "version": "0.2.0",
    "homepage": "https://github.com/sapegin/bower-update",
    "author": {
        "name": "Artem Sapegin",
        "url": "http://sapegin.me/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/sapegin/bower-update.git"
    },
    "bugs": {
        "url": "https://github.com/sapegin/bower-update/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/sapegin/bower-update/blob/master/License.md"
        }
    ],
    "main": "index.js",
    "bin": {
        "bower-update": "bin/bower-update"
    },
    "preferGlobal": true,
    "scripts": {
        "jshint": "jshint index.js",
        "jscs": "jscs index.js",
        "prepare": "cd test && rm -f bower.json && cp src/bower.json . && bower install",
        "mocha": "mocha --timeout 30000 --reporter spec --compilers coffee:coffee-script/register",
        "test": "npm run jshint && npm run jscs && npm run prepare && npm run mocha"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "dependencies": {
        "async": "~0.9.0",
        "bower": "~1.4.0",
        "chalk": "~1.0.0",
        "lodash": "~3.6.0",
        "nomnom": "~1.8.1",
        "readline-sync": "~0.8.0"
    },
    "devDependencies": {
        "mocha": "~2.2.1",
        "coffee-script": "~1.9.1",
        "chai": "~2.2.0",
        "jshint": "~2.6.3",
        "jscs": "~1.12.0"
    },
    "keywords": [
        "bower"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
