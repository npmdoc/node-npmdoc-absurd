# npmdoc-absurd

#### api documentation for  [absurd (v0.3.8)](http://absurdjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-absurd.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-absurd) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-absurd.svg)](https://travis-ci.org/npmdoc/node-npmdoc-absurd)

#### JavaScript library with superpowers - http://absurdjs.com/

[![NPM](https://nodei.co/npm/absurd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/absurd)

- [https://npmdoc.github.io/node-npmdoc-absurd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-absurd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-absurd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-absurd/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-absurd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-absurd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "absurd",
    "version": "0.3.8",
    "homepage": "http://absurdjs.com/",
    "description": "JavaScript library with superpowers - http://absurdjs.com/",
    "main": "./index.js",
    "browser": "./client-side/build/absurd.min.js",
    "author": {
        "name": "Krasimir Tsonev",
        "url": "http://krasimirtsonev.com"
    },
    "license": "MIT",
    "dependencies": {
        "optimist": "0.6.1",
        "colors": "0.6.2",
        "gaze": "1.1.0",
        "glob": "5.0.15",
        "js-yaml": "3.0.1",
        "js-beautify": "1.4.2"
    },
    "devDependencies": {
        "grunt": "0.4.2",
        "grunt-contrib-concat": "0.3.0",
        "grunt-contrib-watch": "0.5.3",
        "grunt-contrib-uglify": "0.3.2",
        "jasmine-node": "1.13.1"
    },
    "keywords": [
        "css",
        "preprocessor"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/krasimir/absurd.git"
    },
    "bin": {
        "absurd": "./index.js"
    },
    "scripts": {
        "test": "./node_modules/jasmine-node/bin/jasmine-node ./tests"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
