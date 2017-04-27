# npmtest-memory-fs

#### basic test coverage for  [memory-fs (v0.4.1)](https://github.com/webpack/memory-fs)  [![npm package](https://img.shields.io/npm/v/npmtest-memory-fs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-memory-fs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-memory-fs.svg)](https://travis-ci.org/npmtest/node-npmtest-memory-fs)

#### A simple in-memory filesystem. Holds data in a javascript object.

[![NPM](https://nodei.co/npm/memory-fs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/memory-fs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-memory-fs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-memory-fs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-memory-fs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-memory-fs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-memory-fs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-memory-fs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-memory-fs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-memory-fs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-memory-fs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-memory-fs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-memory-fs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-memory-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-memory-fs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-memory-fs/build/test-report.html](https://npmtest.github.io/node-npmtest-memory-fs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-memory-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-memory-fs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-memory-fs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-memory-fs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-memory-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-memory-fs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-memory-fs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-memory-fs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "bugs": {
        "url": "https://github.com/webpack/memory-fs/issues"
    },
    "dependencies": {
        "errno": "^0.1.3",
        "readable-stream": "^2.0.1"
    },
    "description": "A simple in-memory filesystem. Holds data in a javascript object.",
    "devDependencies": {
        "bl": "^1.0.0",
        "codecov.io": "^0.1.4",
        "coveralls": "^2.11.2",
        "istanbul": "^0.2.13",
        "mocha": "^1.20.1",
        "should": "^4.0.4"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "3a9a20b8462523e447cfbc7e8bb80ed667bfc552",
        "tarball": "https://registry.npmjs.org/memory-fs/-/memory-fs-0.4.1.tgz"
    },
    "files": [
        "lib/"
    ],
    "gitHead": "1b3c3572b47caa8b6d49b938456cfe180834f377",
    "homepage": "https://github.com/webpack/memory-fs",
    "keywords": [
        "fs",
        "memory"
    ],
    "license": "MIT",
    "main": "lib/MemoryFileSystem.js",
    "maintainers": [
        {
            "name": "sokra"
        }
    ],
    "name": "memory-fs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/webpack/memory-fs.git"
    },
    "scripts": {
        "cover": "istanbul cover node_modules/mocha/bin/_mocha",
        "test": "mocha",
        "travis": "npm run cover -- --report lcovonly"
    },
    "version": "0.4.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
