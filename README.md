# npmtest-tunnel-ssh

#### basic test coverage for  tunnel-ssh (v4.1.2)  [![npm package](https://img.shields.io/npm/v/npmtest-tunnel-ssh.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tunnel-ssh) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tunnel-ssh.svg)](https://travis-ci.org/npmtest/node-npmtest-tunnel-ssh)

#### Easy extendable SSH tunnel

[![NPM](https://nodei.co/npm/tunnel-ssh.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tunnel-ssh)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tunnel-ssh/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tunnel-ssh/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tunnel-ssh/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tunnel-ssh/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tunnel-ssh/build/test-report.html](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tunnel-ssh/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tunnel-ssh/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tunnel-ssh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tunnel-ssh/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tunnel-ssh/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "tunnel-ssh",
    "version": "4.1.2",
    "description": "Easy extendable SSH tunnel",
    "main": "index.js",
    "scripts": {
        "test": "mocha && eslint ."
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/agebrock/tunnel-ssh"
    },
    "keywords": [
        "tunnel",
        "ssh",
        "mysql",
        "develop",
        "net"
    ],
    "author": {
        "name": "Christoph Hagenbrock"
    },
    "license": "MIT",
    "dependencies": {
        "debug": "2.6.0",
        "lodash.defaults": "^4.1.0",
        "ssh2": "0.5.4"
    },
    "devDependencies": {
        "chai": "3.5.0",
        "eslint": "^3.2.2",
        "eslint-config-xo": "^0.17.0",
        "mocha": "^3.0.2"
    },
    "eslintConfig": {
        "extends": "xo",
        "env": {
            "mocha": true
        },
        "rules": {
            "indent": [
                "error",
                4
            ]
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
