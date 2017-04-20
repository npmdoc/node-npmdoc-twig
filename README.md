# npmdoc-twig

#### api documentation for  [twig (v1.10.4)](https://github.com/twigjs/twig.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-twig.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-twig) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-twig.svg)](https://travis-ci.org/npmdoc/node-npmdoc-twig)

#### JS port of the Twig templating language.

[![NPM](https://nodei.co/npm/twig.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/twig)

- [https://npmdoc.github.io/node-npmdoc-twig/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-twig/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-twig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-twig/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-twig/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-twig/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "John Roepke <john@justjohn.us> (http://john.sh/)",
    "name": "twig",
    "description": "JS port of the Twig templating language.",
    "version": "1.10.4",
    "homepage": "https://github.com/twigjs/twig.js",
    "licenses": [
        {
            "type": "BSD-2-Clause",
            "url": "https://raw.github.com/twigjs/twig.js/master/LICENSE"
        }
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/twigjs/twig.js.git"
    },
    "main": "twig.js",
    "engines": {
        "node": "*"
    },
    "bin": {
        "twigjs": "./bin/twigjs"
    },
    "scripts": {
        "preversion": "npm test && git diff --exit-code --quiet",
        "postversion": "git push origin master && git push origin master --tags",
        "test": "npm run build && mocha -r should",
        "build-node": "webpack",
        "build-browser": "WEBPACK_ENV=browser webpack",
        "build": "npm run build-node && npm run build-browser"
    },
    "dependencies": {
        "minimatch": "3.0.x",
        "locutus": "^2.0.5",
        "walk": "2.3.x"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "3.1.x",
        "should": "11.1.x",
        "sinon": "^1.17.6",
        "sinon-chai": "^2.8.0",
        "tokenizer": "1.1.x",
        "webpack": "^1.13.3"
    },
    "browser": {
        "fs": false
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
