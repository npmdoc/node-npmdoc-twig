# npmdoc-twig

#### basic api documentation for  [twig (v1.10.4)](https://github.com/twigjs/twig.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-twig.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-twig) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-twig.svg)](https://travis-ci.org/npmdoc/node-npmdoc-twig)

#### JS port of the Twig templating language.

[![NPM](https://nodei.co/npm/twig.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/twig)

- [https://npmdoc.github.io/node-npmdoc-twig/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-twig/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-twig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-twig/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-twig/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-twig/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John Roepke",
        "url": "http://john.sh/"
    },
    "bin": {
        "twigjs": "./bin/twigjs"
    },
    "browser": {
        "fs": false
    },
    "bugs": {
        "url": "https://github.com/twigjs/twig.js/issues"
    },
    "dependencies": {
        "locutus": "^2.0.5",
        "minimatch": "3.0.x",
        "walk": "2.3.x"
    },
    "description": "JS port of the Twig templating language.",
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "3.1.x",
        "should": "11.1.x",
        "sinon": "^1.17.6",
        "sinon-chai": "^2.8.0",
        "tokenizer": "1.1.x",
        "webpack": "^1.13.3"
    },
    "directories": {},
    "dist": {
        "shasum": "2ebad1e7e38c02b9cc772934822da1163d4ad4a1",
        "tarball": "https://registry.npmjs.org/twig/-/twig-1.10.4.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "56e2f9123f80037ecb97f96b0e07b98edf021982",
    "homepage": "https://github.com/twigjs/twig.js",
    "licenses": [
        {
            "type": "BSD-2-Clause",
            "url": "https://raw.github.com/twigjs/twig.js/master/LICENSE"
        }
    ],
    "main": "twig.js",
    "maintainers": [
        {
            "name": "dave-irvine"
        },
        {
            "name": "evgenius"
        },
        {
            "name": "justjohn"
        },
        {
            "name": "plepe"
        }
    ],
    "name": "twig",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/twigjs/twig.js.git"
    },
    "scripts": {
        "build": "npm run build-node && npm run build-browser",
        "build-browser": "WEBPACK_ENV=browser webpack",
        "build-node": "webpack",
        "postversion": "git push origin master && git push origin master --tags",
        "preversion": "npm test && git diff --exit-code --quiet",
        "test": "npm run build && mocha -r should"
    },
    "version": "1.10.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
