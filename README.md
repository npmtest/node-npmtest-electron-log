# npmtest-electron-log

#### basic test coverage for  [electron-log (v2.2.2)](https://github.com/megahertz/electron-log#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-log.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-log) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-log.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-log)

#### Just a very simple logging module for your Electron application

[![NPM](https://nodei.co/npm/electron-log.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-log)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-log/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-log/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-log/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-log/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-log/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-log/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-log/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-log/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-log/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-log/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-log/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-log/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-log/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-log/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-log/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-log/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-log/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-log/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-log/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-log/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-log/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexey Prokhorov"
    },
    "bugs": {
        "url": "https://github.com/megahertz/electron-log/issues"
    },
    "dependencies": {},
    "description": "Just a very simple logging module for your Electron application",
    "devDependencies": {
        "chai": "*",
        "jscs": "*",
        "jshint": "*",
        "jshint-reporter-jscs": "*",
        "mocha": "*",
        "rewire": "*",
        "tslint": "*",
        "typescript": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "cea73ed05fecf7614955c503d15bc78e92338f38",
        "tarball": "https://registry.npmjs.org/electron-log/-/electron-log-2.2.2.tgz"
    },
    "files": [
        "index.js",
        "main.js",
        "renderer.js",
        "lib/**/*.js",
        "!lib/**/*.spec.js",
        "electron-log.d.ts"
    ],
    "gitHead": "7129245bbb254d3861e36f829441748be1e51dec",
    "homepage": "https://github.com/megahertz/electron-log#readme",
    "keywords": [
        "electron",
        "atom",
        "log",
        "logger",
        "logging",
        "windows",
        "mac",
        "osx",
        "linux",
        "desktop"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "megahertz"
        }
    ],
    "name": "electron-log",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/megahertz/electron-log.git"
    },
    "scripts": {
        "jscs": "jscs .",
        "jshint": "jshint --exclude ./node_modules,./test-projects . --verbose",
        "mocha": "mocha index.spec.js lib/{,**/}{,**/}*.spec.js",
        "test": "npm run jshint && npm run jscs && npm run tslint && npm run mocha && npm run test-projects",
        "test-projects": "mocha test-projects/**/*.spec.js",
        "test-projects-install": "node test-projects/install.js",
        "tslint": "tslint electron-log.d.ts"
    },
    "typings": "./electron-log.d.ts",
    "version": "2.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
