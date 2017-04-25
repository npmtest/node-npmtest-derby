# npmtest-derby

#### basic test coverage for  [derby (v0.9.7)](http://derbyjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-derby.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-derby) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-derby.svg)](https://travis-ci.org/npmtest/node-npmtest-derby)

#### MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.

[![NPM](https://nodei.co/npm/derby.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/derby)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-derby/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-derby/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-derby/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-derby/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-derby/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-derby/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-derby/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-derby/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-derby/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-derby/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-derby/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-derby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-derby/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-derby/build/test-report.html](https://npmtest.github.io/node-npmtest-derby/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-derby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-derby/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-derby/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-derby/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-derby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-derby/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-derby/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-derby/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nate Smith"
    },
    "bugs": {
        "url": "https://github.com/derbyjs/derby/issues"
    },
    "dependencies": {
        "chokidar": "^1.2.0",
        "derby-parsing": "^0.5.0",
        "derby-templates": "^0.4.0",
        "html-util": "^0.2.1",
        "racer": "^0.9.0",
        "resolve": "^1.1.6",
        "through": "^2.3.4",
        "tracks": "^0.5.0"
    },
    "description": "MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.",
    "devDependencies": {
        "browserify": "^11.2.0",
        "expect.js": "^0.3.1",
        "express": "^4.13.3",
        "jshint": "^2.8.0",
        "mocha": "^2.3.3"
    },
    "directories": {
        "doc": "docs",
        "test": "test"
    },
    "dist": {
        "shasum": "bda76b5c2fc70f8a2cb4876e63103e14f745dfd0",
        "tarball": "https://registry.npmjs.org/derby/-/derby-0.9.7.tgz"
    },
    "gitHead": "242f969ca74c76b89ec4fa9b79e7c554490d999f",
    "homepage": "http://derbyjs.com/",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "nateps"
        },
        {
            "name": "josephg"
        },
        {
            "name": "ishbu"
        },
        {
            "name": "enjalot"
        }
    ],
    "name": "derby",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/derbyjs/derby.git"
    },
    "scripts": {
        "test": "mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js"
    },
    "version": "0.9.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
