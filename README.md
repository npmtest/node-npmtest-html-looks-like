# npmtest-html-looks-like

#### basic test-coverage for  [html-looks-like (v1.0.2)](https://github.com/staltz/html-looks-like#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-html-looks-like.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html-looks-like) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html-looks-like.svg)](https://travis-ci.org/npmtest/node-npmtest-html-looks-like)

#### Assert that an HTML string looks approximately the same as another HTML

[![NPM](https://nodei.co/npm/html-looks-like.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html-looks-like)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html-looks-like/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-looks-like/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html-looks-like/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html-looks-like/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html-looks-like/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html-looks-like/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html-looks-like/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html-looks-like/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html-looks-like/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-looks-like/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html-looks-like/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html-looks-like/build/test-report.html](https://npmtest.github.io/node-npmtest-html-looks-like/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html-looks-like/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html-looks-like/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html-looks-like/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html-looks-like/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-looks-like/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-looks-like/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html-looks-like/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html-looks-like/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andre Staltz"
    },
    "bugs": {
        "url": "https://github.com/staltz/html-looks-like/issues"
    },
    "dependencies": {
        "@types/jsdom": "^2.0.30",
        "@types/mocha": "^2.2.39",
        "diff-dom": "^2.1.0",
        "domwalk": "^1.1.0",
        "jsdom": "^9.11.0",
        "lodash.sortby": "^4.7.0",
        "mocha": "^3.2.0",
        "ts-node": "^2.1.0",
        "tslint": "^4.5.1",
        "typescript": "^2.2.1"
    },
    "description": "Assert that an HTML string looks approximately the same as another HTML",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "dc636c8af62fd45e539dc398a8ef7d01caea7e05",
        "tarball": "https://registry.npmjs.org/html-looks-like/-/html-looks-like-1.0.2.tgz"
    },
    "gitHead": "15d46818d856494e6955d0b0924697980b1ba531",
    "homepage": "https://github.com/staltz/html-looks-like#readme",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "cycle"
        },
        {
            "name": "staltz"
        }
    ],
    "name": "html-looks-like",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/staltz/html-looks-like.git"
    },
    "scripts": {
        "compile": "tsc",
        "lint": "tslint -c tslint.json src/**/*.ts src/*.ts",
        "mocha": "mocha test/*.ts test/**/*.ts --require ts-node/register",
        "test": "npm run lint && npm run mocha"
    },
    "typings": "lib/index.d.ts",
    "version": "1.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
