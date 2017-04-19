# npmtest-sockjs-client

#### test coverage for  [sockjs-client (v1.1.2)](http://sockjs.org)  [![npm package](https://img.shields.io/npm/v/npmtest-sockjs-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sockjs-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sockjs-client.svg)](https://travis-ci.org/npmtest/node-npmtest-sockjs-client)

#### SockJS-client is a browser JavaScript library that provides a WebSocket-like object. SockJS gives you a coherent, cross-browser, Javascript API which creates a low latency, full duplex, cross-domain communication channel between the browser and the web se

[![NPM](https://nodei.co/npm/sockjs-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sockjs-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sockjs-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sockjs-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sockjs-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sockjs-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sockjs-client/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sockjs-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sockjs-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sockjs-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sockjs-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sockjs-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sockjs-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sockjs-client/build/test-report.html](https://npmtest.github.io/node-npmtest-sockjs-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sockjs-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sockjs-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sockjs-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sockjs-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sockjs-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sockjs-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sockjs-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sockjs-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bryce Kahle"
    },
    "browser": {
        "./lib/transport/driver/websocket.js": "./lib/transport/browser/websocket.js",
        "eventsource": "./lib/transport/browser/eventsource.js",
        "./lib/transport/driver/xhr.js": "./lib/transport/browser/abstract-xhr.js",
        "crypto": "./lib/utils/browser-crypto.js",
        "events": "./lib/event/emitter.js"
    },
    "bugs": {
        "url": "https://github.com/sockjs/sockjs-client/issues"
    },
    "contributors": [
        {
            "name": "Bryce Kahle"
        },
        {
            "name": "Marek Majkowski"
        }
    ],
    "dependencies": {
        "debug": "^2.2.0",
        "eventsource": "0.1.6",
        "faye-websocket": "~0.11.0",
        "inherits": "^2.0.1",
        "json3": "^3.3.2",
        "url-parse": "^1.1.1"
    },
    "description": "SockJS-client is a browser JavaScript library that provides a WebSocket-like object. SockJS gives you a coherent, cross-browser, Javascript API which creates a low latency, full duplex, cross-domain communication channel between the browser and the web se",
    "devDependencies": {
        "browserify": "^13.3.0",
        "envify": "^4.0.0",
        "eslint": "^3.14.0",
        "expect.js": "~0.3.1",
        "gulp": "^3.9.1",
        "gulp-header": "^1.8.8",
        "gulp-rename": "~1.2.0",
        "gulp-replace": "^0.5.4",
        "gulp-sourcemaps": "^2.4.0",
        "gulp-uglify": "^2.0.0",
        "mocha": "^3.2.0",
        "node-static": "^0.7.6",
        "proxyquire": "^1.7.10",
        "pump": "^1.0.2",
        "sockjs": "^0.3.17",
        "vinyl-buffer": "~1.0.0",
        "vinyl-source-stream": "^1.0.0",
        "zuul": "github:brycekahle/zuul#ngrok",
        "zuul-ngrok": "github:brycekahle/zuul-ngrok#master"
    },
    "directories": {},
    "dist": {
        "shasum": "f0212a8550e4c9468c8cceaeefd2e3493c033ad5",
        "tarball": "https://registry.npmjs.org/sockjs-client/-/sockjs-client-1.1.2.tgz"
    },
    "gitHead": "1d48f43b6effb13c1abb0be3fc2ec00f9c8aeecb",
    "homepage": "http://sockjs.org",
    "keywords": [
        "websockets",
        "websocket"
    ],
    "license": "MIT",
    "main": "./lib/entry.js",
    "maintainers": [
        {
            "name": "brycekahle"
        }
    ],
    "name": "sockjs-client",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sockjs/sockjs-client.git"
    },
    "scripts": {
        "gulp": "gulp",
        "lint": "eslint .",
        "postpublish": "git push origin --all && git push origin --tags",
        "postversion": "npm publish",
        "test": "mocha tests/node.js",
        "test:browser_local": "npm run test:bundle && zuul --disable-tunnel --local 9090 -- tests/browser.js",
        "test:browser_remote": "npm run test:bundle && zuul -- tests/browser.js",
        "test:bundle": "gulp testbundle",
        "version": "gulp release && git add -A dist lib/version.js"
    },
    "version": "1.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
