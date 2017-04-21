# npmtest-yeoman-doctor

#### basic test coverage for  yeoman-doctor (v2.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-yeoman-doctor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yeoman-doctor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yeoman-doctor.svg)](https://travis-ci.org/npmtest/node-npmtest-yeoman-doctor)

#### Detect potential issues with users system that could prevent Yeoman from working correctly

[![NPM](https://nodei.co/npm/yeoman-doctor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yeoman-doctor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yeoman-doctor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yeoman-doctor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yeoman-doctor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yeoman-doctor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yeoman-doctor/build/test-report.html](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yeoman-doctor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yeoman-doctor",
    "version": "2.1.0",
    "description": "Detect potential issues with users system that could prevent Yeoman from working correctly",
    "license": "BSD-2-Clause",
    "author": "Yeoman",
    "repository": "yeoman/doctor",
    "main": "lib/index.js",
    "bin": {
        "yodoctor": "lib/cli.js"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "xo && mocha test/** -R spec"
    },
    "files": [
        "lib"
    ],
    "keywords": [
        "cli-app",
        "cli",
        "yeoman",
        "yo",
        "doctor",
        "system",
        "health",
        "report",
        "check"
    ],
    "dependencies": {
        "bin-version-check": "^2.1.0",
        "chalk": "^1.0.0",
        "each-async": "^1.1.1",
        "log-symbols": "^1.0.1",
        "object-values": "^1.0.0",
        "semver": "^5.0.3",
        "twig": "^0.8.2",
        "user-home": "^2.0.0"
    },
    "devDependencies": {
        "mocha": "^2.0.1",
        "sinon": "^1.12.1",
        "xo": "*"
    },
    "xo": {
        "space": true,
        "envs": [
            "node",
            "mocha"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
