# test coverage for  [errorhandler (v1.5.0)](https://github.com/expressjs/errorhandler)  [![npm package](https://img.shields.io/npm/v/npmtest-errorhandler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-errorhandler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-errorhandler.svg)](https://travis-ci.org/npmtest/node-npmtest-errorhandler)
#### Development-only error handler middleware

[![NPM](https://nodei.co/npm/errorhandler.png?downloads=true)](https://www.npmjs.com/package/errorhandler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-errorhandler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-errorhandler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-errorhandler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-errorhandler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-errorhandler/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-errorhandler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-errorhandler/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-errorhandler/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-errorhandler/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-errorhandler/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-errorhandler%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-errorhandler/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-errorhandler/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-errorhandler%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-errorhandler/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-errorhandler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-errorhandler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/errorhandler/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "Jonathan Ong",
            "email": "me@jongleberry.com",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "accepts": "~1.3.3",
        "escape-html": "~1.0.3"
    },
    "description": "Development-only error handler middleware",
    "devDependencies": {
        "after": "0.8.2",
        "eslint": "3.10.2",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-promise": "3.3.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "eaba64ca5d542a311ac945f582defc336165d9f4",
        "tarball": "https://registry.npmjs.org/errorhandler/-/errorhandler-1.5.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "public/",
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "6bf441d94197219ea6e0f392cb8ccd72602ad357",
    "homepage": "https://github.com/expressjs/errorhandler",
    "license": "MIT",
    "maintainers": [
        {
            "name": "defunctzombie",
            "email": "shtylman@gmail.com"
        },
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "fishrock123",
            "email": "fishrock123@rocketmail.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "mscdex",
            "email": "mscdex@mscdex.net"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "errorhandler",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/errorhandler.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
