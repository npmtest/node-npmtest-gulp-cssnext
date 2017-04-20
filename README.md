# npmtest-gulp-cssnext

#### basic test coverage for  [gulp-cssnext (v1.0.1)](http://cssnext.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-cssnext.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-cssnext) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-cssnext.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-cssnext)

#### Use tomorrow's CSS syntax, today, using cssnext via Gulp

[![NPM](https://nodei.co/npm/gulp-cssnext.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-cssnext)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-cssnext/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-cssnext/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-cssnext/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-cssnext/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-cssnext/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-cssnext/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-cssnext/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-cssnext/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-cssnext/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-cssnext",
    "version": "1.0.1",
    "description": "Use tomorrow's CSS syntax, today, using cssnext via Gulp",
    "keywords": [
        "css",
        "cssnext",
        "preprocessor",
        "postprocessor",
        "rework",
        "postcss",
        "autoprefixer",
        "gulp",
        "gulpplugin"
    ],
    "author": "bloodyowl",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git://github.com/cssnext/gulp-cssnext.git"
    },
    "homepage": "http://cssnext.io/",
    "bugs": {
        "url": "https://github.com/cssnext/gulp-cssnext/issues"
    },
    "files": [
        "CHANGELOG.md",
        "LICENSE",
        "index.js"
    ],
    "dependencies": {
        "cssnext": "^1.0.0",
        "gulp-util": "^3.0.0",
        "through2": "^0.6.1"
    },
    "devDependencies": {
        "eslint": "^0.22.1",
        "tape": "^3.0.0"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "npm run lint && tape 'test/**.js'"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
