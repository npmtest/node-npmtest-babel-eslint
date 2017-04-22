# npmtest-babel-eslint

#### basic test coverage for  [babel-eslint (v7.2.3)](https://github.com/babel/babel-eslint)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-eslint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-eslint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-eslint.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-eslint)

#### Custom parser for ESLint

[![NPM](https://nodei.co/npm/babel-eslint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-eslint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-eslint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-eslint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-eslint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-eslint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-eslint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-eslint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-eslint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-eslint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-eslint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-eslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-eslint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-eslint/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-eslint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-eslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-eslint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-eslint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-eslint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-eslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-eslint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-eslint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-eslint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian McKenzie"
    },
    "bugs": {
        "url": "https://github.com/babel/babel-eslint/issues"
    },
    "dependencies": {
        "babel-code-frame": "^6.22.0",
        "babel-traverse": "^6.23.1",
        "babel-types": "^6.23.0",
        "babylon": "^6.17.0"
    },
    "description": "Custom parser for ESLint",
    "devDependencies": {
        "babel-eslint": "^7.0.0",
        "dedent": "^0.7.0",
        "eslint": "^3.18.0",
        "eslint-config-babel": "^6.0.0",
        "eslint-plugin-flowtype": "^2.30.3",
        "espree": "^3.4.0",
        "mocha": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b2fe2d80126470f5c19442dc757253a897710827",
        "tarball": "https://registry.npmjs.org/babel-eslint/-/babel-eslint-7.2.3.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "babylon-to-espree"
    ],
    "gitHead": "94bb5a1d36c5624fb612de2dd704ffa586d38845",
    "homepage": "https://github.com/babel/babel-eslint",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "danez"
        },
        {
            "name": "hzoo"
        },
        {
            "name": "sebmck"
        }
    ],
    "name": "babel-eslint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/babel/babel-eslint.git"
    },
    "scripts": {
        "changelog": "git log 'git describe --tags --abbrev=0'..HEAD --pretty=format:' * %s (%an)' | grep -v 'Merge pull request'",
        "fix": "eslint index.js babylon-to-espree test --fix",
        "lint": "eslint index.js babylon-to-espree test",
        "preversion": "npm test",
        "test": "npm run lint && npm run test-only",
        "test-only": "mocha"
    },
    "version": "7.2.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
