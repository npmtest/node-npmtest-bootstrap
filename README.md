# npmtest-bootstrap

#### test coverage for  [bootstrap (v3.3.7)](http://getbootstrap.com)  [![npm package](https://img.shields.io/npm/v/npmtest-bootstrap.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bootstrap) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bootstrap.svg)](https://travis-ci.org/npmtest/node-npmtest-bootstrap)

#### The most popular front-end framework for developing responsive, mobile first projects on the web.

[![NPM](https://nodei.co/npm/bootstrap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bootstrap)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bootstrap/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bootstrap/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bootstrap/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bootstrap/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bootstrap/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bootstrap/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bootstrap/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bootstrap/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bootstrap/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bootstrap/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bootstrap/build/test-report.html](https://npmtest.github.io/node-npmtest-bootstrap/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bootstrap/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bootstrap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bootstrap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bootstrap/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bootstrap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bootstrap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Twitter, Inc."
    },
    "bugs": {
        "url": "https://github.com/twbs/bootstrap/issues"
    },
    "dependencies": {},
    "description": "The most popular front-end framework for developing responsive, mobile first projects on the web.",
    "devDependencies": {
        "btoa": "~1.1.2",
        "glob": "~7.0.3",
        "grunt": "~1.0.1",
        "grunt-autoprefixer": "~3.0.4",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-compress": "~1.3.0",
        "grunt-contrib-concat": "~1.0.0",
        "grunt-contrib-connect": "~1.0.0",
        "grunt-contrib-copy": "~1.0.0",
        "grunt-contrib-csslint": "~1.0.0",
        "grunt-contrib-cssmin": "~1.0.0",
        "grunt-contrib-htmlmin": "~1.5.0",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-less": "~1.3.0",
        "grunt-contrib-pug": "~1.0.0",
        "grunt-contrib-qunit": "~0.7.0",
        "grunt-contrib-uglify": "~1.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-csscomb": "~3.1.0",
        "grunt-exec": "~1.0.0",
        "grunt-html": "~8.0.1",
        "grunt-jekyll": "~0.4.4",
        "grunt-jscs": "~3.0.1",
        "grunt-saucelabs": "~9.0.0",
        "load-grunt-tasks": "~3.5.0",
        "markdown-it": "^7.0.0",
        "shelljs": "^0.7.0",
        "shx": "^0.1.2",
        "time-grunt": "^1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5a389394549f23330875a3b150656574f8a9eb71",
        "tarball": "https://registry.npmjs.org/bootstrap/-/bootstrap-3.3.7.tgz"
    },
    "engines": {
        "node": ">=0.10.1"
    },
    "files": [
        "dist",
        "fonts",
        "grunt",
        "js/*.js",
        "less/**/*.less",
        "Gruntfile.js",
        "LICENSE"
    ],
    "gitHead": "0b9c4a4007c44201dce9a6cc1a38407005c26c86",
    "homepage": "http://getbootstrap.com",
    "jspm": {
        "main": "js/bootstrap",
        "shim": {
            "js/bootstrap": {
                "deps": "jquery",
                "exports": "$"
            }
        },
        "files": [
            "css",
            "fonts",
            "js"
        ]
    },
    "keywords": [
        "css",
        "less",
        "mobile-first",
        "responsive",
        "front-end",
        "framework",
        "web"
    ],
    "less": "less/bootstrap.less",
    "license": "MIT",
    "main": "./dist/js/npm",
    "maintainers": [
        {
            "name": "twbs"
        }
    ],
    "name": "bootstrap",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/twbs/bootstrap.git"
    },
    "scripts": {
        "change-version": "node grunt/change-version.js",
        "test": "grunt test",
        "update-shrinkwrap": "npm shrinkwrap --dev && shx mv ./npm-shrinkwrap.json ./grunt/npm-shrinkwrap.json"
    },
    "style": "dist/css/bootstrap.css",
    "version": "3.3.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
