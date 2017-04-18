# npmtest-telegraf

#### test coverage for  [telegraf (v3.6.7)](https://github.com/telegraf/telegraf#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-telegraf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-telegraf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-telegraf.svg)](https://travis-ci.org/npmtest/node-npmtest-telegraf)

#### 📡 Modern Telegram bot framework

[![NPM](https://nodei.co/npm/telegraf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/telegraf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-telegraf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-telegraf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-telegraf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-telegraf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-telegraf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-telegraf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-telegraf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-telegraf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-telegraf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-telegraf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-telegraf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-telegraf/build/test-report.html](https://npmtest.github.io/node-npmtest-telegraf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-telegraf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-telegraf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-telegraf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-telegraf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-telegraf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-telegraf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-telegraf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-telegraf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vitaly Domnikov"
    },
    "bugs": {
        "url": "https://github.com/telegraf/telegraf/issues"
    },
    "dependencies": {
        "debug": "^2.6.0",
        "node-fetch": "^1.6.3",
        "sandwich-stream": "^1.0.0"
    },
    "description": "📡 Modern Telegram bot framework",
    "devDependencies": {
        "ava": "^0.18.1",
        "eslint": "^3.9.1",
        "eslint-config-standard": "^7.0.0",
        "eslint-plugin-ava": "^4.0.0",
        "eslint-plugin-promise": "^3.3.1",
        "eslint-plugin-standard": "^2.0.1",
        "husky": "^0.13.1",
        "should": "^11.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4bc1430639f5f897c9306932480f441b17eb91fc",
        "tarball": "https://registry.npmjs.org/telegraf/-/telegraf-3.6.7.tgz"
    },
    "docpress": {
        "css": "docs/docs.css",
        "github": "telegraf/telegraf"
    },
    "engines": {
        "node": ">=6.2.0"
    },
    "files": [
        "docs",
        "lib"
    ],
    "gitHead": "5f235234cb5c75da7b1eaeb80a63b0991f5c2940",
    "homepage": "https://github.com/telegraf/telegraf#readme",
    "keywords": [
        "telegraf",
        "telegram",
        "telegram bot api",
        "bot",
        "botapi",
        "bot framework"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "dotcypress"
        }
    ],
    "name": "telegraf",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/telegraf/telegraf.git"
    },
    "scripts": {
        "prepush": "npm test",
        "test": "eslint . && ava test --timeout=5s"
    },
    "version": "3.6.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
