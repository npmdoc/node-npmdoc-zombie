# api documentation for  [zombie (v5.0.5)](https://www.npmjs.com/package/zombie)  [![npm package](https://img.shields.io/npm/v/npmdoc-zombie.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-zombie) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-zombie.svg)](https://travis-ci.org/npmdoc/node-npmdoc-zombie)
#### Insanely fast, full-stack, headless browser testing using Node.js

[![NPM](https://nodei.co/npm/zombie.png?downloads=true)](https://www.npmjs.com/package/zombie)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zombie/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-zombie_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zombie/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-zombie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-zombie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Assaf Arkin",
        "email": "assaf@labnotes.org",
        "url": "http://labnotes.org/"
    },
    "bugs": {
        "url": "http://github.com/assaf/zombie/issues"
    },
    "contributors": [
        {
            "name": "Bob Lail",
            "email": "bob.lailfamily@gmail.com",
            "url": "http://boblail.tumblr.com/"
        },
        {
            "name": "Brian McDaniel",
            "url": "https://github.com/brianmcd"
        },
        {
            "name": "Damian Janowski"
        },
        {
            "name": "José Valim",
            "email": "jose.valim@plataformatec.com.br",
            "url": "http://blog.plataformatec.com.br/"
        },
        {
            "name": "Matt Lavin",
            "email": "matt.lavin@gmail.com",
            "url": "https://github.com/mdlavin"
        }
    ],
    "dependencies": {
        "babel-runtime": "5.8.29",
        "bluebird": "^3.0",
        "debug": "^2.2",
        "eventsource": "^0.1.6",
        "iconv-lite": "^0.4.13",
        "jsdom": "^7.2.2",
        "lodash": "^3.10.1",
        "mime": "^1.3.4",
        "ms": "^0.7.1",
        "request": "^2.65.0",
        "tough-cookie": "^2.2.0",
        "ws": "^1.0.1"
    },
    "description": "Insanely fast, full-stack, headless browser testing using Node.js",
    "devDependencies": {
        "babel": "5.8.29",
        "babel-eslint": "^4.0.10",
        "body-parser": "^1.13.3",
        "cookie-parser": "^1.3.5",
        "del": "^2.0.2",
        "eslint": "^1.7.3",
        "express": "^4.13.3",
        "gulp": "^3.9.0",
        "gulp-babel": "^5.3.0",
        "gulp-eslint": "^1.0.0",
        "gulp-exec": "^2.1.2",
        "gulp-notify": "^2.0.1",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-util": "^3.0.7",
        "mocha": "^2.2.5",
        "morgan": "^1.6.1",
        "multiparty": "^4.1.2",
        "replay": "^2.1.2",
        "requirejs": "^2.1.20"
    },
    "directories": {},
    "dist": {
        "shasum": "69da3fa34959ec0f066746267803197a828485c3",
        "tarball": "https://registry.npmjs.org/zombie/-/zombie-5.0.5.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "99d05d30720ab709ff1683d98bec04b07842a272",
    "homepage": "https://www.npmjs.com/package/zombie",
    "keywords": [
        "test",
        "tests",
        "testing",
        "TDD",
        "spec",
        "specs",
        "BDD",
        "headless",
        "browser",
        "html",
        "html5",
        "dom",
        "css",
        "javascript",
        "integration",
        "ajax",
        "full-stack",
        "DSL"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "assaf",
            "email": "assaf@labnotes.org"
        },
        {
            "name": "mdlavin",
            "email": "matt.lavin@gmail.com"
        }
    ],
    "name": "zombie",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/assaf/zombie.git"
    },
    "scripts": {
        "build": "gulp build",
        "postpublish": "git push",
        "prepublish": "npm test && gulp build",
        "test": "gulp lint && mocha"
    },
    "version": "5.0.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module zombie](#apidoc.module.zombie)
1.  boolean <span class="apidocSignatureSpan">zombie.</span>runScripts
1.  boolean <span class="apidocSignatureSpan">zombie.</span>silent
1.  boolean <span class="apidocSignatureSpan">zombie.</span>strictSSL
1.  [function <span class="apidocSignatureSpan">zombie.</span>Assert (browser)](#apidoc.element.zombie.Assert)
1.  [function <span class="apidocSignatureSpan">zombie.</span>Headers (init)](#apidoc.element.zombie.Headers)
1.  [function <span class="apidocSignatureSpan">zombie.</span>Pipeline (browser)](#apidoc.element.zombie.Pipeline)
1.  [function <span class="apidocSignatureSpan">zombie.</span>Request (input, init)](#apidoc.element.zombie.Request)
1.  [function <span class="apidocSignatureSpan">zombie.</span>Response (bodyInit, responseInit)](#apidoc.element.zombie.Response)
1.  [function <span class="apidocSignatureSpan">zombie.</span>_debug ()](#apidoc.element.zombie._debug)
1.  object <span class="apidocSignatureSpan">zombie.</span>_debugEnabled
1.  object <span class="apidocSignatureSpan">zombie.</span>_extensions
1.  object <span class="apidocSignatureSpan">zombie.</span>proxy
1.  object <span class="apidocSignatureSpan">zombie.</span>site
1.  string <span class="apidocSignatureSpan">zombie.</span>VERSION
1.  string <span class="apidocSignatureSpan">zombie.</span>features
1.  string <span class="apidocSignatureSpan">zombie.</span>language
1.  string <span class="apidocSignatureSpan">zombie.</span>localAddress
1.  string <span class="apidocSignatureSpan">zombie.</span>userAgent
1.  string <span class="apidocSignatureSpan">zombie.</span>waitDuration



# <a name="apidoc.module.zombie"></a>[module zombie](#apidoc.module.zombie)

#### <a name="apidoc.element.zombie.Assert"></a>[function <span class="apidocSignatureSpan">zombie.</span>Assert (browser)](#apidoc.element.zombie.Assert)
- description and source-code
```javascript
function Assert(browser) {
  _classCallCheck(this, Assert);

  this.browser = browser;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.zombie.Headers"></a>[function <span class="apidocSignatureSpan">zombie.</span>Headers (init)](#apidoc.element.zombie.Headers)
- description and source-code
```javascript
function Headers(init) {
  var _this = this;

  _classCallCheck(this, Headers);

  this._headers = [];
  if (init instanceof Headers || init instanceof Array) {
    var _iteratorNormalCompletion = true;
    var _didIteratorError = false;
    var _iteratorError = undefined;

    try {
      for (var _iterator = _getIterator(init), _step; !(_iteratorNormalCompletion = (_step = _iterator.next()).done); _iteratorNormalCompletion
 = true) {
        var _step$value = _slicedToArray(_step.value, 2);

        var _name = _step$value[0];
        var value = _step$value[1];

        this.append(_name, value);
      }
    } catch (err) {
      _didIteratorError = true;
      _iteratorError = err;
    } finally {
      try {
        if (!_iteratorNormalCompletion && _iterator['return']) {
          _iterator['return']();
        }
      } finally {
        if (_didIteratorError) {
          throw _iteratorError;
        }
      }
    }
  } else if (typeof init === "object") _.each(init, function (value, name) {
    _this.append(name, value);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.zombie.Pipeline"></a>[function <span class="apidocSignatureSpan">zombie.</span>Pipeline (browser)](#apidoc.element.zombie.Pipeline)
- description and source-code
```javascript
function Pipeline(browser) {
  _classCallCheck(this, Pipeline);

  _get(Object.getPrototypeOf(Pipeline.prototype), 'constructor', this).call(this);
  this._browser = browser;
  var _iteratorNormalCompletion = true;
  var _didIteratorError = false;
  var _iteratorError = undefined;

  try {
    for (var _iterator = _getIterator(Pipeline._default), _step; !(_iteratorNormalCompletion = (_step = _iterator.next()).done);
_iteratorNormalCompletion = true) {
      var handler = _step.value;

      this.push(handler);
    }
  } catch (err) {
    _didIteratorError = true;
    _iteratorError = err;
  } finally {
    try {
      if (!_iteratorNormalCompletion && _iterator['return']) {
        _iterator['return']();
      }
    } finally {
      if (_didIteratorError) {
        throw _iteratorError;
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.zombie.Request"></a>[function <span class="apidocSignatureSpan">zombie.</span>Request (input, init)](#apidoc.element.zombie.Request)
- description and source-code
```javascript
function Request(input, init) {
  _classCallCheck(this, Request);

  var method = ((init ? init.method : input.method) || 'GET').toUpperCase();
  var bodyInit = null;

  if (input instanceof Request && input._stream) {
    if (input._bodyUsed) throw new TypeError('Request body already used');
    bodyInit = input;
    input._bodyUsed = true;
  }

  if (init && init.body) {
    if (method === 'GET' || method === 'HEAD') throw new TypeError('Cannot include body with GET/HEAD request');
    bodyInit = init.body;
  }
  _get(Object.getPrototypeOf(Request.prototype), 'constructor', this).call(this, bodyInit);

  if (typeof input === 'string' || input instanceof String) this.url = URL.format(input);else if (input instanceof Request) this
.url = input.url;
  if (!this.url) throw new TypeError('Input must be string or another Request');

  this.method = method;
  this.headers = new Headers(init ? init.headers : input.headers);
  if (this._contentType && !this.headers.has('Content-Type')) this.headers.set('Content-Type', this._contentType);

  // Default redirect is follow, also treat manual as follow
  this.redirect = init && init.redirect;
  if (this.redirect !== 'error') this.redirect = 'follow';
  this._redirectCount = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.zombie.Response"></a>[function <span class="apidocSignatureSpan">zombie.</span>Response (bodyInit, responseInit)](#apidoc.element.zombie.Response)
- description and source-code
```javascript
function Response(bodyInit, responseInit) {
  _classCallCheck(this, Response);

  _get(Object.getPrototypeOf(Response.prototype), 'constructor', this).call(this, bodyInit);
  if (responseInit) {
    if (responseInit.status < 200 || responseInit.status > 599) throw new RangeError('Status code ' + responseInit.status + ' not
 in range');
    var statusText = responseInit.statusText || HTTP.STATUS_CODES[responseInit.status] || 'Unknown';
    if (!/^[^\n\r]+$/.test(statusText)) throw new TypeError('Status text ' + responseInit.statusText + ' not valid format');

    this._url = URL.format(responseInit.url || '');
    this.type = 'default';
    this.status = responseInit.status;
    this.statusText = statusText;
    this.headers = new Headers(responseInit.headers);
  } else {
    this.type = 'error';
    this.status = 0;
    this.statusText = '';
    this.headers = new Headers();
  }
  if (this._contentType && !this.headers.has('Content-Type')) this.headers.set('Content-Type', this._contentType);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.zombie._debug"></a>[function <span class="apidocSignatureSpan">zombie.</span>_debug ()](#apidoc.element.zombie._debug)
- description and source-code
```javascript
function debug() {
  // disabled?
  if (!debug.enabled) return;

  var self = debug;

  // set 'diff' timestamp
  var curr = +new Date();
  var ms = curr - (prevTime || curr);
  self.diff = ms;
  self.prev = prevTime;
  self.curr = curr;
  prevTime = curr;

  // turn the 'arguments' into a proper Array
  var args = new Array(arguments.length);
  for (var i = 0; i < args.length; i++) {
    args[i] = arguments[i];
  }

  args[0] = exports.coerce(args[0]);

  if ('string' !== typeof args[0]) {
    // anything else let's inspect with %O
    args.unshift('%O');
  }

  // apply any 'formatters' transformations
  var index = 0;
  args[0] = args[0].replace(/%([a-zA-Z%])/g, function(match, format) {
    // if we encounter an escaped % then don't increase the array index
    if (match === '%%') return match;
    index++;
    var formatter = exports.formatters[format];
    if ('function' === typeof formatter) {
      var val = args[index];
      match = formatter.call(self, val);

      // now we need to remove 'args[index]' since it's inlined in the 'format'
      args.splice(index, 1);
      index--;
    }
    return match;
  });

  // apply env-specific formatting (colors, etc.)
  exports.formatArgs.call(self, args);

  var logFn = debug.log || exports.log || console.log.bind(console);
  logFn.apply(self, args);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
