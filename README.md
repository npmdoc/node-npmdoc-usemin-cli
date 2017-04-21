# npmdoc-usemin-cli

#### api documentation for  [usemin-cli (v0.5.1)](https://github.com/nelsyeung/usemin-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-usemin-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-usemin-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-usemin-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-usemin-cli)

#### Replaces references to non-optimized scripts or stylesheets into a set of HTML files (or any templates/views).

[![NPM](https://nodei.co/npm/usemin-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/usemin-cli)

- [https://npmdoc.github.io/node-npmdoc-usemin-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-usemin-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-usemin-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-usemin-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-usemin-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-usemin-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "usemin-cli",
    "version": "0.5.1",
    "description": "Replaces references to non-optimized scripts or stylesheets into a set of HTML files (or any templates/views).",
    "bin": {
        "usemin": "./bin/usemin"
    },
    "scripts": {
        "test": "eslint . && mocha"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/nelsyeung/usemin-cli.git"
    },
    "keywords": [
        "usemin",
        "html",
        "css",
        "optimize"
    ],
    "author": "Nelson Yeung (http://nelsyeung.com)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/nelsyeung/usemin-cli/issues"
    },
    "homepage": "https://github.com/nelsyeung/usemin-cli#readme",
    "dependencies": {
        "usemin": "^0.4.3",
        "yargs": "^6.6.0"
    },
    "eslintConfig": {
        "env": {
            "node": true,
            "mocha": true
        },
        "extends": "eslint:recommended",
        "rules": {
            "indent": [
                "error",
                "tab"
            ],
            "linebreak-style": [
                "error",
                "unix"
            ],
            "quotes": [
                "error",
                "single"
            ],
            "semi": [
                "error",
                "always"
            ],
            "comma-dangle": [
                "error",
                "always"
            ],
            "brace-style": [
                "error",
                "1tbs"
            ]
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
