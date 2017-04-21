# npmdoc-penthouse

#### api documentation for  [penthouse (v0.10.9)](https://github.com/pocketjoso/penthouse)  [![npm package](https://img.shields.io/npm/v/npmdoc-penthouse.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-penthouse) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-penthouse.svg)](https://travis-ci.org/npmdoc/node-npmdoc-penthouse)

#### Generate critical path CSS for web pages

[![NPM](https://nodei.co/npm/penthouse.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/penthouse)

- [https://npmdoc.github.io/node-npmdoc-penthouse/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-penthouse/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-penthouse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-penthouse/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-penthouse/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-penthouse/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "penthouse",
    "description": "Generate critical path CSS for web pages",
    "version": "0.10.9",
    "homepage": "https://github.com/pocketjoso/penthouse",
    "author": {
        "name": "Jonas Ohlsson",
        "url": "https://jonassebastianohlsson.com"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/pocketjoso/penthouse.git#master"
    },
    "bugs": {
        "url": "https://github.com/pocketjoso/penthouse/issues"
    },
    "license": "MIT",
    "main": "./lib/index.js",
    "engines": {
        "node": ">=0.12.0"
    },
    "scripts": {
        "lint": "jshint .",
        "test": "npm run lint && mocha --compilers js:babel-core/register test/core-tests.js",
        "test-all": "npm run lint && mocha --compilers js:babel-core/register"
    },
    "dependencies": {
        "apartment": "^1.1.1",
        "css": "https://github.com/pocketjoso/css.git",
        "css-mediaquery": "^0.1.2",
        "jsesc": "^1.0.0",
        "os-tmpdir": "^1.0.1",
        "phantomjs-prebuilt": "^2.1.3",
        "tmp": "0.0.31"
    },
    "devDependencies": {
        "babel-core": "^6.8.0",
        "babel-preset-es2015": "^6.6.0",
        "chai": "^1.9.1",
        "css-compare-screenshots": "0.0.7",
        "global-mocha": "^1.0.1",
        "gm": "^1.21.1",
        "jshint": "^2.9.3",
        "mocha": "^1.20.1",
        "rimraf": "^2.4.3"
    },
    "keywords": [
        "CSS Critical Path Generator",
        "phantomjs",
        "css",
        "performance",
        "build",
        "tool"
    ],
    "files": [
        "lib/**/*.js",
        "lib/phantomjs/config.json"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
