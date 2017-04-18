# npmtest-nwb

#### test coverage for  [nwb (v0.15.6)](https://github.com/insin/nwb#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nwb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nwb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nwb.svg)](https://travis-ci.org/npmtest/node-npmtest-nwb)

#### A toolkit for React, Preact & Inferno apps, React libraries and other npm modules for the web, with no configuration (until you need it)

[![NPM](https://nodei.co/npm/nwb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nwb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nwb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nwb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nwb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nwb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nwb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nwb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nwb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nwb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nwb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nwb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nwb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nwb/build/test-report.html](https://npmtest.github.io/node-npmtest-nwb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nwb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nwb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nwb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nwb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nwb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nwb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nwb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nwb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonny Buchanan"
    },
    "babel": {
        "presets": [
            [
                "env",
                {
                    "loose": true,
                    "targets": {
                        "node": 4
                    }
                }
            ],
            "stage-3"
        ],
        "plugins": [
            "add-module-exports"
        ],
        "env": {
            "test": {
                "plugins": [
                    [
                        "istanbul",
                        {
                            "include": "src"
                        }
                    ]
                ]
            }
        }
    },
    "bin": {
        "inferno": "./lib/bin/inferno.js",
        "nwb": "./lib/bin/nwb.js",
        "preact": "./lib/bin/preact.js",
        "react": "./lib/bin/react.js"
    },
    "bugs": {
        "url": "https://github.com/insin/nwb/issues"
    },
    "dependencies": {
        "@insin/extract-text-webpack-plugin": "2.0.0-beta.5.1b711fa5",
        "@insin/npm-install-webpack-plugin": "4.0.4-3ee2c673",
        "autoprefixer": "6.7.0",
        "babel-cli": "6.22.2",
        "babel-core": "6.22.1",
        "babel-loader": "6.2.10",
        "babel-plugin-add-module-exports": "0.2.1",
        "babel-plugin-inferno": "1.7.0",
        "babel-plugin-istanbul": "3.1.2",
        "babel-plugin-lodash": "3.2.11",
        "babel-plugin-react-transform": "2.0.2",
        "babel-plugin-syntax-dynamic-import": "6.18.0",
        "babel-plugin-syntax-jsx": "6.18.0",
        "babel-plugin-transform-decorators-legacy": "1.3.4",
        "babel-plugin-transform-react-jsx": "6.22.0",
        "babel-plugin-transform-react-jsx-self": "6.22.0",
        "babel-plugin-transform-react-jsx-source": "6.22.0",
        "babel-plugin-transform-react-remove-prop-types": "0.2.11",
        "babel-plugin-transform-runtime": "6.22.0",
        "babel-polyfill": "6.22.0",
        "babel-preset-es2015": "6.22.0",
        "babel-preset-es2016": "6.22.0",
        "babel-preset-react": "6.22.0",
        "babel-preset-stage-0": "6.22.0",
        "babel-preset-stage-1": "6.22.0",
        "babel-preset-stage-2": "6.22.0",
        "babel-preset-stage-3": "6.22.0",
        "babel-runtime": "6.22.0",
        "case-sensitive-paths-webpack-plugin": "1.1.4",
        "chalk": "1.1.3",
        "connect-history-api-fallback": "1.3.0",
        "copy-template-dir": "1.3.0",
        "copy-webpack-plugin": "4.0.1",
        "cross-spawn": "5.0.1",
        "css-loader": "0.26.1",
        "debug": "2.6.0",
        "detect-port": "1.1.0",
        "diff": "3.2.0",
        "eventsource-polyfill": "0.9.6",
        "expect": "1.20.2",
        "express": "4.14.0",
        "figures": "2.0.0",
        "file-loader": "0.9.0",
        "filesize": "3.4.3",
        "glob": "7.1.1",
        "gzip-size": "3.0.0",
        "html-webpack-plugin": "2.26.0",
        "inquirer": "3.0.1",
        "karma": "1.4.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-coverage": "1.1.1",
        "karma-mocha": "1.3.0",
        "karma-mocha-reporter": "2.2.2",
        "karma-phantomjs-launcher": "1.0.2",
        "karma-sourcemap-loader": "0.3.7",
        "karma-webpack": "2.0.1",
        "minimist": "1.2.0",
        "mocha": "3.2.0",
        "object-assign": "4.1.1",
        "ora": "1.1.0",
        "phantomjs-prebuilt": "2.1.14",
        "postcss-loader": "1.2.2",
        "promise": "7.1.1",
        "react-transform-catch-errors": "1.0.2",
        "react-transform-hmr": "1.0.4",
        "redbox-noreact": "1.1.0",
        "resolve": "1.2.0",
        "rimraf": "2.5.4",
        "run-series": "1.1.4",
        "semver": "5.3.0",
        "style-loader": "0.13.1",
        "url-loader": "0.5.7",
        "webpack": "2.2.0",
        "webpack-dev-middleware": "1.9.0",
        "webpack-hot-middleware": "2.15.0",
        "webpack-md5-hash": "0.0.5",
        "webpack-merge": "2.4.0",
        "whatwg-fetch": "2.0.2"
    },
    "description": "A toolkit for React, Preact & Inferno apps, React libraries and other npm modules for the web, with no configuration (until you need it)",
    "devDependencies": {
        "babel-preset-env": "1.1.8",
        "cross-env": "3.1.4",
        "eslint-config-jonnybuchanan": "4.8.0",
        "eventsource": "0.2.1",
        "nyc": "10.1.2",
        "shelljs": "0.7.6",
        "temp": "0.8.3",
        "tree-kill": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1448bec35c91cb026e9c115eda85c1aa80e63a42",
        "tarball": "https://registry.npmjs.org/nwb/-/nwb-0.15.6.tgz"
    },
    "engines": {
        "node": ">=4.3.0"
    },
    "files": [
        "babel-presets",
        "docs",
        "lib",
        "templates",
        "express.js",
        "polyfills.js"
    ],
    "gitHead": "208a4b1c275fd6eb0302ae54958f5245c8f4ca0c",
    "homepage": "https://github.com/insin/nwb#readme",
    "keywords": [
        "development",
        "inferno",
        "preact",
        "react",
        "tooling"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "insin"
        }
    ],
    "name": "nwb",
    "nyc": {
        "instrument": false,
        "reporter": [
            "lcov",
            "text-summary"
        ],
        "require": [
            "babel-core/register"
        ],
        "sourceMap": false
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/insin/nwb.git"
    },
    "scripts": {
        "build": "npm run lint && rimraf lib && babel src --out-dir lib --quiet",
        "build:watch": "rimraf lib && babel src --watch --out-dir lib",
        "lint": "eslint *.js babel-presets src tests",
        "lint:fix": "npm run lint -- --fix",
        "test": "npm run build && cross-env NODE_ENV=test NWB_TEST=true mocha --compilers js:babel-core/register tests/*-test.js tests/commands/*-test.js",
        "test:coverage": "npm run build && cross-env NODE_ENV=test NWB_TEST=true nyc mocha tests/*-test.js tests/commands/*-test.js",
        "test:watch": "cross-env NODE_ENV=test NWB_TEST=true mocha --watch --compilers js:babel-core/register tests/*-test.js"
    },
    "version": "0.15.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
