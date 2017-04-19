# npmtest-crypto-browserify

#### test coverage for  [crypto-browserify (v3.11.0)](https://github.com/crypto-browserify/crypto-browserify)  [![npm package](https://img.shields.io/npm/v/npmtest-crypto-browserify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-crypto-browserify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-crypto-browserify.svg)](https://travis-ci.org/npmtest/node-npmtest-crypto-browserify)

#### implementation of crypto for the browser

[![NPM](https://nodei.co/npm/crypto-browserify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/crypto-browserify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-crypto-browserify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-crypto-browserify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-crypto-browserify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-crypto-browserify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-crypto-browserify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-crypto-browserify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-crypto-browserify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-crypto-browserify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-crypto-browserify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-crypto-browserify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-crypto-browserify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-crypto-browserify/build/test-report.html](https://npmtest.github.io/node-npmtest-crypto-browserify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-crypto-browserify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-crypto-browserify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-crypto-browserify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-crypto-browserify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-crypto-browserify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-crypto-browserify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-crypto-browserify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-crypto-browserify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "dominictarr.com"
    },
    "browser": {
        "crypto": false
    },
    "bugs": {
        "url": "https://github.com/crypto-browserify/crypto-browserify/issues"
    },
    "dependencies": {
        "browserify-cipher": "^1.0.0",
        "browserify-sign": "^4.0.0",
        "create-ecdh": "^4.0.0",
        "create-hash": "^1.1.0",
        "create-hmac": "^1.1.0",
        "diffie-hellman": "^5.0.0",
        "inherits": "^2.0.1",
        "pbkdf2": "^3.0.3",
        "public-encrypt": "^4.0.0",
        "randombytes": "^2.0.0"
    },
    "description": "implementation of crypto for the browser",
    "devDependencies": {
        "hash-test-vectors": "~1.3.2",
        "pseudorandombytes": "^2.0.0",
        "standard": "^5.0.2",
        "tape": "~2.3.2",
        "zuul": "^3.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3652a0906ab9b2a7e0c3ce66a408e957a2485522",
        "tarball": "https://registry.npmjs.org/crypto-browserify/-/crypto-browserify-3.11.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "9fabcbd78209a99c7c624d1509d389b00e8d733f",
    "homepage": "https://github.com/crypto-browserify/crypto-browserify",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dominictarr"
        },
        {
            "name": "cwmma"
        },
        {
            "name": "dcousens"
        },
        {
            "name": "jprichardson"
        },
        {
            "name": "indutny"
        }
    ],
    "name": "crypto-browserify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/crypto-browserify/crypto-browserify.git"
    },
    "scripts": {
        "browser": "zuul --browser-version $BROWSER_VERSION --browser-name $BROWSER_NAME -- test/index.js",
        "standard": "standard",
        "test": "npm run standard && npm run unit",
        "unit": "node test/"
    },
    "version": "3.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
