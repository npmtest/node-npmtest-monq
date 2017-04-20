# npmtest-monq

#### basic test coverage for  [monq (v0.3.7)](http://github.com/scttnlsn/monq)  [![npm package](https://img.shields.io/npm/v/npmtest-monq.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-monq) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-monq.svg)](https://travis-ci.org/npmtest/node-npmtest-monq)

#### MongoDB-backed job queue for Node.js

[![NPM](https://nodei.co/npm/monq.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/monq)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-monq/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-monq/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-monq/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-monq/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-monq/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-monq/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-monq/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-monq/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-monq/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-monq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-monq/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-monq/build/test-report.html](https://npmtest.github.io/node-npmtest-monq/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-monq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-monq/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-monq/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-monq/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-monq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-monq/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-monq/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-monq/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "monq",
    "version": "0.3.7",
    "description": "MongoDB-backed job queue for Node.js",
    "homepage": "http://github.com/scttnlsn/monq",
    "author": "Scott Nelson <scott@scttnlsn.com>",
    "license": "MIT",
    "main": "./lib/index",
    "scripts": {
        "test": "./node_modules/.bin/mocha",
        "jsdoc2md": "jsdoc2md lib/*.js > API.md"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/scttnlsn/monq.git"
    },
    "dependencies": {
        "mongojs": "^2.1.0"
    },
    "devDependencies": {
        "async": "^1.5.0",
        "jsdoc-to-markdown": "^2.0.1",
        "mocha": "^2.3.4",
        "sinon": "^1.17.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
