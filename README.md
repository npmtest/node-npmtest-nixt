# npmtest-nixt

#### basic test coverage for  [nixt (v0.5.0)](https://github.com/vesln/nixt)  [![npm package](https://img.shields.io/npm/v/npmtest-nixt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nixt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nixt.svg)](https://travis-ci.org/npmtest/node-npmtest-nixt)

#### Simple and powerful testing for command-line apps

[![NPM](https://nodei.co/npm/nixt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nixt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nixt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nixt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nixt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nixt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nixt/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nixt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nixt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nixt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nixt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nixt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nixt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nixt/build/test-report.html](https://npmtest.github.io/node-npmtest-nixt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nixt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nixt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nixt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nixt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nixt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nixt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nixt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nixt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nixt",
    "version": "0.5.0",
    "description": "Simple and powerful testing for command-line apps",
    "keywords": [
        "testing",
        "test",
        "cli",
        "command-line",
        "command-line apps",
        "command-line applications"
    ],
    "main": "index.js",
    "homepage": "https://github.com/vesln/nixt",
    "directories": {
        "test": "test"
    },
    "scripts": {
        "test": "make test"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/vesln/nixt.git"
    },
    "author": "Veselin Todorov <hi@vesln.com>",
    "license": "MIT",
    "devDependencies": {
        "chai": "*",
        "hydro": "*",
        "hydro-dot": "*",
        "hydro-chai": "*",
        "hydro-bdd": "*",
        "prompt": "^0.2.12"
    },
    "dependencies": {
        "assertion-error": "~1.0.0",
        "clone": "^1.0.2",
        "shell-quote": "^1.4.1",
        "string": "^3.3.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
