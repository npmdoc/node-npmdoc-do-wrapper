# npmdoc-do-wrapper

#### api documentation for  [do-wrapper (v3.11.1)](https://github.com/matt-major/do-wrapper)  [![npm package](https://img.shields.io/npm/v/npmdoc-do-wrapper.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-do-wrapper) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-do-wrapper.svg)](https://travis-ci.org/npmdoc/node-npmdoc-do-wrapper)

#### Node.js Wrapper for Digital Ocean API v2

[![NPM](https://nodei.co/npm/do-wrapper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/do-wrapper)

- [https://npmdoc.github.io/node-npmdoc-do-wrapper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-do-wrapper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-do-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-do-wrapper/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-do-wrapper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-do-wrapper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Major"
    },
    "bugs": {
        "url": "https://github.com/matt-major/do-wrapper/issues"
    },
    "dependencies": {
        "request": "2.74.0"
    },
    "description": "Node.js Wrapper for Digital Ocean API v2",
    "devDependencies": {
        "chai": "^3.5.0",
        "gulp": "3.9.1",
        "gulp-babel": "5.2.1",
        "gulp-uglify": "1.5.1",
        "husky": "0.10.2",
        "jsdoc": "3.4.0",
        "jsdox": "^0.4.9",
        "jshint": "2.8.0",
        "mocha": "^2.4.5",
        "should": "^8.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "bedaf217230c8f9ba7eecc4e68c23ba284c762f2",
        "tarball": "https://registry.npmjs.org/do-wrapper/-/do-wrapper-3.11.1.tgz"
    },
    "gitHead": "db1db00462e9cb0115a1ce894122dfff7895b154",
    "homepage": "https://github.com/matt-major/do-wrapper",
    "keywords": [
        "digital ocean",
        "digitalocean",
        "droplet",
        "cloud",
        "wrapper",
        "api",
        "babel",
        "es6"
    ],
    "license": "MIT",
    "main": "./dist/do-wrapper.js",
    "maintainers": [
        {
            "name": "matt-major"
        }
    ],
    "name": "do-wrapper",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/matt-major/do-wrapper.git"
    },
    "scripts": {
        "build": "gulp compile && npm run doc",
        "doc": "jsdoc src/*.js -d docs/",
        "precommit": "npm t",
        "test": "jshint src/*.js && ./node_modules/mocha/bin/mocha"
    },
    "types": "./types/do-wrapper.d.ts",
    "version": "3.11.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
