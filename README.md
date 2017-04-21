# npmtest-vivagraphjs

#### basic test coverage for  [vivagraphjs (v0.8.2)](https://github.com/anvaka/VivaGraphJS#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-vivagraphjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vivagraphjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vivagraphjs.svg)](https://travis-ci.org/npmtest/node-npmtest-vivagraphjs)

#### Graph Drawing Library

[![NPM](https://nodei.co/npm/vivagraphjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vivagraphjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vivagraphjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vivagraphjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vivagraphjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vivagraphjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vivagraphjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vivagraphjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vivagraphjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vivagraphjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vivagraphjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vivagraphjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vivagraphjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vivagraphjs/build/test-report.html](https://npmtest.github.io/node-npmtest-vivagraphjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vivagraphjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vivagraphjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vivagraphjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vivagraphjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vivagraphjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vivagraphjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vivagraphjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vivagraphjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrei Kashcha"
    },
    "bugs": {
        "url": "https://github.com/anvaka/VivaGraphJS/issues"
    },
    "dependencies": {
        "gintersect": "0.1.0",
        "ngraph.centrality": "0.1.3",
        "ngraph.events": "0.0.3",
        "ngraph.forcelayout": "0.0.21",
        "ngraph.fromjson": "0.1.7",
        "ngraph.generators": "0.0.15",
        "ngraph.graph": "0.0.11",
        "ngraph.merge": "0.0.1",
        "ngraph.random": "0.0.1",
        "ngraph.tojson": "0.1.3",
        "simplesvg": "0.0.10"
    },
    "description": "Graph Drawing Library",
    "devDependencies": {
        "browserify": "^8.0.3",
        "del": "^1.1.1",
        "gulp": "^3.9.0",
        "gulp-rename": "^1.2.0",
        "gulp-run": "^1.6.5",
        "gulp-uglify": "^1.0.2",
        "gulp-util": "^3.0.2",
        "tap": "^0.4.13",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.0.0"
    },
    "directories": {
        "doc": "docs"
    },
    "dist": {
        "shasum": "a9692ad9134086becc56045e626b84c5af8aee85",
        "tarball": "https://registry.npmjs.org/vivagraphjs/-/vivagraphjs-0.8.2.tgz"
    },
    "gitHead": "12ccef6ddd50743af96c5ab8da9e12eb8d2b5db8",
    "homepage": "https://github.com/anvaka/VivaGraphJS#readme",
    "keywords": [
        "graph"
    ],
    "license": "BSD-3-Clause",
    "main": "src/viva",
    "maintainers": [
        {
            "name": "anvaka"
        }
    ],
    "name": "vivagraphjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/anvaka/VivaGraphJS.git"
    },
    "scripts": {
        "release": "gulp release",
        "start": "gulp",
        "test": "tap test/*.js"
    },
    "version": "0.8.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
