# npmtest-passport-local-mongoose

#### basic test coverage for  [passport-local-mongoose (v4.0.0)](https://github.com/saintedlama/passport-local-mongoose#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-local-mongoose.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-local-mongoose) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-local-mongoose.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-local-mongoose)

#### Mongoose plugin that simplifies building username and password login with Passport

[![NPM](https://nodei.co/npm/passport-local-mongoose.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-local-mongoose)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-local-mongoose/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-local-mongoose/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-local-mongoose/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-local-mongoose/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-local-mongoose/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-local-mongoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-local-mongoose/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-local-mongoose/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christoph Walcher"
    },
    "bugs": {
        "url": "https://github.com/saintedlama/passport-local-mongoose/issues"
    },
    "dependencies": {
        "generaterr": "^1.2.0",
        "passport-local": "^1.0.0",
        "scmp": "^1.0.0",
        "semver": "^5.1.0"
    },
    "description": "Mongoose plugin that simplifies building username and password login with Passport",
    "devDependencies": {
        "chai": "^3.2.0",
        "mocha": "^2.3.2",
        "mongoose": "4.1.x",
        "shelljs": "^0.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "10fee927eaf9785bb2e10e2a8c446a0ff1fa0107",
        "tarball": "https://registry.npmjs.org/passport-local-mongoose/-/passport-local-mongoose-4.0.0.tgz"
    },
    "engines": {
        "node": ">= 0.12"
    },
    "gitHead": "0b5da93def0244a551188263bf473d48f3b95876",
    "homepage": "https://github.com/saintedlama/passport-local-mongoose#readme",
    "keywords": [
        "mongoose",
        "passport",
        "authentication",
        "login"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "saintedlama"
        }
    ],
    "name": "passport-local-mongoose",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/saintedlama/passport-local-mongoose.git"
    },
    "scripts": {
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha --report html -- -R spec",
        "release": "node release.js",
        "test": "mocha -R spec test/"
    },
    "version": "4.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
