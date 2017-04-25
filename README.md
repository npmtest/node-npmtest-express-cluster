# npmtest-express-cluster

#### basic test coverage for  [express-cluster (v0.0.4)](https://github.com/Flipboard/express-cluster)  [![npm package](https://img.shields.io/npm/v/npmtest-express-cluster.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-cluster) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-cluster.svg)](https://travis-ci.org/npmtest/node-npmtest-express-cluster)

#### Simple drop-in for express apps to spawn multiple processes

[![NPM](https://nodei.co/npm/express-cluster.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-cluster)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-cluster/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-cluster/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-cluster/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-cluster/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-cluster/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-cluster/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-cluster/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-cluster/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-cluster/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-cluster/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-cluster/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-cluster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-cluster/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-cluster/build/test-report.html](https://npmtest.github.io/node-npmtest-express-cluster/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-cluster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-cluster/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-cluster/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-cluster/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-cluster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-cluster/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-cluster/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-cluster/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eden Li"
    },
    "bugs": {
        "url": "https://github.com/Flipboard/express-cluster/issues"
    },
    "dependencies": {},
    "description": "Simple drop-in for express apps to spawn multiple processes",
    "devDependencies": {
        "coffee-script": "~1.10.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7aa5c39779bbc7550a30525d02b4c022e40b8798",
        "tarball": "https://registry.npmjs.org/express-cluster/-/express-cluster-0.0.4.tgz"
    },
    "gitHead": "974423e7045395d75c3c22179f62491965195719",
    "homepage": "https://github.com/Flipboard/express-cluster",
    "keywords": [
        "cluster",
        "express",
        "http",
        "https",
        "net",
        "listener"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "eden"
        }
    ],
    "name": "express-cluster",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Flipboard/express-cluster.git"
    },
    "scripts": {
        "prepublish": "coffee -o lib/ -c src/index.coffee"
    },
    "version": "0.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
