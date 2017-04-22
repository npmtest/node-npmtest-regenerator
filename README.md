# npmtest-regenerator

#### basic test coverage for  [regenerator (v0.9.7)](http://github.com/facebook/regenerator)  [![npm package](https://img.shields.io/npm/v/npmtest-regenerator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-regenerator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-regenerator.svg)](https://travis-ci.org/npmtest/node-npmtest-regenerator)

#### Source transformer enabling ECMAScript 6 generator functions (yield) in JavaScript-of-today (ES5)

[![NPM](https://nodei.co/npm/regenerator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/regenerator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-regenerator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-regenerator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-regenerator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-regenerator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-regenerator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-regenerator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-regenerator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-regenerator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-regenerator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-regenerator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-regenerator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-regenerator/build/test-report.html](https://npmtest.github.io/node-npmtest-regenerator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-regenerator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-regenerator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-regenerator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-regenerator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-regenerator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-regenerator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-regenerator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-regenerator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Newman"
    },
    "bin": {
        "regenerator": "bin/regenerator"
    },
    "bugs": {
        "url": "https://github.com/facebook/regenerator/issues"
    },
    "dependencies": {
        "babel-core": "^6.18.2",
        "commoner": "^0.10.8",
        "recast": "^0.11.17",
        "regenerator-preset": "^0.9.6",
        "regenerator-runtime": "^0.10.3",
        "through": "^2.3.8"
    },
    "description": "Source transformer enabling ECMAScript 6 generator functions (yield) in JavaScript-of-today (ES5)",
    "devDependencies": {
        "babylon": "^6.14.1",
        "mocha": "^2.3.4",
        "promise": "^7.0.4",
        "semver": "^5.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "e0ba58ebbde23b896eac75ae7b93be2483ccf86f",
        "tarball": "https://registry.npmjs.org/regenerator/-/regenerator-0.9.7.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "gitHead": "c7207b0f673f229f44e0d9174a65607c1b975131",
    "homepage": "http://github.com/facebook/regenerator",
    "keywords": [
        "generator",
        "yield",
        "coroutine",
        "rewriting",
        "transformation",
        "syntax",
        "codegen",
        "rewriting",
        "refactoring",
        "transpiler",
        "desugaring",
        "ES6"
    ],
    "license": "BSD",
    "main": "main.js",
    "maintainers": [
        {
            "name": "benjamn"
        }
    ],
    "name": "regenerator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/facebook/regenerator.git"
    },
    "scripts": {
        "pretest": "./link.sh",
        "test": "node test/run.js"
    },
    "version": "0.9.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
