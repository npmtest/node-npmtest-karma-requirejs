# npmtest-karma-requirejs

#### test coverage for  [karma-requirejs (v1.1.0)](https://github.com/karma-runner/karma-requirejs#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-karma-requirejs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-karma-requirejs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-karma-requirejs.svg)](https://travis-ci.org/npmtest/node-npmtest-karma-requirejs)

#### A Karma plugin. Adapter for RequireJS framework.

[![NPM](https://nodei.co/npm/karma-requirejs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/karma-requirejs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-karma-requirejs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-requirejs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-karma-requirejs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-karma-requirejs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-karma-requirejs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-karma-requirejs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-karma-requirejs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-karma-requirejs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-karma-requirejs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-requirejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-karma-requirejs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-karma-requirejs/build/test-report.html](https://npmtest.github.io/node-npmtest-karma-requirejs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-karma-requirejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-karma-requirejs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-karma-requirejs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-karma-requirejs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-requirejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-requirejs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-karma-requirejs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-karma-requirejs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vojta Jina"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma-requirejs/issues"
    },
    "contributors": [
        {
            "name": "dignifiedquire"
        },
        {
            "name": "Friedel Ziegelmayer"
        },
        {
            "name": "Friedel Ziegelmayer"
        },
        {
            "name": "Mark Ethan Trostler"
        },
        {
            "name": "Jackson Ray Hamilton"
        },
        {
            "name": "Peter Galiba"
        },
        {
            "name": "Sahat Yalkabov"
        },
        {
            "name": "Sven Ambros"
        },
        {
            "name": "Aymeric Beaumet"
        },
        {
            "name": "xorrr"
        },
        {
            "name": "Daniel Tschinder"
        },
        {
            "name": "Ignacio Rivas"
        },
        {
            "name": "Jacob Buck"
        },
        {
            "name": "Janusz Jablonski"
        },
        {
            "name": "Kevin Warnock"
        }
    ],
    "dependencies": {},
    "description": "A Karma plugin. Adapter for RequireJS framework.",
    "devDependencies": {
        "eslint": "^2.4.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-standard": "^1.3.2",
        "grunt": "~0.4.1",
        "grunt-auto-release": "~0.0.2",
        "grunt-bump": "~0.7.0",
        "grunt-contrib-jshint": "~1.0",
        "grunt-eslint": "^18.0.0",
        "grunt-karma": "1.x || ~0.12",
        "grunt-npm": "~0.0.2",
        "jasmine-core": "^2.4.1",
        "karma": "1.x || ^0.13.22",
        "karma-chrome-launcher": "1.x || ^0.2.2",
        "karma-firefox-launcher": "1.x || ^0.1.7",
        "karma-jasmine": "1.x || ^0.3.8",
        "requirejs": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fddae2cb87d7ebc16fb0222893564d7fee578798",
        "tarball": "https://registry.npmjs.org/karma-requirejs/-/karma-requirejs-1.1.0.tgz"
    },
    "gitHead": "31aeefb025a7d3b7e77172edbfa7b42a05468aee",
    "homepage": "https://github.com/karma-runner/karma-requirejs#readme",
    "keywords": [
        "karma-plugin",
        "karma-adapter",
        "requirejs"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "vojtajina"
        },
        {
            "name": "zzo"
        },
        {
            "name": "dignifiedquire"
        }
    ],
    "name": "karma-requirejs",
    "optionalDependencies": {},
    "peerDependencies": {
        "karma": ">=0.9",
        "requirejs": "^2.1.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/karma-runner/karma-requirejs.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
