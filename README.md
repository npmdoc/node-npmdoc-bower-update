# api documentation for  [bower-update (v0.2.0)](https://github.com/sapegin/bower-update)  [![npm package](https://img.shields.io/npm/v/npmdoc-bower-update.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bower-update) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bower-update.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bower-update)
#### Updates Bower components to the really latest versions.

[![NPM](https://nodei.co/npm/bower-update.png?downloads=true)](https://www.npmjs.com/package/bower-update)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bower-update/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-bower-update_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bower-update/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bower-update/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bower-update/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Artem Sapegin",
        "url": "http://sapegin.me/"
    },
    "bin": {
        "bower-update": "bin/bower-update"
    },
    "bugs": {
        "url": "https://github.com/sapegin/bower-update/issues"
    },
    "dependencies": {
        "async": "~0.9.0",
        "bower": "~1.4.0",
        "chalk": "~1.0.0",
        "lodash": "~3.6.0",
        "nomnom": "~1.8.1",
        "readline-sync": "~0.8.0"
    },
    "deprecated": "Please use npm-check-updates",
    "description": "Updates Bower components to the really latest versions.",
    "devDependencies": {
        "chai": "~2.2.0",
        "coffee-script": "~1.9.1",
        "jscs": "~1.12.0",
        "jshint": "~2.6.3",
        "mocha": "~2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "410ded81975a5297d33315bd8dbec0aeb8a585b8",
        "tarball": "https://registry.npmjs.org/bower-update/-/bower-update-0.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "1452536680c15f0d9ba453c11329b3ca0bd8e234",
    "homepage": "https://github.com/sapegin/bower-update",
    "keywords": [
        "bower"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/sapegin/bower-update/blob/master/License.md"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "sapegin",
            "email": "artem@sapegin.ru"
        }
    ],
    "name": "bower-update",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/sapegin/bower-update.git"
    },
    "scripts": {
        "jscs": "jscs index.js",
        "jshint": "jshint index.js",
        "mocha": "mocha --timeout 30000 --reporter spec --compilers coffee:coffee-script/register",
        "prepare": "cd test && rm -f bower.json && cp src/bower.json . && bower install",
        "test": "npm run jshint && npm run jscs && npm run prepare && npm run mocha"
    },
    "version": "0.2.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module bower-update](#apidoc.module.bower-update)



# <a name="apidoc.module.bower-update"></a>[module bower-update](#apidoc.module.bower-update)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
