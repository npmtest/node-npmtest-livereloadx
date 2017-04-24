# npmtest-livereloadx

#### basic test coverage for  [livereloadx (v0.3.9)](https://github.com/nitoyon/livereloadx#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-livereloadx.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-livereloadx) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-livereloadx.svg)](https://travis-ci.org/npmtest/node-npmtest-livereloadx)

#### An implementation of the LiveReload 2 server in Node.js

[![NPM](https://nodei.co/npm/livereloadx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/livereloadx)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-livereloadx/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-livereloadx/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-livereloadx/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-livereloadx/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-livereloadx/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-livereloadx/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-livereloadx/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-livereloadx/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-livereloadx/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-livereloadx/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-livereloadx/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-livereloadx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-livereloadx/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-livereloadx/build/test-report.html](https://npmtest.github.io/node-npmtest-livereloadx/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-livereloadx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-livereloadx/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-livereloadx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-livereloadx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-livereloadx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-livereloadx/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-livereloadx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-livereloadx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kenichi Saita"
    },
    "bin": {
        "livereloadx": "bin/livereloadx.js"
    },
    "bugs": {
        "url": "https://github.com/nitoyon/livereloadx/issues"
    },
    "dependencies": {
        "commander": "~2.3.0",
        "debug": "~2.0.0",
        "fsmonitor": "~ 0.2.4",
        "http-proxy": "~ 0.8.7",
        "minimatch": "~ 0.2.11",
        "pause": "~ 0.0.1",
        "send": "~ 0.9.3",
        "ws": "~ 0.8.0"
    },
    "description": "An implementation of the LiveReload 2 server in Node.js",
    "devDependencies": {
        "grunt": "~0.4.1",
        "grunt-contrib-jshint": "~0.1.1",
        "grunt-contrib-watch": "~0.4.4",
        "grunt-mocha-test": "~0.5.0",
        "mocha": ">= 1.7.4",
        "should": "~ 2.1.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "d93eb6a0fe0882f5473a90d85c6e0bdc053ecb21",
        "tarball": "https://registry.npmjs.org/livereloadx/-/livereloadx-0.3.9.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "6889c13527a3c895e28d345f7df56b0dea25130b",
    "homepage": "https://github.com/nitoyon/livereloadx#readme",
    "keywords": [
        "LiveReload",
        "browser",
        "gruntplugin",
        "test"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/nitoyon/livereloadx/blob/master/LICENSE-MIT"
        }
    ],
    "main": "lib/index",
    "maintainers": [
        {
            "name": "nitoyon"
        }
    ],
    "name": "livereloadx",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nitoyon/livereloadx.git"
    },
    "scripts": {
        "test": "grunt"
    },
    "version": "0.3.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
