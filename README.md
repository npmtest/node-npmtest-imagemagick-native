# npmtest-imagemagick-native

#### basic test coverage for  imagemagick-native (v1.9.3)  [![npm package](https://img.shields.io/npm/v/npmtest-imagemagick-native.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-imagemagick-native) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-imagemagick-native.svg)](https://travis-ci.org/npmtest/node-npmtest-imagemagick-native)

#### ImageMagick's Magick++ bindings for NodeJS

[![NPM](https://nodei.co/npm/imagemagick-native.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imagemagick-native)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-imagemagick-native/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-imagemagick-native/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-imagemagick-native/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-imagemagick-native/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-imagemagick-native/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-imagemagick-native/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-imagemagick-native/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-imagemagick-native/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-imagemagick-native/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-imagemagick-native/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-imagemagick-native/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-imagemagick-native/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-imagemagick-native/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-imagemagick-native/build/test-report.html](https://npmtest.github.io/node-npmtest-imagemagick-native/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-imagemagick-native/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-imagemagick-native/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-imagemagick-native/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imagemagick-native/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imagemagick-native/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imagemagick-native/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-imagemagick-native/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-imagemagick-native/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "imagemagick-native",
    "description": "ImageMagick's Magick++ bindings for NodeJS",
    "keywords": [
        "imagemagick",
        "magick++",
        "resize",
        "convert"
    ],
    "version": "1.9.3",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git://github.com/mash/node-imagemagick-native.git"
    },
    "author": "Masakazu Ohtsuka <o.masakazu@gmail.com> (http://maaash.jp/)",
    "contributors": [],
    "main": "./index.js",
    "scripts": {
        "test": "tap test/test.js test/test.async.js test/test.streams.js test/test.trim.js test/test.background.js",
        "install": "node-gyp rebuild"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "dependencies": {
        "nan": "2.x"
    },
    "devDependencies": {
        "tap": "*",
        "grunt": "~0.4",
        "grunt-release": "~0.7",
        "grunt-contrib-clean": "~0.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
