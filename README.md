# npmtest-react-router

#### test coverage for  [react-router (v4.1.1)](https://github.com/reacttraining/react-router#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-router.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-router) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-router.svg)](https://travis-ci.org/npmtest/node-npmtest-react-router)

#### Declarative routing for React

[![NPM](https://nodei.co/npm/react-router.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-router)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-router/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-router/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-router/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-router/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-router/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-router/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-router/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-router/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-router/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-router/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-router/build/test-report.html](https://npmtest.github.io/node-npmtest-react-router/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-router/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-router/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-router/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-router/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-router/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-router/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Michael Jackson",
        "Ryan Florence"
    ],
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/reacttraining/react-router/issues"
    },
    "dependencies": {
        "history": "^4.6.0",
        "hoist-non-react-statics": "^1.2.0",
        "invariant": "^2.2.2",
        "loose-envify": "^1.3.1",
        "path-to-regexp": "^1.5.3",
        "prop-types": "^15.5.4",
        "warning": "^3.0.0"
    },
    "description": "Declarative routing for React",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-eslint": "^6.0.4",
        "babel-loader": "^6.2.10",
        "babel-plugin-dev-expression": "^0.2.1",
        "babel-plugin-transform-react-remove-prop-types": "^0.2.11",
        "babel-preset-es2015": "^6.14.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "eslint": "^3.19.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-react": "^6.10.3",
        "expect": "^1.20.1",
        "gzip-size": "^3.0.0",
        "in-publish": "^2.0.0",
        "karma": "^0.13.22",
        "karma-browserstack-launcher": "^1.0.1",
        "karma-chrome-launcher": "^1.0.1",
        "karma-mocha": "^1.0.1",
        "karma-mocha-reporter": "^2.0.4",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.5.3",
        "pretty-bytes": "^3.0.1",
        "react": "^15.4.2",
        "react-addons-test-utils": "^15.4.2",
        "react-dom": "^15.3.0",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d448f3b7c1b429a6fbb03395099949c606b1fe95",
        "tarball": "https://registry.npmjs.org/react-router/-/react-router-4.1.1.tgz"
    },
    "files": [
        "MemoryRouter.js",
        "Prompt.js",
        "Redirect.js",
        "Route.js",
        "Router.js",
        "StaticRouter.js",
        "Switch.js",
        "index.js",
        "matchPath.js",
        "withRouter.js",
        "es",
        "umd"
    ],
    "homepage": "https://github.com/reacttraining/react-router#readme",
    "keywords": [
        "react",
        "router",
        "route",
        "routing",
        "history",
        "link"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mjackson"
        },
        {
            "name": "ryanflorence"
        },
        {
            "name": "timdorr"
        }
    ],
    "module": "es/index.js",
    "name": "react-router",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reacttraining/react-router.git"
    },
    "scripts": {
        "build": "node ./tools/build.js",
        "clean": "git clean -fdX .",
        "lint": "eslint modules",
        "prepublish": "node ./tools/build.js",
        "test": "karma start --single-run",
        "watch": "babel ./modules -d . --ignore __tests__ --watch"
    },
    "version": "4.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
