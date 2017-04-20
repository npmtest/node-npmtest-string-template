# npmtest-string-template

#### basic test coverage for  [string-template (v1.0.0)](https://github.com/Matt-Esch/string-template)  [![npm package](https://img.shields.io/npm/v/npmtest-string-template.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-string-template) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-string-template.svg)](https://travis-ci.org/npmtest/node-npmtest-string-template)

#### A simple string template function based on named or indexed arguments

[![NPM](https://nodei.co/npm/string-template.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/string-template)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-string-template/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-string-template/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-string-template/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-string-template/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-string-template/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-string-template/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-string-template/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-string-template/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-string-template/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-string-template/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-string-template/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-string-template/build/test-report.html](https://npmtest.github.io/node-npmtest-string-template/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-string-template/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-string-template/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-string-template/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-string-template/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-string-template/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-string-template/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-string-template/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-string-template/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt-Esch"
    },
    "bugs": {
        "url": "https://github.com/Matt-Esch/string-template/issues"
    },
    "contributors": [
        {
            "name": "Matt-Esch"
        }
    ],
    "dependencies": {},
    "description": "A simple string template function based on named or indexed arguments",
    "devDependencies": {
        "istanbul": "^0.4.1",
        "opn": "^3.0.3",
        "tape": "~1.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "9e9f2233dc00f218718ec379a28a5673ecca8b96",
        "tarball": "https://registry.npmjs.org/string-template/-/string-template-1.0.0.tgz"
    },
    "gitHead": "1a936280d4c9569035f9ac6a9808df564d413b30",
    "homepage": "https://github.com/Matt-Esch/string-template",
    "keywords": [
        "template",
        "string",
        "format",
        "replace",
        "arguments"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "mattesch"
        }
    ],
    "name": "string-template",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Matt-Esch/string-template.git"
    },
    "scripts": {
        "cover": "istanbul cover --report none --print detail ./test/index.js",
        "test": "node ./test/index.js",
        "travis-test": "istanbul cover ./test/index.js && ((cat coverage/lcov.info | coveralls) || exit 0)",
        "view-cover": "istanbul report html && opn --no-wait ./coverage/index.html"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "ie/8..latest",
            "firefox/16..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
