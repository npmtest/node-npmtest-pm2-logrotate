# npmtest-pm2-logrotate

#### basic test coverage for  [pm2-logrotate (v2.2.0)](https://github.com/pm2-hive/pm2-logrotate)  [![npm package](https://img.shields.io/npm/v/npmtest-pm2-logrotate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pm2-logrotate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pm2-logrotate.svg)](https://travis-ci.org/npmtest/node-npmtest-pm2-logrotate)

#### Module to rotate logs of every pm2 application

[![NPM](https://nodei.co/npm/pm2-logrotate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pm2-logrotate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pm2-logrotate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pm2-logrotate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pm2-logrotate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pm2-logrotate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pm2-logrotate/build/test-report.html](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2-logrotate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pm2-logrotate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "apps": [
        {
            "name": "pm2-logrotate",
            "script": "app.js"
        }
    ],
    "author": {
        "name": "Joni SHKURTI"
    },
    "bugs": {
        "url": "https://github.com/pm2-hive/pm2-logrotate/issues"
    },
    "config": {
        "max_size": "10M",
        "retain": "all",
        "compress": false,
        "dateFormat": "YYYY-MM-DD_HH-mm-ss",
        "workerInterval": "30",
        "rotateInterval": "0 0 * * *",
        "rotateModule": true
    },
    "dependencies": {
        "moment-timezone": "0.5.5",
        "node-schedule": "1.1.1",
        "pm2": "latest",
        "pmx": "latest"
    },
    "description": "Module to rotate logs of every pm2 application",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "d46ef034156151857e7798e99c5d81ad2084c653",
        "tarball": "https://registry.npmjs.org/pm2-logrotate/-/pm2-logrotate-2.2.0.tgz"
    },
    "gitHead": "815ceb1294366405d30ef80fd0cd4c456dfe41f0",
    "homepage": "https://github.com/pm2-hive/pm2-logrotate",
    "license": "MIT",
    "main": "app.js",
    "maintainers": [
        {
            "name": "alavit-d"
        },
        {
            "name": "jshkurti"
        },
        {
            "name": "tknew"
        },
        {
            "name": "vmarchaud"
        }
    ],
    "name": "pm2-logrotate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pm2-hive/pm2-logrotate.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
