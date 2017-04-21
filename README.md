# npmtest-websockets-streaming-audio

#### basic test coverage for  [websockets-streaming-audio (v1.0.35)](https://github.com/scottstensland)  [![npm package](https://img.shields.io/npm/v/npmtest-websockets-streaming-audio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-websockets-streaming-audio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-websockets-streaming-audio.svg)](https://travis-ci.org/npmtest/node-npmtest-websockets-streaming-audio)

#### Click a browser button to launch a node.js process on the server side which streams audio using web sockets back to the browser which is then rendered using web audio API   My plan is to make this modular enough to get added to your process as simple API calls

[![NPM](https://nodei.co/npm/websockets-streaming-audio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/websockets-streaming-audio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-websockets-streaming-audio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-websockets-streaming-audio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/test-report.html](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-websockets-streaming-audio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-websockets-streaming-audio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-websockets-streaming-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-websockets-streaming-audio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-websockets-streaming-audio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "websockets-streaming-audio",
    "version": "1.0.35",
    "author": "Scott Stensland <scottstensland@gmail.com> (http://catfoodnation.com/)",
    "bugs": {
        "url": "https://github.com/scottstensland/websockets-streaming-audio/issues"
    },
    "dependencies": {
        "ws": "0.4.x",
        "express": "^4.4.5",
        "audio-utils": "1.0.x",
        "shared-utils": "0.1.8"
    },
    "description": "Click a browser button to launch a node.js process on the server side which streams audio using web sockets back to the browser which is then rendered using web audio API   My plan is to make this modular enough to get added to your process as simple API calls",
    "engines": {
        "node": "0.10.x"
    },
    "homepage": "https://github.com/scottstensland",
    "keywords": [
        "Node.js",
        "websockets",
        "webworkers",
        "webaudio",
        "audio",
        "streaming"
    ],
    "license": "ISC",
    "repository": {
        "type": "git",
        "url": "https://github.com/scottstensland/websockets-streaming-audio.git"
    },
    "scripts": {
        "start_min": "node src_min/app.js",
        "start_loki": "node src/app_loki.js",
        "start": "node src/app.js",
        "test": "make"
    },
    "subdomain": "websockets-streaming-audio",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
