# npmdoc-styled-jsx

#### basic api documentation for  [styled-jsx (v0.5.7)](https://github.com/zeit/styled-jsx#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-styled-jsx.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-styled-jsx) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-styled-jsx.svg)](https://travis-ci.org/npmdoc/node-npmdoc-styled-jsx)

#### Full CSS support for JSX without compromises

[![NPM](https://nodei.co/npm/styled-jsx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/styled-jsx)

- [https://npmdoc.github.io/node-npmdoc-styled-jsx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-styled-jsx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-styled-jsx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-styled-jsx/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-styled-jsx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-styled-jsx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "ava": {
        "require": [
            "babel-register",
            "babel-polyfill"
        ]
    },
    "babel": {
        "presets": [
            "es2015",
            "stage-3",
            "react"
        ]
    },
    "bugs": {
        "url": "https://github.com/zeit/styled-jsx/issues"
    },
    "dependencies": {
        "babel-plugin-syntax-jsx": "6.18.0",
        "babel-traverse": "6.21.0",
        "babylon": "6.14.1",
        "convert-source-map": "1.3.0",
        "escape-string-regexp": "1.0.5",
        "object.entries": "1.0.4",
        "source-map": "0.5.6",
        "string-hash": "1.1.1"
    },
    "description": "Full CSS support for JSX without compromises",
    "devDependencies": {
        "ava": "0.17.0",
        "babel-cli": "6.18.0",
        "babel-core": "6.18.2",
        "babel-plugin-transform-runtime": "6.15.0",
        "babel-polyfill": "6.16.0",
        "babel-preset-babili": "0.0.10",
        "babel-preset-es2015": "6.16.0",
        "babel-preset-react": "6.16.0",
        "babel-preset-stage-3": "6.16.0",
        "babel-register": "6.18.0",
        "benchmark": "2.1.3",
        "gulp": "3.9.1",
        "gulp-babel": "6.1.2",
        "gulp-benchmark": "1.1.1",
        "human-size": "1.1.0",
        "mz": "2.6.0",
        "react": "15.4.1",
        "react-dom": "15.4.1",
        "xo": "0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "2cb02263ffa719b1435a864fdd6c62802ae86669",
        "tarball": "https://registry.npmjs.org/styled-jsx/-/styled-jsx-0.5.7.tgz"
    },
    "files": [
        "dist",
        "lib",
        "server.js",
        "babel.js",
        "style.js"
    ],
    "gitHead": "df90c37c929b5b9d17c5ef62d6fb71b723c830f4",
    "homepage": "https://github.com/zeit/styled-jsx#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "leo"
        },
        {
            "name": "nkzawa"
        },
        {
            "name": "rauchg"
        }
    ],
    "name": "styled-jsx",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/styled-jsx.git"
    },
    "scripts": {
        "dev": "gulp",
        "prepublish": "gulp transpile",
        "start": "node server.js",
        "test": "xo && ava"
    },
    "version": "0.5.7",
    "xo": {
        "esnext": true,
        "space": true,
        "semicolon": false,
        "ignores": [
            "lib/**",
            "test/fixtures/**"
        ],
        "envs": [
            "node",
            "browser"
        ],
        "rules": {
            "eqeqeq": [
                "error",
                "always",
                {
                    "null": "ignore"
                }
            ],
            "no-eq-null": 0,
            "import/no-unresolved": 0,
            "new-cap": 0
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
