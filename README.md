# npmtest-changelog-maker

#### basic test coverage for  changelog-maker (v2.2.5)  [![npm package](https://img.shields.io/npm/v/npmtest-changelog-maker.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-changelog-maker) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-changelog-maker.svg)](https://travis-ci.org/npmtest/node-npmtest-changelog-maker)

#### A git log to CHANGELOG.md tool

[![NPM](https://nodei.co/npm/changelog-maker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/changelog-maker)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-changelog-maker/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-changelog-maker/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-changelog-maker/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-changelog-maker/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-changelog-maker/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-changelog-maker/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-changelog-maker/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-changelog-maker/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-changelog-maker/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-changelog-maker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-changelog-maker/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-changelog-maker/build/test-report.html](https://npmtest.github.io/node-npmtest-changelog-maker/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-changelog-maker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-changelog-maker/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-changelog-maker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-changelog-maker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-changelog-maker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-changelog-maker/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-changelog-maker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-changelog-maker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "changelog-maker",
    "version": "2.2.5",
    "description": "A git log to CHANGELOG.md tool",
    "main": "changelog-maker.js",
    "bin": {
        "changelog-maker": "./changelog-maker.js"
    },
    "author": "Rod <rod@vagg.org> (http://r.va.gg/)",
    "license": "MIT",
    "dependencies": {
        "async": "~2.1.5",
        "bl": "~1.2.0",
        "chalk": "~1.1.3",
        "commit-stream": "~1.0.2",
        "debug": "~2.6.1",
        "ghauth": "~3.2.1",
        "ghissues": "~1.1.3",
        "gitexec": "~1.0.0",
        "list-stream": "~1.0.1",
        "minimist": "~1.2.0",
        "pkg-to-id": "~0.0.3",
        "split2": "~2.1.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/rvagg/changelog-maker.git"
    },
    "preferGlobal": true,
    "scripts": {
        "lint": "jshint ./*js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
