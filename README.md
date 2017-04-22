# npmtest-gulp-tsc

#### basic test coverage for  [gulp-tsc (v1.3.2)](https://github.com/kant2002/gulp-tsc/)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-tsc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-tsc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-tsc.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-tsc)

#### TypeScript compiler for gulp.js

[![NPM](https://nodei.co/npm/gulp-tsc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-tsc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-tsc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-tsc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-tsc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-tsc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-tsc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-tsc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-tsc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-tsc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-tsc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-tsc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-tsc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-tsc/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-tsc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-tsc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-tsc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-tsc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-tsc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-tsc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-tsc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-tsc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-tsc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kota Saito",
        "url": "https://github.com/kotas"
    },
    "bugs": {
        "url": "https://github.com/kant2002/gulp-tsc/issues"
    },
    "contributors": [
        {
            "name": "Cai Lei",
            "url": "https://github.com/ccll"
        },
        {
            "name": "Andrey Kurdyumov"
        }
    ],
    "copyright": "2014 Kota Saito",
    "dependencies": {
        "async": "^1.4.2",
        "byline": "^4.1.1",
        "gulp-util": "^3.0.1",
        "lodash": "^3.2.0",
        "node-version-compare": "^1.0.1",
        "resolve": "^1.0.0",
        "rimraf": "^2.2.6",
        "temp": "^0.8.1",
        "through2": "^2.0.0",
        "vinyl-fs": "^1.0.0",
        "which": "^1.0.5"
    },
    "description": "TypeScript compiler for gulp.js",
    "devDependencies": {
        "del": "^2.0.0",
        "event-stream": "^3.1.0",
        "glob": "^5.0.3",
        "gulp": "^3.8.11",
        "gulp-expect-file": "^0.0.7",
        "mocha": "^2.1.0",
        "run-sequence": "^1.0.2",
        "should": "^7.1.0",
        "sinon": "^1.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5a66f80af3976005e6f5f06b9cfccb0e6d7399ce",
        "tarball": "https://registry.npmjs.org/gulp-tsc/-/gulp-tsc-1.3.2.tgz"
    },
    "gitHead": "327593bc35690ac21039eca0515185da69faad4e",
    "homepage": "https://github.com/kant2002/gulp-tsc/",
    "keywords": [
        "gulpplugin",
        "typescript",
        "gulp",
        "tsc",
        "compile",
        "transpile",
        "compiler"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kotas"
        },
        {
            "name": "kant2002"
        }
    ],
    "name": "gulp-tsc",
    "optionalDependencies": {},
    "peerDependencies": {
        "typescript": ">=1.0.1 || 2.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kant2002/gulp-tsc.git"
    },
    "scripts": {
        "e2e": "gulp --gulpfile test-e2e/gulpfile.js",
        "mocha": "mocha",
        "test": "npm run mocha && npm run e2e"
    },
    "version": "1.3.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
