# npmdoc-generator-generator

#### api documentation for  generator-generator (v3.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-generator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-generator)

#### Generate a Yeoman generator

[![NPM](https://nodei.co/npm/generator-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-generator)

- [https://npmdoc.github.io/node-npmdoc-generator-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-generator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-generator-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-generator-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-generator",
    "version": "3.1.0",
    "description": "Generate a Yeoman generator",
    "author": "Yeoman team",
    "files": [
        "app",
        "subgenerator"
    ],
    "keywords": [
        "yeoman-generator",
        "yeoman",
        "generator",
        "inception",
        "init",
        "create",
        "boilerplate"
    ],
    "repository": "yeoman/generator-generator",
    "scripts": {
        "test": "jest",
        "pretest": "eslint . --fix",
        "prepublish": "nsp check"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "deep-extend": "^0.4.1",
        "generator-node": "^2.1.0",
        "inquirer-npm-name": "^2.0.0",
        "lodash": "^4.17.2",
        "mkdirp": "^0.5.1",
        "superb": "^1.3.0",
        "yeoman-generator": "^1.0.0",
        "yosay": "^2.0.0"
    },
    "devDependencies": {
        "coveralls": "^2.12.0",
        "eslint": "^3.18.0",
        "eslint-config-xo-space": "^0.16.0",
        "jest": "^19.0.2",
        "jest-cli": "^19.0.2",
        "nsp": "^2.6.3",
        "yeoman-assert": "^3.0.0",
        "yeoman-test": "^1.6.0"
    },
    "eslintConfig": {
        "extends": "xo-space",
        "env": {
            "jest": true,
            "node": true
        }
    },
    "jest": {
        "testEnvironment": "node",
        "testPathIgnorePatterns": [
            "templates"
        ]
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
