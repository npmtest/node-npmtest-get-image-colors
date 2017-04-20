# npmtest-get-image-colors

#### basic test coverage for  get-image-colors (v1.8.1)  [![npm package](https://img.shields.io/npm/v/npmtest-get-image-colors.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-get-image-colors) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-get-image-colors.svg)](https://travis-ci.org/npmtest/node-npmtest-get-image-colors)

#### Extract colors from images. Supports GIF, JPG, PNG, and even SVG!

[![NPM](https://nodei.co/npm/get-image-colors.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/get-image-colors)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-get-image-colors/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-get-image-colors/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-get-image-colors/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-get-image-colors/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-get-image-colors/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-get-image-colors/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-get-image-colors/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-get-image-colors/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-get-image-colors/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-get-image-colors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-get-image-colors/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-get-image-colors/build/test-report.html](https://npmtest.github.io/node-npmtest-get-image-colors/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-get-image-colors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-get-image-colors/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-get-image-colors/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-get-image-colors/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-get-image-colors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-get-image-colors/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-get-image-colors/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-get-image-colors/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "get-image-colors",
    "version": "1.8.1",
    "description": "Extract colors from images. Supports GIF, JPG, PNG, and even SVG!",
    "main": "index.js",
    "scripts": {
        "test": "mocha && standard && standard-markdown",
        "lint": "standard"
    },
    "repository": "https://github.com/zeke/get-image-colors",
    "keywords": [
        "color",
        "palette",
        "svg",
        "gif",
        "png",
        "jpg",
        "canvas",
        "pixels",
        "rgb",
        "rgba"
    ],
    "author": "zeke",
    "license": "MIT",
    "devDependencies": {
        "mocha": "^2.3.3",
        "standard": "^8.6.0",
        "standard-markdown": "^2.3.0"
    },
    "dependencies": {
        "pify": "^2.3.0",
        "chroma-js": "^1.1.1",
        "get-pixels": "^3.3.0",
        "get-rgba-palette": "^2.0.0",
        "get-svg-colors": "^1.3.0"
    },
    "standard": {
        "env": {
            "mocha": true
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
