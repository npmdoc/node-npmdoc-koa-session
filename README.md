# npmdoc-koa-session

#### basic api documentation for  [koa-session (v5.0.0)](https://github.com/koajs/session#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-koa-session.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-koa-session) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-koa-session.svg)](https://travis-ci.org/npmdoc/node-npmdoc-koa-session)

#### Koa cookie session middleware

[![NPM](https://nodei.co/npm/koa-session.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-session)

- [https://npmdoc.github.io/node-npmdoc-koa-session/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-session/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-session/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-koa-session/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-koa-session/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/koajs/session/issues"
    },
    "dependencies": {
        "crc": "^3.4.4",
        "debug": "^2.2.0",
        "uid-safe": "^2.1.3"
    },
    "description": "Koa cookie session middleware",
    "devDependencies": {
        "eslint": "3",
        "eslint-config-egg": "3",
        "istanbul": "0",
        "koa": "2",
        "mm": "^2.1.0",
        "mocha": "3",
        "should": "8",
        "supertest": "2"
    },
    "directories": {},
    "dist": {
        "shasum": "7f1f9392df6c8a792901ecfbfaa1f88a084c6d2a",
        "tarball": "https://registry.npmjs.org/koa-session/-/koa-session-5.0.0.tgz"
    },
    "engines": {
        "node": ">=7.6"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "11bbb66c73f6fb68f887183a4e860947c6a9b96f",
    "homepage": "https://github.com/koajs/session#readme",
    "keywords": [
        "koa",
        "middleware",
        "session",
        "cookie"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "aheckmann"
        },
        {
            "name": "coderhaoxin"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "eivifj"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "koa-session",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/session.git"
    },
    "scripts": {
        "lint": "eslint lib test index.js",
        "test": "npm run lint && NODE_ENV=test mocha --require should --reporter spec test/*.test.js",
        "test-cov": "NODE_ENV=test node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require should test/*.test.js",
        "test-travis": "npm run lint && NODE_ENV=test node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --require should test/*.test.js"
    },
    "version": "5.0.0",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": ">=7.6"
            },
            "pkgid": "koa-session@5.0.0"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": ">=7.6"
            },
            "pkgid": "koa-session@5.0.0"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
