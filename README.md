# npmtest-node-svm

#### basic test coverage for  [node-svm (v2.1.8)](https://github.com/nicolaspanel/node-svm)  [![npm package](https://img.shields.io/npm/v/npmtest-node-svm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-svm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-svm.svg)](https://travis-ci.org/npmtest/node-npmtest-node-svm)

#### Support Vector Machine for nodejs

[![NPM](https://nodei.co/npm/node-svm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-svm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-svm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-svm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-svm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-svm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-svm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-svm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-svm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-svm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-svm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-svm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-svm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-svm/build/test-report.html](https://npmtest.github.io/node-npmtest-node-svm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-svm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-svm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-svm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-svm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-svm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-svm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-svm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-svm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolas Panel"
    },
    "bin": {
        "node-svm": "./bin/node-svm"
    },
    "bugs": {
        "url": "https://github.com/nicolaspanel/node-svm/issues"
    },
    "config": {
        "blanket": {
            "pattern": [
                "node-svm/lib"
            ]
        }
    },
    "dependencies": {
        "abbrev": "^1.0.5",
        "cardinal": "^0.4.4",
        "chalk": "^0.5.1",
        "graceful-fs": "^4.1.0",
        "handlebars": "^2.0.0",
        "inquirer": "^0.8.0",
        "moment": "^2.8.4",
        "mout": "^0.11.0",
        "nan": "^2.3.3",
        "node-gyp": "~1.0.2",
        "nopt": "~3.0.0",
        "numeric": "^1.2.6",
        "optimist": "^0.6.1",
        "osenv": "^0.1.0",
        "promptly": "^0.2.0",
        "q": "^1.1.2",
        "stringify-object": "^1.0.0",
        "underscore": "^1.7.0"
    },
    "description": "Support Vector Machine for nodejs",
    "devDependencies": {
        "coveralls": "~2.11.0",
        "expect.js": "^0.3.1",
        "grunt": "~0.4.4",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-jshint": "~0.11.0",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-exec": "~0.4.2",
        "grunt-node-gyp": "^0.5.0",
        "grunt-simple-mocha": "~0.4.0",
        "istanbul": "~0.3.2",
        "load-grunt-tasks": "~0.6.0",
        "mocha": "~1.21.4",
        "mocha-lcov-reporter": "0.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5e1c629637fbb8041e65379928a4802305e14157",
        "tarball": "https://registry.npmjs.org/node-svm/-/node-svm-2.1.8.tgz"
    },
    "gitHead": "ee1482ad72836c9ba7717b72672fc7aa0765a9f4",
    "gypfile": true,
    "homepage": "https://github.com/nicolaspanel/node-svm",
    "keywords": [
        "svm",
        "machine learning",
        "libsvm"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "nicolaspanel"
        }
    ],
    "name": "node-svm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nicolaspanel/node-svm.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "grunt"
    },
    "version": "2.1.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
