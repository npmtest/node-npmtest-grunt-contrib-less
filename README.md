# npmtest-grunt-contrib-less

#### test coverage for  [grunt-contrib-less (v1.4.1)](https://github.com/gruntjs/grunt-contrib-less#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-contrib-less.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-contrib-less) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-contrib-less.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-contrib-less)

#### Compile LESS files to CSS

[![NPM](https://nodei.co/npm/grunt-contrib-less.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-contrib-less)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-contrib-less/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-contrib-less/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-contrib-less/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-contrib-less/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-contrib-less/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-contrib-less/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-contrib-less/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-contrib-less/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "appveyor_id": "e3aa4d07xe4w4u05",
    "author": {
        "name": "Grunt Team",
        "url": "http://gruntjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gruntjs/grunt-contrib-less/issues"
    },
    "contributors": [
        {
            "name": "Tyler Kellen",
            "url": "http://goingslowly.com/"
        },
        {
            "name": "\"Cowboy\" Ben Alman",
            "url": "http://benalman.com/"
        },
        {
            "name": "Chris Talkington",
            "url": "http://christalkington.com/"
        },
        {
            "name": "Teddy Cross",
            "url": "http://tkaz.ec/"
        },
        {
            "name": "Justin Searls",
            "url": "http://about.me/searls/"
        },
        {
            "name": "Thomas Boyt",
            "url": "http://www.thomasboyt.com/"
        },
        {
            "name": "Jake Harding",
            "url": "http://thejakeharding.com/"
        },
        {
            "name": "Jason Karns",
            "url": "http://jasonkarns.com/"
        },
        {
            "name": "Sebastian Tschan",
            "url": "https://blueimp.net/"
        }
    ],
    "dependencies": {
        "async": "^2.0.0",
        "chalk": "^1.0.0",
        "less": "~2.7.1",
        "lodash": "^4.8.2"
    },
    "description": "Compile LESS files to CSS",
    "devDependencies": {
        "grunt": "^1.0.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-internal": "^1.1.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "less-plugin-clean-css": "^1.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3bbdec0b75d12ceaa55d62943625c0b0861cdf6f",
        "tarball": "https://registry.npmjs.org/grunt-contrib-less/-/grunt-contrib-less-1.4.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "tasks"
    ],
    "gitHead": "c282d0d52c55631bb468e6262fb2fd9de248d5c6",
    "homepage": "https://github.com/gruntjs/grunt-contrib-less#readme",
    "keywords": [
        "gruntplugin"
    ],
    "license": "MIT",
    "main": "tasks/less.js",
    "maintainers": [
        {
            "name": "cowboy"
        },
        {
            "name": "jmeas"
        },
        {
            "name": "shama"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "tkellen"
        },
        {
            "name": "vladikoff"
        },
        {
            "name": "xhmikosr"
        }
    ],
    "name": "grunt-contrib-less",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gruntjs/grunt-contrib-less.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
