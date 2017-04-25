# npmtest-config

#### basic test coverage for  [config (v1.25.1)](http://lorenwest.github.com/node-config)  [![npm package](https://img.shields.io/npm/v/npmtest-config.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-config) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-config.svg)](https://travis-ci.org/npmtest/node-npmtest-config)

#### Configuration control for production node deployments

[![NPM](https://nodei.co/npm/config.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/config)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-config/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-config/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-config/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-config/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-config/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-config/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-config/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-config/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-config/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-config/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-config/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-config/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-config/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-config/build/test-report.html](https://npmtest.github.io/node-npmtest-config/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-config/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-config/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-config/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-config/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-config/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-config/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-config/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-config/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Loren West"
    },
    "bugs": {
        "url": "https://github.com/lorenwest/node-config/issues"
    },
    "dependencies": {
        "json5": "0.4.0"
    },
    "description": "Configuration control for production node deployments",
    "devDependencies": {
        "coffee-script": ">=1.7.0",
        "cson": "^3.0.1",
        "hjson": "^1.2.0",
        "js-yaml": "^3.2.2",
        "properties": "~1.2.1",
        "toml": "^2.0.6",
        "underscore": "^1.8.3",
        "vows": ">=0.8.1",
        "x2js": "^2.0.1"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "72ac51cde81e2c77c6b3b66d0130dae527a19c92",
        "tarball": "https://registry.npmjs.org/config/-/config-1.25.1.tgz"
    },
    "engines": {
        "node": ">0.4.x"
    },
    "gitHead": "c226283619b2f759ff236d5e1f65055a3c39ba54",
    "homepage": "http://lorenwest.github.com/node-config",
    "keywords": [
        "conf",
        "config",
        "configuration",
        "node-config",
        "config-node",
        "env",
        "environment"
    ],
    "license": "MIT",
    "main": "./lib/config.js",
    "maintainers": [
        {
            "name": "lorenwest"
        },
        {
            "name": "markstos"
        }
    ],
    "name": "config",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/lorenwest/node-config.git"
    },
    "scripts": {
        "test": "./node_modules/vows/bin/vows test/*.js --spec"
    },
    "version": "1.25.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
