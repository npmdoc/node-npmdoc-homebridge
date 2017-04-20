# npmdoc-homebridge

#### api documentation for  homebridge (v0.4.19)  [![npm package](https://img.shields.io/npm/v/npmdoc-homebridge.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-homebridge) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-homebridge.svg)](https://travis-ci.org/npmdoc/node-npmdoc-homebridge)

#### HomeKit support for the impatient

[![NPM](https://nodei.co/npm/homebridge.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/homebridge)

- [https://npmdoc.github.io/node-npmdoc-homebridge/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-homebridge/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-homebridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-homebridge/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-homebridge/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-homebridge/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "homebridge",
    "description": "HomeKit support for the impatient",
    "version": "0.4.19",
    "scripts": {
        "dev": "DEBUG=* ./bin/homebridge -D -P example-plugins/ || true"
    },
    "author": {
        "name": "Nick Farina"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/nfarina/homebridge.git"
    },
    "bugs": {
        "url": "http://github.com/nfarina/homebridge/issues"
    },
    "license": "ISC",
    "bin": {
        "homebridge": "bin/homebridge"
    },
    "engines": {
        "node": ">=4.3.2"
    },
    "preferGlobal": true,
    "dependencies": {
        "chalk": "^1.1.1",
        "commander": "2.8.1",
        "hap-nodejs": "0.4.24",
        "semver": "5.0.3",
        "node-persist": "^0.0.8"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
