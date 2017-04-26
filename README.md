# npmtest-flow-bin

#### basic test coverage for  [flow-bin (v0.44.2)](https://github.com/flowtype/flow-bin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-flow-bin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-flow-bin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-flow-bin.svg)](https://travis-ci.org/npmtest/node-npmtest-flow-bin)

#### Binary wrapper for Flow - A static type checker for JavaScript

[![NPM](https://nodei.co/npm/flow-bin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/flow-bin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-flow-bin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-flow-bin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-flow-bin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-flow-bin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-flow-bin/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-flow-bin/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-flow-bin/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-flow-bin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-flow-bin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-flow-bin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-flow-bin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-flow-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-flow-bin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-flow-bin/build/test-report.html](https://npmtest.github.io/node-npmtest-flow-bin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-flow-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-flow-bin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-flow-bin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-flow-bin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-flow-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-flow-bin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-flow-bin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-flow-bin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bin": {
        "flow": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/flowtype/flow-bin/issues"
    },
    "dependencies": {},
    "description": "Binary wrapper for Flow - A static type checker for JavaScript",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "3893c7db5de043ed82674f327a04b1309db208b5",
        "tarball": "https://registry.npmjs.org/flow-bin/-/flow-bin-0.44.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "flow-linux64-v*/flow",
        "flow-osx-v*/flow",
        "flow-win64-v*/flow.exe",
        "vendor",
        "cli.js",
        "index.js",
        "SHASUM256.txt"
    ],
    "gitHead": "f227bbf39a4e05d0c1c23997c0a06401ef416e5b",
    "homepage": "https://github.com/flowtype/flow-bin#readme",
    "keywords": [
        "cli-app",
        "cli",
        "bin",
        "binary",
        "flow",
        "facebook",
        "type",
        "inference",
        "check",
        "checker",
        "javascript",
        "js",
        "wrapper"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "gabelevi"
        },
        {
            "name": "jeffmo"
        },
        {
            "name": "kevva"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "flow-bin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/flowtype/flow-bin.git"
    },
    "scripts": {
        "test": "echo \"Error: Run 'make test' instead.\" && exit 1",
        "verify": "shasum -c SHASUM256.txt"
    },
    "version": "0.44.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
