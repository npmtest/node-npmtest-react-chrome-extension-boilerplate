# npmtest-react-chrome-extension-boilerplate

#### basic test coverage for  react-chrome-extension-boilerplate (v0.9.0)  [![npm package](https://img.shields.io/npm/v/npmtest-react-chrome-extension-boilerplate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-chrome-extension-boilerplate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-chrome-extension-boilerplate.svg)](https://travis-ci.org/npmtest/node-npmtest-react-chrome-extension-boilerplate)

#### Boilerplate for Chrome extension React.js project

[![NPM](https://nodei.co/npm/react-chrome-extension-boilerplate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-chrome-extension-boilerplate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-chrome-extension-boilerplate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-chrome-extension-boilerplate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/test-report.html](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-chrome-extension-boilerplate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-chrome-extension-boilerplate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-chrome-extension-boilerplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-chrome-extension-boilerplate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-chrome-extension-boilerplate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-chrome-extension-boilerplate",
    "version": "0.9.0",
    "description": "Boilerplate for Chrome extension React.js project",
    "scripts": {
        "dev": "node scripts/dev",
        "build": "node scripts/build",
        "compress": "node scripts/compress",
        "compress-keygen": "crx keygen",
        "clean": "rimraf build/ dev/ *.zip *.crx",
        "lint": "eslint app chrome test scripts",
        "test-e2e": "cross-env NODE_ENV=test mocha test/e2e",
        "test": "cross-env NODE_ENV=test mocha -r ./test/setup-app test/app"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/jhen0409/react-chrome-extension-boilerplate.git"
    },
    "keywords": [
        "chrome",
        "extension",
        "react",
        "redux",
        "hot reload",
        "webpack",
        "boilerplate"
    ],
    "author": "Jhen <developer@jhen.me>",
    "license": "MIT",
    "devDependencies": {
        "babel-core": "^6.3.15",
        "babel-eslint": "^6.0.0",
        "babel-loader": "^6.2.0",
        "babel-plugin-add-module-exports": "^0.1.1",
        "babel-plugin-transform-decorators-legacy": "^1.2.0",
        "babel-plugin-transform-runtime": "^6.5.2",
        "babel-plugin-webpack-loaders": "^0.4.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-react-hmre": "^1.0.0",
        "babel-preset-stage-0": "^6.3.13",
        "babel-runtime": "^6.3.19",
        "chai": "^3.2.0",
        "chromedriver": "^2.19.0",
        "co-mocha": "^1.1.2",
        "cross-env": "^1.0.7",
        "crx": "^3.0.3",
        "css-loader": "^0.23.1",
        "eslint": "^2.5.3",
        "eslint-config-airbnb": "^8.0.0",
        "eslint-plugin-import": "^1.6.1",
        "eslint-plugin-jsx-a11y": "^1.0.4",
        "eslint-plugin-react": "^5.0.1",
        "extract-text-webpack-plugin": "^1.0.1",
        "jade": "^1.11.0",
        "jsdom": "^8.2.0",
        "minimist": "^1.2.0",
        "mocha": "^2.4.5",
        "postcss-loader": "^0.9.1",
        "react-addons-test-utils": "^15.0.2",
        "rimraf": "^2.4.3",
        "selenium-webdriver": "^2.47.0",
        "shelljs": "^0.7.0",
        "sinon": "^1.17.1",
        "style-loader": "^0.13.1",
        "webpack": "^1.13.0",
        "webpack-httpolyglot-server": "^0.2.0"
    },
    "dependencies": {
        "bluebird": "^3.3.4",
        "classnames": "^2.1.3",
        "react": "^15.0.2",
        "react-dock": "^0.2.3",
        "react-dom": "^15.0.2",
        "react-redux": "^4.3.0",
        "redux": "^3.2.1",
        "redux-thunk": "^2.0.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
