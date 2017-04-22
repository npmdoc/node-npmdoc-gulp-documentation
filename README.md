# npmdoc-gulp-documentation

#### api documentation for  [gulp-documentation (v3.2.0)](https://github.com/documentationjs/gulp-documentation#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-documentation.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-documentation) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-documentation.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-documentation)

#### documentation plugin for gulp

[![NPM](https://nodei.co/npm/gulp-documentation.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-documentation)

- [https://npmdoc.github.io/node-npmdoc-gulp-documentation/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-documentation/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-documentation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-documentation/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-documentation/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-documentation/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tom MacWright"
    },
    "bugs": {
        "url": "https://github.com/documentationjs/gulp-documentation/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "documentation": "4.0.0-beta.18",
        "through2": "^2.0.1",
        "vinyl": "^2.0.0"
    },
    "description": "documentation plugin for gulp",
    "devDependencies": {
        "concat-stream": "^1.4.8",
        "cz-conventional-changelog": "^2.0.0",
        "gulp": "^3.8.11",
        "husky": "^0.13.3",
        "lint-staged": "^3.4.0",
        "prettier": "^0.22.0",
        "standard-version": "^4.0.0",
        "tap": "10.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "371cc33c83cfe04c45ca88ac582160dca69b85d6",
        "tarball": "https://registry.npmjs.org/gulp-documentation/-/gulp-documentation-3.2.0.tgz"
    },
    "gitHead": "ace561e6cfebfac83624060376a0b5177505250c",
    "homepage": "https://github.com/documentationjs/gulp-documentation#readme",
    "keywords": [
        "documentation",
        "gulp",
        "gulpplugin",
        "jsdoc"
    ],
    "license": "BSD-2-Clause",
    "lint-staged": {
        "*.js": [
            "prettier --write --single-quote"
        ]
    },
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "tmcw"
        }
    ],
    "name": "gulp-documentation",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/documentationjs/gulp-documentation.git"
    },
    "scripts": {
        "docs": "documentation readme index.js --section=API",
        "format": "prettier --write '{lib,test}/**/*.js' --single-quote",
        "precommit": "lint-staged --verbose",
        "release": "standard-version"
    },
    "version": "3.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
