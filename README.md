# api documentation for  [readdirp (v2.1.0)](https://github.com/thlorenz/readdirp)  [![npm package](https://img.shields.io/npm/v/npmdoc-readdirp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-readdirp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-readdirp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-readdirp)
#### Recursive version of fs.readdir with streaming api.

[![NPM](https://nodei.co/npm/readdirp.png?downloads=true)](https://www.npmjs.com/package/readdirp)

[![apidoc](https://npmdoc.github.io/node-npmdoc-readdirp/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-readdirp%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-readdirp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-readdirp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-readdirp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thorsten Lorenz",
        "email": "thlorenz@gmx.de",
        "url": "thlorenz.com"
    },
    "bugs": {
        "url": "https://github.com/thlorenz/readdirp/issues"
    },
    "dependencies": {
        "graceful-fs": "^4.1.2",
        "minimatch": "^3.0.2",
        "readable-stream": "^2.0.2",
        "set-immediate-shim": "^1.0.1"
    },
    "description": "Recursive version of fs.readdir with streaming api.",
    "devDependencies": {
        "nave": "^0.5.1",
        "proxyquire": "^1.7.9",
        "tap": "1.3.2",
        "through2": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4ed0ad060df3073300c48440373f72d1cc642d78",
        "tarball": "https://registry.npmjs.org/readdirp/-/readdirp-2.1.0.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "5a3751f86a1c2bbbb8e3a42685d4191992631e6c",
    "homepage": "https://github.com/thlorenz/readdirp",
    "keywords": [
        "recursive",
        "fs",
        "stream",
        "streams",
        "readdir",
        "filesystem",
        "find",
        "filter"
    ],
    "license": "MIT",
    "main": "readdirp.js",
    "maintainers": [
        {
            "name": "thlorenz",
            "email": "thlorenz@gmx.de"
        }
    ],
    "name": "readdirp",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/readdirp.git"
    },
    "scripts": {
        "test": "if [ -e $TRAVIS ]; then npm run test-all; else npm run test-main; fi",
        "test-0.10": "nave use 0.10 npm run test-main",
        "test-0.12": "nave use 0.12 npm run test-main",
        "test-4": "nave use 4.4 npm run test-main",
        "test-6": "nave use 6.2 npm run test-main",
        "test-all": "npm run test-main && npm run test-0.10 && npm run test-0.12 && npm run test-4 && npm run test-6",
        "test-main": "(cd test && set -e; for t in ./*.js; do node $t; done)"
    },
    "version": "2.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module readdirp](#apidoc.module.readdirp)



# <a name="apidoc.module.readdirp"></a>[module readdirp](#apidoc.module.readdirp)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
