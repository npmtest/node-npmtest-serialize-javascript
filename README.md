# npmtest-serialize-javascript

#### basic test coverage for  [serialize-javascript (v1.3.0)](https://github.com/yahoo/serialize-javascript)  [![npm package](https://img.shields.io/npm/v/npmtest-serialize-javascript.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-serialize-javascript) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-serialize-javascript.svg)](https://travis-ci.org/npmtest/node-npmtest-serialize-javascript)

#### Serialize JavaScript to a superset of JSON that includes regular expressions and functions.

[![NPM](https://nodei.co/npm/serialize-javascript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/serialize-javascript)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-serialize-javascript/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-serialize-javascript/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-serialize-javascript/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-serialize-javascript/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-serialize-javascript/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-serialize-javascript/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-serialize-javascript/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-serialize-javascript/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-serialize-javascript/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-serialize-javascript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-serialize-javascript/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-serialize-javascript/build/test-report.html](https://npmtest.github.io/node-npmtest-serialize-javascript/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-serialize-javascript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-serialize-javascript/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-serialize-javascript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-serialize-javascript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-serialize-javascript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-serialize-javascript/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-serialize-javascript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-serialize-javascript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Ferraiuolo"
    },
    "bugs": {
        "url": "https://github.com/yahoo/serialize-javascript/issues"
    },
    "dependencies": {},
    "description": "Serialize JavaScript to a superset of JSON that includes regular expressions and functions.",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "chai": "^1.9.1",
        "istanbul": "^0.3.2",
        "mocha": "^1.21.4",
        "xunit-file": "0.0.5"
    },
    "directories": {},
    "dist": {
        "shasum": "86a4f3752f5c7e47295449b0bbb63d64ba533f05",
        "tarball": "https://registry.npmjs.org/serialize-javascript/-/serialize-javascript-1.3.0.tgz"
    },
    "gitHead": "457a4c6a04859fddea8dd4ae8422f73ade9da72e",
    "homepage": "https://github.com/yahoo/serialize-javascript",
    "keywords": [
        "serialize",
        "serialization",
        "javascript",
        "js",
        "json"
    ],
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ericf"
        }
    ],
    "name": "serialize-javascript",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yahoo/serialize-javascript.git"
    },
    "scripts": {
        "benchmark": "node -v && node test/benchmark/serialize.js",
        "test": "istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
