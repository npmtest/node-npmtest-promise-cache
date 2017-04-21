# npmtest-promise-cache

#### basic test coverage for  [promise-cache (v0.1.8)](https://github.com/Vinelab/node-promise-cache)  [![npm package](https://img.shields.io/npm/v/npmtest-promise-cache.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-promise-cache) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-promise-cache.svg)](https://travis-ci.org/npmtest/node-npmtest-promise-cache)

#### A caching tool that can easily be expanded with different cache stores and preserves data-types.

[![NPM](https://nodei.co/npm/promise-cache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/promise-cache)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-promise-cache/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-promise-cache/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-promise-cache/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-promise-cache/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-promise-cache/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-promise-cache/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-promise-cache/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-promise-cache/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-promise-cache/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-promise-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-promise-cache/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-promise-cache/build/test-report.html](https://npmtest.github.io/node-npmtest-promise-cache/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-promise-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-promise-cache/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-promise-cache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-promise-cache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-promise-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-promise-cache/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-promise-cache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-promise-cache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "promise-cache",
    "version": "0.1.8",
    "description": "A caching tool that can easily be expanded with different cache stores and preserves data-types.",
    "main": "lib/Cache.js",
    "scripts": {
        "spec": "./node_modules/.bin/jasmine-node --coffee spec --verbose",
        "test": "./node_modules/.bin/jasmine-node --coffee test --verbose"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Vinelab/node-promise-cache"
    },
    "keywords": [
        "cache",
        "promise",
        "redis"
    ],
    "author": "Abed Halawi <abed.halawi@vinelab.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Vinelab/node-promise-cache/issues"
    },
    "homepage": "https://github.com/Vinelab/node-promise-cache",
    "dependencies": {
        "q": "~2.0.2",
        "extend": "~1.3.0",
        "sol-redis-pool": "~0.2.0"
    },
    "devDependencies": {
        "jasmine-node": "~2.0.0",
        "coffee-script": "~1.7.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
