# npmtest-rxjs

#### test coverage for  [rxjs (v5.3.0)](https://github.com/ReactiveX/RxJS)  [![npm package](https://img.shields.io/npm/v/npmtest-rxjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rxjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rxjs.svg)](https://travis-ci.org/npmtest/node-npmtest-rxjs)

#### Reactive Extensions for modern JavaScript

[![NPM](https://nodei.co/npm/rxjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rxjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rxjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rxjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rxjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rxjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rxjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rxjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rxjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rxjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rxjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rxjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rxjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rxjs/build/test-report.html](https://npmtest.github.io/node-npmtest-rxjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rxjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rxjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rxjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rxjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rxjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rxjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rxjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rxjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Lesh"
    },
    "bugs": {
        "url": "https://github.com/ReactiveX/RxJS/issues"
    },
    "config": {
        "commitizen": {
            "path": "cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Ben Lesh"
        },
        {
            "name": "Paul Taylor"
        },
        {
            "name": "Jeff Cross"
        },
        {
            "name": "Matthew Podwysocki"
        },
        {
            "name": "OJ Kwon"
        },
        {
            "name": "Andre Staltz"
        }
    ],
    "dependencies": {
        "symbol-observable": "^1.0.1"
    },
    "description": "Reactive Extensions for modern JavaScript",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "benchpress": "2.0.0-beta.1",
        "chai": "^3.5.0",
        "color": "^0.11.1",
        "colors": "1.1.2",
        "commitizen": "^2.8.6",
        "coveralls": "^2.11.13",
        "cz-conventional-changelog": "^1.2.0",
        "doctoc": "^1.0.0",
        "escape-string-regexp": "^1.0.5 ",
        "esdoc": "^0.4.7",
        "eslint": "^3.8.0",
        "fs-extra": "^2.1.2",
        "glob": "^7.0.3",
        "gm": "^1.22.0",
        "google-closure-compiler-js": "^20170218.0.0",
        "gzip-size": "^3.0.0",
        "http-server": "^0.9.0",
        "husky": "^0.13.3",
        "lint-staged": "^3.2.5",
        "lodash": "^4.15.0",
        "madge": "^1.4.3",
        "markdown-doctest": "^0.9.1",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "mocha": "^3.0.2",
        "mocha-in-sauce": "0.0.1",
        "npm-run-all": "^4.0.2",
        "npm-scripts-info": "^0.3.4",
        "nyc": "^10.2.0",
        "opn-cli": "^3.1.0",
        "platform": "^1.3.1",
        "promise": "^7.1.1",
        "protractor": "^3.1.1",
        "rollup": "0.36.3",
        "rollup-plugin-inject": "^2.0.0",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rx": "latest",
        "shx": "^0.2.2",
        "sinon": "^2.1.0",
        "sinon-chai": "^2.9.0",
        "source-map-support": "^0.4.0",
        "tslib": "^1.5.0",
        "tslint": "^4.4.2",
        "typescript": "~2.0.6",
        "typings": "^2.0.0",
        "validate-commit-msg": "^2.3.1",
        "watch": "^1.0.1",
        "webpack": "^1.13.1",
        "xmlhttprequest": "1.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d88ccbdd46af290cbdb97d5d8055e52453fabe2d",
        "tarball": "https://registry.npmjs.org/rxjs/-/rxjs-5.3.0.tgz"
    },
    "engines": {
        "npm": ">=2.0.0"
    },
    "homepage": "https://github.com/ReactiveX/RxJS",
    "keywords": [
        "Rx",
        "RxJS",
        "ReactiveX",
        "ReactiveExtensions",
        "Streams",
        "Observables",
        "Observable",
        "Stream",
        "ES6",
        "ES2015"
    ],
    "license": "Apache-2.0",
    "lint-staged": {
        "*.@(js)": [
            "eslint --fix",
            "git add"
        ],
        "*.@(ts)": [
            "tslint --fix",
            "git add"
        ]
    },
    "main": "Rx.js",
    "maintainers": [
        {
            "name": "blesh"
        },
        {
            "name": "jeffbcross"
        }
    ],
    "name": "rxjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ReactiveX/RxJS.git"
    },
    "scripts": {},
    "scripts-info": {
        "info": "List available script",
        "build_all": "Build all packages (ES6, CJS, UMD) and generate packages",
        "build_cjs": "Build CJS package with clean up existing build, copy source into dist",
        "build_es6": "Build ES6 package with clean up existing build, copy source into dist",
        "build_closure_core": "Minify Global core build using closure compiler",
        "build_global": "Build Global package, then minify build",
        "build_perf": "Build CJS & Global build, run macro performance test",
        "build_test": "Build CJS package & test spec, execute mocha test runner",
        "build_cover": "Run lint to current code, build CJS & test spec, execute test coverage",
        "build_docs": "Build ES6 & global package, create documentation using it",
        "build_spec": "Build test specs",
        "check_circular_dependencies": "Check codebase has circular dependencies",
        "clean_spec": "Clean up existing test spec build output",
        "clean_dist_cjs": "Clean up existing CJS package output",
        "clean_dist_es6": "Clean up existing ES6 package output",
        "clean_dist_global": "Clean up existing Global package output",
        "commit": "Run git commit wizard",
        "compile_dist_cjs": "Compile codebase into CJS module",
        "compile_module_es6": "Compile codebase into ES6",
        "cover": "Execute test coverage",
        "lint_perf": "Run lint against performance test suite",
        "lint_spec": "Run lint against test spec",
        "lint_src": "Run lint against source",
        "lint": "Run lint against everything",
        "perf": "Run macro performance benchmark",
        "perf_micro": "Run micro performance benchmark",
        "test_mocha": "Execute mocha test runner against existing test spec build",
        "test_browser": "Execute mocha test runner on browser against existing test spec build",
        "test": "Clean up existing test spec build, build test spec and execute mocha test runner",
        "tests2png": "Generate marble diagram image from test spec",
        "watch": "Watch codebase, trigger compile when source code changes"
    },
    "typings": "Rx.d.ts",
    "version": "5.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
