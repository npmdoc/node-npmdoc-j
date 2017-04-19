# npmdoc-j

#### api documentation for  [j (v0.4.5)](https://github.com/SheetJS/j#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-j.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-j) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-j.svg)](https://travis-ci.org/npmdoc/node-npmdoc-j)

#### CLI tool for working with spreadsheet files

[![NPM](https://nodei.co/npm/j.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/j)

- [https://npmdoc.github.io/node-npmdoc-j/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-j/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-j/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-j/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-j/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-j/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "sheetjs"
    },
    "bin": {
        "j": "./bin/j.njs"
    },
    "bugs": {
        "url": "https://github.com/SheetJS/j/issues"
    },
    "config": {
        "blanket": {
            "pattern": "[./j.js,./node_modules/xlsx/xlsx.js]"
        }
    },
    "dependencies": {
        "commander": "",
        "concat-stream": "",
        "exit-on-epipe": "",
        "harb": "~0.1.1",
        "xlsjs": "~0.7.6",
        "xlsx": "~0.9.1"
    },
    "description": "CLI tool for working with spreadsheet files",
    "devDependencies": {
        "mocha": ""
    },
    "directories": {},
    "dist": {
        "shasum": "02cf29f1ddbe54e527263d0754d6e8d217a6064e",
        "tarball": "https://registry.npmjs.org/j/-/j-0.4.5.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "files": [
        "LICENSE",
        "README.md",
        "bin",
        "j.js"
    ],
    "gitHead": "0ba2eadb63fba85042ea74bb6214744dda4bf4c3",
    "homepage": "https://github.com/SheetJS/j#readme",
    "keywords": [
        "excel",
        "xls",
        "xlsx",
        "xlsm",
        "xlsb",
        "ods",
        "dif",
        "csv",
        "sylk",
        "prn",
        "ods",
        "dbf",
        "office",
        "spreadsheet"
    ],
    "license": "Apache-2.0",
    "main": "./j",
    "maintainers": [
        {
            "name": "sheetjs"
        }
    ],
    "name": "j",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/SheetJS/j.git"
    },
    "scripts": {
        "test": "make mocha"
    },
    "version": "0.4.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
