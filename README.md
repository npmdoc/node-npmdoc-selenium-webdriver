# api documentation for  [selenium-webdriver (v3.3.0)](https://github.com/SeleniumHQ/selenium)  [![npm package](https://img.shields.io/npm/v/npmdoc-selenium-webdriver.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-selenium-webdriver) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-selenium-webdriver.svg)](https://travis-ci.org/npmdoc/node-npmdoc-selenium-webdriver)
#### The official WebDriver JavaScript bindings from the Selenium project

[![NPM](https://nodei.co/npm/selenium-webdriver.png?downloads=true)](https://www.npmjs.com/package/selenium-webdriver)

[![apidoc](https://npmdoc.github.io/node-npmdoc-selenium-webdriver/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-selenium-webdriver%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-selenium-webdriver/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-selenium-webdriver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-selenium-webdriver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/SeleniumHQ/selenium/issues"
    },
    "dependencies": {
        "adm-zip": "^0.4.7",
        "rimraf": "^2.5.4",
        "tmp": "0.0.30",
        "xml2js": "^0.4.17"
    },
    "description": "The official WebDriver JavaScript bindings from the Selenium project",
    "devDependencies": {
        "express": "^4.14.0",
        "mocha": "^3.1.2",
        "multer": "^1.2.0",
        "promises-aplus-tests": "^2.1.2",
        "serve-index": "^1.8.0",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "f14d9b04cee9495d4284d22105b189b8305ccca1",
        "tarball": "https://registry.npmjs.org/selenium-webdriver/-/selenium-webdriver-3.3.0.tgz"
    },
    "engines": {
        "node": ">= 6.9.0"
    },
    "homepage": "https://github.com/SeleniumHQ/selenium",
    "keywords": [
        "automation",
        "selenium",
        "testing",
        "webdriver",
        "webdriverjs"
    ],
    "license": "Apache-2.0",
    "main": "./index",
    "maintainers": [
        {
            "name": "jmleyba",
            "email": "jmleyba@gmail.com"
        }
    ],
    "name": "selenium-webdriver",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/SeleniumHQ/selenium.git"
    },
    "scripts": {
        "test": "mocha -t 600000 --recursive test"
    },
    "version": "3.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module selenium-webdriver](#apidoc.module.selenium-webdriver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>ActionSequence (driver)](#apidoc.element.selenium-webdriver.ActionSequence)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>Builder ()](#apidoc.element.selenium-webdriver.Builder)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>By (using, value)](#apidoc.element.selenium-webdriver.By)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>Capabilities (Capabilities|Map<string, ?>|Object)](#apidoc.element.selenium-webdriver.Capabilities)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>Condition (!WebDriver)](#apidoc.element.selenium-webdriver.Condition)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>EventEmitter (type, var_args)](#apidoc.element.selenium-webdriver.EventEmitter)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>FileDetector (driver, path)](#apidoc.element.selenium-webdriver.FileDetector)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>Session (Object|Capabilities)](#apidoc.element.selenium-webdriver.Session)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>ThenableWebDriver (...args)](#apidoc.element.selenium-webdriver.ThenableWebDriver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>TouchSequence (driver)](#apidoc.element.selenium-webdriver.TouchSequence)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>WebDriver (Session|IThenable<!Session>)](#apidoc.element.selenium-webdriver.WebDriver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>WebElement (!IThenable<string>|string)](#apidoc.element.selenium-webdriver.WebElement)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>WebElementCondition (!WebDriver)](#apidoc.element.selenium-webdriver.WebElementCondition)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>WebElementPromise (driver, el)](#apidoc.element.selenium-webdriver.WebElementPromise)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>assert (value)](#apidoc.element.selenium-webdriver.assert)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>exec (command, opt_options)](#apidoc.element.selenium-webdriver.exec)
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>Browser
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>Button
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>Capability
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>Key
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>actions
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>binary
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>by
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>capabilities
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>chrome
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>command
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>edge
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>error
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>events
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>extension
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>http
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>ie
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>input
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>logging
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>opera
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>phantomjs
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>portprober
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>profile
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>promise
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>proxy
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>safari
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>session
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>until
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>util
1.  object <span class="apidocSignatureSpan">selenium-webdriver.</span>webdriver

#### [module selenium-webdriver.Key](#apidoc.module.selenium-webdriver.Key)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>chord (var_args)](#apidoc.element.selenium-webdriver.Key.chord)
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>ADD
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>ALT
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>ARROW_DOWN
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>ARROW_LEFT
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>ARROW_RIGHT
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>ARROW_UP
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>BACK_SPACE
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>CANCEL
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>CLEAR
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>COMMAND
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>CONTROL
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>DECIMAL
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>DELETE
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>DIVIDE
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>DOWN
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>END
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>ENTER
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>EQUALS
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>ESCAPE
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F1
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F10
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F11
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F12
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F2
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F3
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F4
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F5
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F6
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F7
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F8
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>F9
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>HELP
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>HOME
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>INSERT
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>LEFT
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>META
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>MULTIPLY
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NULL
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD0
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD1
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD2
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD3
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD4
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD5
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD6
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD7
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD8
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>NUMPAD9
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>PAGE_DOWN
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>PAGE_UP
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>PAUSE
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>RETURN
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>RIGHT
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>SEMICOLON
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>SEPARATOR
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>SHIFT
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>SPACE
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>SUBTRACT
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>TAB
1.  string <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>UP

#### [module selenium-webdriver.actions](#apidoc.module.selenium-webdriver.actions)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.actions.</span>ActionSequence (driver)](#apidoc.element.selenium-webdriver.actions.ActionSequence)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.actions.</span>TouchSequence (driver)](#apidoc.element.selenium-webdriver.actions.TouchSequence)

#### [module selenium-webdriver.assert](#apidoc.module.selenium-webdriver.assert)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>assert (value)](#apidoc.element.selenium-webdriver.assert.assert)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.assert.</span>Assertion (subject, opt_invert)](#apidoc.element.selenium-webdriver.assert.Assertion)

#### [module selenium-webdriver.binary](#apidoc.module.selenium-webdriver.binary)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.binary.</span>Binary (string|Channel)](#apidoc.element.selenium-webdriver.binary.Binary)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.binary.</span>Channel (darwin, win32)](#apidoc.element.selenium-webdriver.binary.Channel)

#### [module selenium-webdriver.by](#apidoc.module.selenium-webdriver.by)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.by.</span>By (using, value)](#apidoc.element.selenium-webdriver.by.By)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.by.</span>checkedLocator (locator)](#apidoc.element.selenium-webdriver.by.checkedLocator)

#### [module selenium-webdriver.capabilities](#apidoc.module.selenium-webdriver.capabilities)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.capabilities.</span>Capabilities (Capabilities|Map<string, ?>|Object)](#apidoc.element.selenium-webdriver.capabilities.Capabilities)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.capabilities.</span>ProxyConfig ()](#apidoc.element.selenium-webdriver.capabilities.ProxyConfig)
1.  object <span class="apidocSignatureSpan">selenium-webdriver.capabilities.</span>Browser
1.  object <span class="apidocSignatureSpan">selenium-webdriver.capabilities.</span>Capability

#### [module selenium-webdriver.chrome](#apidoc.module.selenium-webdriver.chrome)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>Driver (Capabilities|Options)](#apidoc.element.selenium-webdriver.chrome.Driver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>Options ()](#apidoc.element.selenium-webdriver.chrome.Options)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>ServiceBuilder (opt_exe)](#apidoc.element.selenium-webdriver.chrome.ServiceBuilder)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>getDefaultService ()](#apidoc.element.selenium-webdriver.chrome.getDefaultService)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>setDefaultService (service)](#apidoc.element.selenium-webdriver.chrome.setDefaultService)

#### [module selenium-webdriver.command](#apidoc.module.selenium-webdriver.command)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.command.</span>Command (name)](#apidoc.element.selenium-webdriver.command.Command)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.command.</span>Executor (command)](#apidoc.element.selenium-webdriver.command.Executor)
1.  object <span class="apidocSignatureSpan">selenium-webdriver.command.</span>Name

#### [module selenium-webdriver.edge](#apidoc.module.selenium-webdriver.edge)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>Driver (capabilities.Capabilities|Options)](#apidoc.element.selenium-webdriver.edge.Driver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>Options ()](#apidoc.element.selenium-webdriver.edge.Options)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>ServiceBuilder (opt_exe)](#apidoc.element.selenium-webdriver.edge.ServiceBuilder)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>getDefaultService ()](#apidoc.element.selenium-webdriver.edge.getDefaultService)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>setDefaultService (service)](#apidoc.element.selenium-webdriver.edge.setDefaultService)

#### [module selenium-webdriver.error](#apidoc.module.selenium-webdriver.error)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>ElementNotSelectableError (opt_error)](#apidoc.element.selenium-webdriver.error.ElementNotSelectableError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>ElementNotVisibleError (opt_error)](#apidoc.element.selenium-webdriver.error.ElementNotVisibleError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidArgumentError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidArgumentError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidCookieDomainError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidCookieDomainError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidElementCoordinatesError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidElementCoordinatesError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidElementStateError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidElementStateError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidSelectorError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidSelectorError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>JavascriptError (opt_error)](#apidoc.element.selenium-webdriver.error.JavascriptError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>MoveTargetOutOfBoundsError (opt_error)](#apidoc.element.selenium-webdriver.error.MoveTargetOutOfBoundsError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchAlertError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchAlertError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchElementError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchElementError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchFrameError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchFrameError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchSessionError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchSessionError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchWindowError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchWindowError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>ScriptTimeoutError (opt_error)](#apidoc.element.selenium-webdriver.error.ScriptTimeoutError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>SessionNotCreatedError (opt_error)](#apidoc.element.selenium-webdriver.error.SessionNotCreatedError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>StaleElementReferenceError (opt_error)](#apidoc.element.selenium-webdriver.error.StaleElementReferenceError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>TimeoutError (opt_error)](#apidoc.element.selenium-webdriver.error.TimeoutError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnableToCaptureScreenError (opt_error)](#apidoc.element.selenium-webdriver.error.UnableToCaptureScreenError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnableToSetCookieError (opt_error)](#apidoc.element.selenium-webdriver.error.UnableToSetCookieError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnexpectedAlertOpenError (opt_error, opt_text)](#apidoc.element.selenium-webdriver.error.UnexpectedAlertOpenError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnknownCommandError (opt_error)](#apidoc.element.selenium-webdriver.error.UnknownCommandError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnknownMethodError (opt_error)](#apidoc.element.selenium-webdriver.error.UnknownMethodError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnsupportedOperationError (opt_error)](#apidoc.element.selenium-webdriver.error.UnsupportedOperationError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>WebDriverError (opt_error)](#apidoc.element.selenium-webdriver.error.WebDriverError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>checkLegacyResponse (responseObj)](#apidoc.element.selenium-webdriver.error.checkLegacyResponse)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>checkResponse (data)](#apidoc.element.selenium-webdriver.error.checkResponse)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>encodeError (err)](#apidoc.element.selenium-webdriver.error.encodeError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>isErrorResponse (data)](#apidoc.element.selenium-webdriver.error.isErrorResponse)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>throwDecodedError (data)](#apidoc.element.selenium-webdriver.error.throwDecodedError)
1.  object <span class="apidocSignatureSpan">selenium-webdriver.error.</span>ErrorCode

#### [module selenium-webdriver.events](#apidoc.module.selenium-webdriver.events)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.events.</span>EventEmitter (type, var_args)](#apidoc.element.selenium-webdriver.events.EventEmitter)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.events.</span>Listener (Object|undefined)](#apidoc.element.selenium-webdriver.events.Listener)

#### [module selenium-webdriver.exec](#apidoc.module.selenium-webdriver.exec)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.</span>exec (command, opt_options)](#apidoc.element.selenium-webdriver.exec.exec)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.exec.</span>Command (string)](#apidoc.element.selenium-webdriver.exec.Command)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.exec.</span>Result (code, signal)](#apidoc.element.selenium-webdriver.exec.Result)

#### [module selenium-webdriver.extension](#apidoc.module.selenium-webdriver.extension)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.extension.</span>install (extension, dir)](#apidoc.element.selenium-webdriver.extension.install)

#### [module selenium-webdriver.http](#apidoc.module.selenium-webdriver.http)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>Client (httpRequest)](#apidoc.element.selenium-webdriver.http.Client)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>Executor (Client|IThenable<!Client>)](#apidoc.element.selenium-webdriver.http.Executor)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>Request (method, path, opt_data)](#apidoc.element.selenium-webdriver.http.Request)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>Response (status, headers, body)](#apidoc.element.selenium-webdriver.http.Response)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>buildPath (path, parameters)](#apidoc.element.selenium-webdriver.http.buildPath)

#### [module selenium-webdriver.ie](#apidoc.module.selenium-webdriver.ie)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.ie.</span>Driver (capabilities.Capabilities|Options)](#apidoc.element.selenium-webdriver.ie.Driver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.ie.</span>Options ()](#apidoc.element.selenium-webdriver.ie.Options)
1.  object <span class="apidocSignatureSpan">selenium-webdriver.ie.</span>Level

#### [module selenium-webdriver.input](#apidoc.module.selenium-webdriver.input)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.input.</span>FileDetector (driver, path)](#apidoc.element.selenium-webdriver.input.FileDetector)
1.  object <span class="apidocSignatureSpan">selenium-webdriver.input.</span>Button
1.  object <span class="apidocSignatureSpan">selenium-webdriver.input.</span>Key

#### [module selenium-webdriver.logging](#apidoc.module.selenium-webdriver.logging)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Entry (!Level|string|number)](#apidoc.element.selenium-webdriver.logging.Entry)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Level (name, level)](#apidoc.element.selenium-webdriver.logging.Level)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>LogManager ()](#apidoc.element.selenium-webdriver.logging.LogManager)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Logger (name, opt_level)](#apidoc.element.selenium-webdriver.logging.Logger)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Preferences ()](#apidoc.element.selenium-webdriver.logging.Preferences)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>addConsoleHandler (opt_logger)](#apidoc.element.selenium-webdriver.logging.addConsoleHandler)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>getLevel (nameOrValue)](#apidoc.element.selenium-webdriver.logging.getLevel)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>getLogger (name)](#apidoc.element.selenium-webdriver.logging.getLogger)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>installConsoleHandler ()](#apidoc.element.selenium-webdriver.logging.installConsoleHandler)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>removeConsoleHandler (opt_logger)](#apidoc.element.selenium-webdriver.logging.removeConsoleHandler)
1.  object <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Type

#### [module selenium-webdriver.opera](#apidoc.module.selenium-webdriver.opera)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>Driver (capabilities.Capabilities|Options)](#apidoc.element.selenium-webdriver.opera.Driver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>Options ()](#apidoc.element.selenium-webdriver.opera.Options)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>ServiceBuilder (opt_exe)](#apidoc.element.selenium-webdriver.opera.ServiceBuilder)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>getDefaultService ()](#apidoc.element.selenium-webdriver.opera.getDefaultService)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>setDefaultService (service)](#apidoc.element.selenium-webdriver.opera.setDefaultService)

#### [module selenium-webdriver.phantomjs](#apidoc.module.selenium-webdriver.phantomjs)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.phantomjs.</span>Driver (opt_capabilities, opt_flow, opt_logFile)](#apidoc.element.selenium-webdriver.phantomjs.Driver)

#### [module selenium-webdriver.portprober](#apidoc.module.selenium-webdriver.portprober)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.portprober.</span>findFreePort (opt_host)](#apidoc.element.selenium-webdriver.portprober.findFreePort)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.portprober.</span>isFree (port, opt_host)](#apidoc.element.selenium-webdriver.portprober.isFree)

#### [module selenium-webdriver.profile](#apidoc.module.selenium-webdriver.profile)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.profile.</span>Profile (opt_dir)](#apidoc.element.selenium-webdriver.profile.Profile)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.profile.</span>decode (data)](#apidoc.element.selenium-webdriver.profile.decode)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.profile.</span>loadUserPrefs (f)](#apidoc.element.selenium-webdriver.profile.loadUserPrefs)

#### [module selenium-webdriver.promise](#apidoc.module.selenium-webdriver.promise)
1.  boolean <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>LONG_STACK_TRACES
1.  boolean <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>USE_PROMISE_MANAGER
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>CancellableThenable (new: CancellableThenable, ...?)](#apidoc.element.selenium-webdriver.promise.CancellableThenable)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>CancellationError (opt_msg)](#apidoc.element.selenium-webdriver.promise.CancellationError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>ControlFlow ()](#apidoc.element.selenium-webdriver.promise.ControlFlow)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Deferred (opt_flow, opt_skipLog)](#apidoc.element.selenium-webdriver.promise.Deferred)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>MultipleUnhandledRejectionError (Set<*>)](#apidoc.element.selenium-webdriver.promise.MultipleUnhandledRejectionError)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Promise ( * function((T|IThenable<T>|Thenable)](#apidoc.element.selenium-webdriver.promise.Promise)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Resolver ()](#apidoc.element.selenium-webdriver.promise.Resolver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Scheduler ()](#apidoc.element.selenium-webdriver.promise.Scheduler)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Thenable (new: Thenable, ...?)](#apidoc.element.selenium-webdriver.promise.Thenable)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>all (arr)](#apidoc.element.selenium-webdriver.promise.all)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>asap (value, callback, opt_errback)](#apidoc.element.selenium-webdriver.promise.asap)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>captureStackTrace (name, msg, opt_topFn)](#apidoc.element.selenium-webdriver.promise.captureStackTrace)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>checkedNodeCall (fn, var_args)](#apidoc.element.selenium-webdriver.promise.checkedNodeCall)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>consume (generatorFn, opt_self, ...var_args)](#apidoc.element.selenium-webdriver.promise.consume)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>controlFlow ()](#apidoc.element.selenium-webdriver.promise.controlFlow)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>createFlow (callback)](#apidoc.element.selenium-webdriver.promise.createFlow)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>createPromise (resolver)](#apidoc.element.selenium-webdriver.promise.createPromise)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>defer ()](#apidoc.element.selenium-webdriver.promise.defer)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>delayed (ms)](#apidoc.element.selenium-webdriver.promise.delayed)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>filter (arr, fn, opt_self)](#apidoc.element.selenium-webdriver.promise.filter)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>finally (promise, callback)](#apidoc.element.selenium-webdriver.promise.finally)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>fulfilled (opt_value)](#apidoc.element.selenium-webdriver.promise.fulfilled)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>fullyResolved (value)](#apidoc.element.selenium-webdriver.promise.fullyResolved)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>isGenerator (fn)](#apidoc.element.selenium-webdriver.promise.isGenerator)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>isPromise (value)](#apidoc.element.selenium-webdriver.promise.isPromise)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>map (arr, fn, opt_self)](#apidoc.element.selenium-webdriver.promise.map)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>rejected (opt_reason)](#apidoc.element.selenium-webdriver.promise.rejected)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>setDefaultFlow (flow)](#apidoc.element.selenium-webdriver.promise.setDefaultFlow)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>when (value, opt_callback, opt_errback)](#apidoc.element.selenium-webdriver.promise.when)

#### [module selenium-webdriver.proxy](#apidoc.module.selenium-webdriver.proxy)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>direct ()](#apidoc.element.selenium-webdriver.proxy.direct)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>manual (options)](#apidoc.element.selenium-webdriver.proxy.manual)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>pac (url)](#apidoc.element.selenium-webdriver.proxy.pac)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>socks (host, username, password)](#apidoc.element.selenium-webdriver.proxy.socks)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>system ()](#apidoc.element.selenium-webdriver.proxy.system)

#### [module selenium-webdriver.safari](#apidoc.module.selenium-webdriver.safari)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.safari.</span>Driver (Options|Capabilities)](#apidoc.element.selenium-webdriver.safari.Driver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.safari.</span>Options ()](#apidoc.element.selenium-webdriver.safari.Options)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.safari.</span>ServiceBuilder (opt_exe)](#apidoc.element.selenium-webdriver.safari.ServiceBuilder)

#### [module selenium-webdriver.session](#apidoc.module.selenium-webdriver.session)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.session.</span>Session (Object|Capabilities)](#apidoc.element.selenium-webdriver.session.Session)

#### [module selenium-webdriver.until](#apidoc.module.selenium-webdriver.until)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>ableToSwitchToFrame (frame)](#apidoc.element.selenium-webdriver.until.ableToSwitchToFrame)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>alertIsPresent ()](#apidoc.element.selenium-webdriver.until.alertIsPresent)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsDisabled (element)](#apidoc.element.selenium-webdriver.until.elementIsDisabled)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsEnabled (element)](#apidoc.element.selenium-webdriver.until.elementIsEnabled)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsNotSelected (element)](#apidoc.element.selenium-webdriver.until.elementIsNotSelected)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsNotVisible (element)](#apidoc.element.selenium-webdriver.until.elementIsNotVisible)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsSelected (element)](#apidoc.element.selenium-webdriver.until.elementIsSelected)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsVisible (element)](#apidoc.element.selenium-webdriver.until.elementIsVisible)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementLocated (locator)](#apidoc.element.selenium-webdriver.until.elementLocated)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementTextContains (element, substr)](#apidoc.element.selenium-webdriver.until.elementTextContains)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementTextIs (element, text)](#apidoc.element.selenium-webdriver.until.elementTextIs)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementTextMatches (element, regex)](#apidoc.element.selenium-webdriver.until.elementTextMatches)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementsLocated (locator)](#apidoc.element.selenium-webdriver.until.elementsLocated)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>stalenessOf (element)](#apidoc.element.selenium-webdriver.until.stalenessOf)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>titleContains (substr)](#apidoc.element.selenium-webdriver.until.titleContains)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>titleIs (title)](#apidoc.element.selenium-webdriver.until.titleIs)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>titleMatches (regex)](#apidoc.element.selenium-webdriver.until.titleMatches)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>urlContains (substrUrl)](#apidoc.element.selenium-webdriver.until.urlContains)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>urlIs (url)](#apidoc.element.selenium-webdriver.until.urlIs)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>urlMatches (regex)](#apidoc.element.selenium-webdriver.until.urlMatches)

#### [module selenium-webdriver.util](#apidoc.module.selenium-webdriver.util)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.util.</span>getStatus (url)](#apidoc.element.selenium-webdriver.util.getStatus)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.util.</span>waitForServer (url, timeout, opt_cancelToken)](#apidoc.element.selenium-webdriver.util.waitForServer)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.util.</span>waitForUrl (url, timeout, opt_cancelToken)](#apidoc.element.selenium-webdriver.util.waitForUrl)

#### [module selenium-webdriver.webdriver](#apidoc.module.selenium-webdriver.webdriver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Alert (driver, text)](#apidoc.element.selenium-webdriver.webdriver.Alert)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>AlertPromise (driver, alert)](#apidoc.element.selenium-webdriver.webdriver.AlertPromise)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Condition (!WebDriver)](#apidoc.element.selenium-webdriver.webdriver.Condition)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>IWebDriver ()](#apidoc.element.selenium-webdriver.webdriver.IWebDriver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Logs (driver)](#apidoc.element.selenium-webdriver.webdriver.Logs)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Navigation (driver)](#apidoc.element.selenium-webdriver.webdriver.Navigation)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Options (driver)](#apidoc.element.selenium-webdriver.webdriver.Options)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>TargetLocator (driver)](#apidoc.element.selenium-webdriver.webdriver.TargetLocator)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Timeouts (driver)](#apidoc.element.selenium-webdriver.webdriver.Timeouts)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>WebDriver (Session|IThenable<!Session>)](#apidoc.element.selenium-webdriver.webdriver.WebDriver)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>WebElement (!IThenable<string>|string)](#apidoc.element.selenium-webdriver.webdriver.WebElement)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>WebElementCondition (!WebDriver)](#apidoc.element.selenium-webdriver.webdriver.WebElementCondition)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>WebElementPromise (driver, el)](#apidoc.element.selenium-webdriver.webdriver.WebElementPromise)
1.  [function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Window (driver)](#apidoc.element.selenium-webdriver.webdriver.Window)



# <a name="apidoc.module.selenium-webdriver"></a>[module selenium-webdriver](#apidoc.module.selenium-webdriver)

#### <a name="apidoc.element.selenium-webdriver.ActionSequence"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>ActionSequence (driver)](#apidoc.element.selenium-webdriver.ActionSequence)
- description and source-code
```javascript
class ActionSequence {
<span class="apidocCodeCommentSpan">  /**
   * @param {!./webdriver.WebDriver} driver The driver that should be used to
   *     perform this action sequence.
   */
</span>  constructor(driver) {
    /** @private {!./webdriver.WebDriver} */
    this.driver_ = driver;

    /** @private {!Array<{description: string, command: !command.Command}>} */
    this.actions_ = [];
  }

  /**
   * Schedules an action to be executed each time {@link #perform} is called on
   * this instance.
   *
   * @param {string} description A description of the command.
   * @param {!command.Command} command The command.
   * @private
   */
  schedule_(description, command) {
    this.actions_.push({
      description: description,
      command: command
    });
  }

  /**
   * Executes this action sequence.
   *
   * @return {!./promise.Thenable} A promise that will be resolved once
   *     this sequence has completed.
   */
  perform() {
    // Make a protected copy of the scheduled actions. This will protect against
    // users defining additional commands before this sequence is actually
    // executed.
    let actions = this.actions_.concat();
    let driver = this.driver_;
    return driver.controlFlow().execute(function() {
      let results = actions.map(action => {
        return driver.schedule(action.command, action.description);
      });
      return Promise.all(results);
    }, 'ActionSequence.perform');
  }

  /**
   * Moves the mouse. The location to move to may be specified in terms of the
   * mouse's current location, an offset relative to the top-left corner of an
   * element, or an element (in which case the middle of the element is used).
   *
   * @param {(!./webdriver.WebElement|{x: number, y: number})} location The
   *     location to drag to, as either another WebElement or an offset in
   *     pixels.
   * @param {{x: number, y: number}=} opt_offset If the target {@code location}
   *     is defined as a {@link ./webdriver.WebElement}, this parameter defines
   *     an offset within that element. The offset should be specified in pixels
   *     relative to the top-left corner of the element's bounding box. If
   *     omitted, the element's center will be used as the target offset.
   * @return {!ActionSequence} A self reference.
   */
  mouseMove(location, opt_offset) {
    let cmd = new command.Command(command.Name.MOVE_TO);

    if (typeof location.x === 'number') {
      setOffset(/** @type {{x: number, y: number}} */(location));
    } else {
      cmd.setParameter('element', location.getId());
      if (opt_offset) {
        setOffset(opt_offset);
      }
    }

    this.schedule_('mouseMove', cmd);
    return this;

    /** @param {{x: number, y: number}} offset The offset to use. */
    function setOffset(offset) {
      cmd.setParameter('xoffset', offset.x || 0);
      cmd.setParameter('yoffset', offset.y || 0);
    }
  }

  /**
   * Schedules a mouse action.
   * @param {string} description A simple descriptive label for the scheduled
   *     action.
   * @param {!command.Name} commandName The name of the command.
   * @param {(./webdriver.WebElement|input.Button)=} opt_elementOrButton Either
   *     the element to interact with or the button to click with.
   *     Defaults to {@link input.Button.LEFT} if neither an element nor
   *     button is specified.
   * @param {input.Button=} opt_button The button to use. Defaults to
   *     {@link input.Button.LEFT}. Ignored if the previous argument is
   *     provided as a button.
   * @return {!ActionSequence} A self reference.
   * @private
   */
  scheduleMouseAction_(
      description, commandName, opt_elementOrButton, opt_button) {
    let button;
    if (typeof opt_elementOrButton === 'number') {
      button = opt_elementOrButton;
    } else {
      if (opt_elementOrButton) {
        this.mouseMove(
            /** @type {!./webdriver.WebElement} */ (opt_elementOrButton));
      }
      button = opt_button !== void(0) ? opt_button : input.Button.LEFT;
    }

    let cmd = new command.Command(commandName).
        setParameter('button', button);
    this.schedule_(de ...
```
- example usage
```shell
...
      return this.onQuit_.call(void 0);
    }
  }));
}

/** @override */
actions() {
  return new actions.ActionSequence(this);
}

/** @override */
touchActions() {
  return new actions.TouchSequence(this);
}
...
```

#### <a name="apidoc.element.selenium-webdriver.Builder"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>Builder ()](#apidoc.element.selenium-webdriver.Builder)
- description and source-code
```javascript
class Builder {
  constructor() {
<span class="apidocCodeCommentSpan">    /** @private @const */
</span>    this.log_ = logging.getLogger('webdriver.Builder');

    /** @private {promise.ControlFlow} */
    this.flow_ = null;

    /** @private {string} */
    this.url_ = '';

    /** @private {?string} */
    this.proxy_ = null;

    /** @private {!Capabilities} */
    this.capabilities_ = new Capabilities();

    /** @private {chrome.Options} */
    this.chromeOptions_ = null;

    /** @private {firefox.Options} */
    this.firefoxOptions_ = null;

    /** @private {opera.Options} */
    this.operaOptions_ = null;

    /** @private {ie.Options} */
    this.ieOptions_ = null;

    /** @private {safari.Options} */
    this.safariOptions_ = null;

    /** @private {edge.Options} */
    this.edgeOptions_ = null;

    /** @private {boolean} */
    this.ignoreEnv_ = false;

    /** @private {http.Agent} */
    this.agent_ = null;
  }

  /**
   * Configures this builder to ignore any environment variable overrides and to
   * only use the configuration specified through this instance's API.
   *
   * @return {!Builder} A self reference.
   */
  disableEnvironmentOverrides() {
    this.ignoreEnv_ = true;
    return this;
  }

  /**
   * Sets the URL of a remote WebDriver server to use. Once a remote URL has
   * been specified, the builder direct all new clients to that server. If this
   * method is never called, the Builder will attempt to create all clients
   * locally.
   *
   * As an alternative to this method, you may also set the
   * 'SELENIUM_REMOTE_URL' environment variable.
   *
   * @param {string} url The URL of a remote server to use.
   * @return {!Builder} A self reference.
   */
  usingServer(url) {
    this.url_ = url;
    return this;
  }

  /**
   * @return {string} The URL of the WebDriver server this instance is
   *     configured to use.
   */
  getServerUrl() {
    return this.url_;
  }

  /**
   * Sets the URL of the proxy to use for the WebDriver's HTTP connections.
   * If this method is never called, the Builder will create a connection
   * without a proxy.
   *
   * @param {string} proxy The URL of a proxy to use.
   * @return {!Builder} A self reference.
   */
  usingWebDriverProxy(proxy) {
    this.proxy_ = proxy;
    return this;
  }

  /**
   * @return {?string} The URL of the proxy server to use for the WebDriver's
   *    HTTP connections, or 'null' if not set.
   */
  getWebDriverProxy() {
    return this.proxy_;
  }

  /**
   * Sets the http agent to use for each request.
   * If this method is not called, the Builder will use http.globalAgent by default.
   *
   * @param {http.Agent} agent The agent to use for each request.
   * @return {!Builder} A self reference.
   */
  usingHttpAgent(agent) {
    this.agent_ = agent;
    return this;
  }

  /**
   * @return {http.Agent} The http agent used for each request
   */
  getHttpAgent() {
    return this.agent_;
  }

  /**
   * Sets the desired capabilities when requesting a new session. This will
   * overwrite any previously set capabilities.
   * @param {!(Object|Capabilities)} capabilities The desired capabilities for
   *     a new session.
   * @return {!Builder} A self reference.
   */
  withCapabilities(capabilities) {
    this.capabilities_ = new Capabilities(capabilities);
    return this;
  }

  /**
   * Returns the base set of capabilities this instance is currently configured
   * to use.
   * @return {!Capabilities} The current capabilities for this builder.
   */
  getCapabilities() {
    return this.capabilities_;
  }

  /**
   * Configures the target browser for clients created by this instance.
   * Any calls to {@link #withCapabilities} after this function will
   * overwrite these settings.
   *
   * You may also define the target browser using the {@code SELENIUM_BROWSER}
   * environment variable. If set, this environment variable should be of the
   * form 'browser[:[version][:platform]]'.
   *
   * @param {(string|Browser)} name The name of the target browser;
   *     common defaults are available on the {@link webdriver.Browser} enum.
   * @param {string=} o ...
```
- example usage
```shell
...
The sample below and others are included in the 'example' directory. You may
also find the tests for selenium-webdriver informative.

var webdriver = require('selenium-webdriver'),
    By = webdriver.By,
    until = webdriver.until;

var driver = new webdriver.Builder()
    .forBrowser('firefox')
    .build();

driver.get('http://www.google.com/ncr');
driver.findElement(By.name('q')).sendKeys('webdriver');
driver.findElement(By.name('btnG')).click();
driver.wait(until.titleIs('webdriver - Google Search'), 1000);
...
```

#### <a name="apidoc.element.selenium-webdriver.By"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>By (using, value)](#apidoc.element.selenium-webdriver.By)
- description and source-code
```javascript
class By {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} using the name of the location strategy to use.
   * @param {string} value the value to search for.
   */
</span>  constructor(using, value) {
    /** @type {string} */
    this.using = using;

    /** @type {string} */
    this.value = value;
  }

  /**
   * Locates elements that have a specific class name.
   *
   * @param {string} name The class name to search for.
   * @return {!By} The new locator.
   * @see http://www.w3.org/TR/2011/WD-html5-20110525/elements.html#classes
   * @see http://www.w3.org/TR/CSS2/selector.html#class-html
   */
  static className(name) {
    let names = name.split(/\s+/g)
        .filter(s => s.length > 0)
        .map(s => escapeCss(s));
    return By.css('.' + names.join('.'));
  }

  /**
   * Locates elements using a CSS selector.
   *
   * @param {string} selector The CSS selector to use.
   * @return {!By} The new locator.
   * @see http://www.w3.org/TR/CSS2/selector.html
   */
  static css(selector) {
    return new By('css selector', selector);
  }

  /**
   * Locates elements by the ID attribute. This locator uses the CSS selector
   * '*[id="$ID"]', _not_ 'document.getElementById'.
   *
   * @param {string} id The ID to search for.
   * @return {!By} The new locator.
   */
  static id(id) {
    return By.css('*[id="' + escapeCss(id) + '"]');
  }

  /**
   * Locates link elements whose
   * {@linkplain webdriver.WebElement#getText visible text} matches the given
   * string.
   *
   * @param {string} text The link text to search for.
   * @return {!By} The new locator.
   */
  static linkText(text) {
    return new By('link text', text);
  }

  /**
   * Locates an elements by evaluating a
   * {@linkplain webdriver.WebDriver#executeScript JavaScript expression}.
   * The result of this expression must be an element or list of elements.
   *
   * @param {!(string|Function)} script The script to execute.
   * @param {...*} var_args The arguments to pass to the script.
   * @return {function(!./webdriver.WebDriver): !./promise.Promise}
   *     A new JavaScript-based locator function.
   */
  static js(script, var_args) {
    let args = Array.prototype.slice.call(arguments, 0);
    return function(driver) {
      return driver.executeScript.apply(driver, args);
    };
  }

  /**
   * Locates elements whose 'name' attribute has the given value.
   *
   * @param {string} name The name attribute to search for.
   * @return {!By} The new locator.
   */
  static name(name) {
    return By.css('*[name="' + escapeCss(name) + '"]');
  }

  /**
   * Locates link elements whose
   * {@linkplain webdriver.WebElement#getText visible text} contains the given
   * substring.
   *
   * @param {string} text The substring to check for in a link's visible text.
   * @return {!By} The new locator.
   */
  static partialLinkText(text) {
    return new By('partial link text', text);
  }

  /**
   * Locates elements with a given tag name.
   *
   * @param {string} name The tag name to search for.
   * @return {!By} The new locator.
   * @deprecated Use {@link By.css() By.css(tagName)} instead.
   */
  static tagName(name) {
    return By.css(name);
  }

  /**
   * Locates elements matching a XPath selector. Care should be taken when
   * using an XPath selector with a {@link webdriver.WebElement} as WebDriver
   * will respect the context in the specified in the selector. For example,
   * given the selector '//div', WebDriver will search from the document root
   * regardless of whether the locator was used with a WebElement.
   *
   * @param {string} xpath The XPath selector to use.
   * @return {!By} The new locator.
   * @see http://www.w3.org/TR/xpath/
   */
  static xpath(xpath) {
    return new By('xpath', xpath);
  }

  /** @override */
  toString() {
    // The static By.name() overrides this.constructor.name.  Shame...
    return 'By(${this.using}, ${this.value})';
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.Capabilities"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>Capabilities (Capabilities|Map<string, ?>|Object)](#apidoc.element.selenium-webdriver.Capabilities)
- description and source-code
```javascript
class Capabilities extends Map {
<span class="apidocCodeCommentSpan">  /**
   * @param {(Capabilities|Map<string, ?>|Object)=} opt_other Another set of
   *     capabilities to initialize this instance from.
   */
</span>  constructor(opt_other) {
    if (opt_other && !(opt_other instanceof Map)) {
      opt_other = toMap(opt_other);
    }
    super(opt_other);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Android.
   */
  static android() {
    return new Capabilities()
        .set(Capability.BROWSER_NAME, Browser.ANDROID)
        .set(Capability.PLATFORM, 'ANDROID');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Chrome.
   */
  static chrome() {
    return new Capabilities().set(Capability.BROWSER_NAME, Browser.CHROME);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Microsoft Edge.
   */
  static edge() {
    return new Capabilities()
        .set(Capability.BROWSER_NAME, Browser.EDGE)
        .set(Capability.PLATFORM, 'WINDOWS');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Firefox.
   */
  static firefox() {
    return new Capabilities().set(Capability.BROWSER_NAME, Browser.FIREFOX);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Internet Explorer.
   */
  static ie() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.INTERNET_EXPLORER).
        set(Capability.PLATFORM, 'WINDOWS');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for iPad.
   */
  static ipad() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.IPAD).
        set(Capability.PLATFORM, 'MAC');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for iPhone.
   */
  static iphone() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.IPHONE).
        set(Capability.PLATFORM, 'MAC');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Opera.
   */
  static opera() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.OPERA);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for PhantomJS.
   */
  static phantomjs() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.PHANTOM_JS);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Safari.
   */
  static safari() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.SAFARI).
        set(Capability.PLATFORM, 'MAC');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for HTMLUnit.
   */
  static htmlunit() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.HTMLUNIT);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for HTMLUnit
   *     with enabled Javascript.
   */
  static htmlunitwithjs() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.HTMLUNIT).
        set(Capability.SUPPORTS_JAVASCRIPT, true);
  }

  /**
   * @return {!Object<string, ?>} The JSON representation of this instance.
   *     Note, the returned object may contain nested promised values.
   * @suppress {checkTypes} Suppress [] access on a struct (state inherited from
   *     Map).
   */
  [Symbols.serialize]() {
    return serialize(this);
  }

  /**
   * Merges another set of capabilities into this instance.
   * @param {!(Capabilities|Map<String, ?>|Object<string, ?>)} other The other
   *     set of capabilities to merge.
   * @return {!Capabilities} A self reference.
   */
  merge(other) {
    if (!other) {
      throw new TypeError('no capabilities provided for merge');
    }

    if (!(other instanceof Map)) {
      other = toMap(other);
    }

    for (let key of other.keys()) {
      this.set(key, other.get(key));
    }

    return this;
  }

  /**
   * @param {string} key The capability key.
   * @param {*} value The capability value.
   * @return {!Capabilities} A self reference.
   * @throws {TypeError} If the 'key' is not a string.
   * @override
   */
  set(key, value) {
    if (typeof key !== 'string') { ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.Condition"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>Condition (!WebDriver)](#apidoc.element.selenium-webdriver.Condition)
- description and source-code
```javascript
class Condition {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} message A descriptive error message. Should complete the
   *     sentence "Waiting [...]"
   * @param {function(!WebDriver): OUT} fn The condition function to
   *     evaluate on each iteration of the wait loop.
   */
</span>  constructor(message, fn) {
    /** @private {string} */
    this.description_ = 'Waiting ' + message;

    /** @type {function(!WebDriver): OUT} */
    this.fn = fn;
  }

  /** @return {string} A description of this condition. */
  description() {
    return this.description_;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.EventEmitter"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>EventEmitter (type, var_args)](#apidoc.element.selenium-webdriver.EventEmitter)
- description and source-code
```javascript
class EventEmitter {
<span class="apidocCodeCommentSpan">  /**
   * Fires an event and calls all listeners.
   * @param {string} type The type of event to emit.
   * @param {...*} var_args Any arguments to pass to each listener.
   */
</span>  emit(type, var_args) {
    let events = EVENTS.get(this);
    if (!events) {
      return;
    }

    let args = Array.prototype.slice.call(arguments, 1);

    let listeners = events.get(type);
    if (listeners) {
      for (let listener of listeners) {
        listener.fn.apply(listener.scope, args);
        if (listener.oneshot) {
          listeners.delete(listener);
        }
      }
    }
  }

  /**
   * Returns a mutable list of listeners for a specific type of event.
   * @param {string} type The type of event to retrieve the listeners for.
   * @return {!Set<!Listener>} The registered listeners for the given event
   *     type.
   */
  listeners(type) {
    let events = EVENTS.get(this);
    if (!events) {
      events = new Map;
      EVENTS.set(this, events);
    }

    let listeners = events.get(type);
    if (!listeners) {
      listeners = new Set;
      events.set(type, listeners);
    }
    return listeners;
  }

  /**
   * Registers a listener.
   * @param {string} type The type of event to listen for.
   * @param {!Function} fn The function to invoke when the event is fired.
   * @param {Object=} opt_self The object in whose scope to invoke the listener.
   * @param {boolean=} opt_oneshot Whether the listener should b (e removed after
   *    the first event is fired.
   * @return {!EventEmitter} A self reference.
   * @private
   */
  addListener_(type, fn, opt_self, opt_oneshot) {
    let listeners = this.listeners(type);
    for (let listener of listeners) {
      if (listener.fn === fn) {
        return this;
      }
    }
    listeners.add(new Listener(fn, opt_self || undefined, !!opt_oneshot));
    return this;
  }

  /**
   * Registers a listener.
   * @param {string} type The type of event to listen for.
   * @param {!Function} fn The function to invoke when the event is fired.
   * @param {Object=} opt_self The object in whose scope to invoke the listener.
   * @return {!EventEmitter} A self reference.
   */
  addListener(type, fn, opt_self) {
    return this.addListener_(type, fn, opt_self, false);
  }

  /**
   * Registers a one-time listener which will be called only the first time an
   * event is emitted, after which it will be removed.
   * @param {string} type The type of event to listen for.
   * @param {!Function} fn The function to invoke when the event is fired.
   * @param {Object=} opt_self The object in whose scope to invoke the listener.
   * @return {!EventEmitter} A self reference.
   */
  once(type, fn, opt_self) {
    return this.addListener_(type, fn, opt_self, true);
  }

  /**
   * An alias for {@link #addListener() addListener()}.
   * @param {string} type The type of event to listen for.
   * @param {!Function} fn The function to invoke when the event is fired.
   * @param {Object=} opt_self The object in whose scope to invoke the listener.
   * @return {!EventEmitter} A self reference.
   */
  on(type, fn, opt_self) {
    return this.addListener(type, fn, opt_self);
  }

  /**
   * Removes a previously registered event listener.
   * @param {string} type The type of event to unregister.
   * @param {!Function} listenerFn The handler function to remove.
   * @return {!EventEmitter} A self reference.
   */
  removeListener(type, listenerFn) {
    if (typeof type !== 'string' || typeof listenerFn !== 'function') {
      throw TypeError('invalid args: expected (string, function), got ('
          + (typeof type) + ', ' + (typeof listenerFn) + ')');
    }

    let events = EVENTS.get(this);
    if (!events) {
      return this;
    }

    let listeners = events.get(type);
    if (!listeners) {
      return this;
    }

    let match;
    for (let listener of listeners) {
      if (listener.fn === listenerFn) {
        match = listener;
        break;
      }
    }
    if (match) {
      listeners.delete(match);
      if (!listeners.size) {
        events.delete(type);
      } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.FileDetector"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>FileDetector (driver, path)](#apidoc.element.selenium-webdriver.FileDetector)
- description and source-code
```javascript
class FileDetector {

<span class="apidocCodeCommentSpan">  /**
   * Handles the file specified by the given path, preparing it for use with
   * the current browser. If the path does not refer to a valid file, it will
   * be returned unchanged, otherwise a path suitable for use with the current
   * browser will be returned.
   *
   * This default implementation is a no-op. Subtypes may override this function
   * for custom tailored file handling.
   *
   * @param {!./webdriver.WebDriver} driver The driver for the current browser.
   * @param {string} path The path to process.
   * @return {!Promise<string>} A promise for the processed file path.
   * @package
   */
</span>  handleFile(driver, path) {
    return Promise.resolve(path);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.Session"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>Session (Object|Capabilities)](#apidoc.element.selenium-webdriver.Session)
- description and source-code
```javascript
class Session {

<span class="apidocCodeCommentSpan">  /**
   * @param {string} id The session ID.
   * @param {!(Object|Capabilities)} capabilities The session
   *     capabilities.
   */
</span>  constructor(id, capabilities) {
    /** @private {string} */
    this.id_ = id;

    /** @private {!Capabilities} */
    this.caps_ = capabilities instanceof Capabilities
        ? /** @type {!Capabilities} */(capabilities)
        : new Capabilities(capabilities);
  }

  /**
   * @return {string} This session's ID.
   */
  getId() {
    return this.id_;
  }

  /**
   * @return {!Capabilities} This session's capabilities.
   */
  getCapabilities() {
    return this.caps_;
  }

  /**
   * Retrieves the value of a specific capability.
   * @param {string} key The capability to retrieve.
   * @return {*} The capability value.
   */
  getCapability(key) {
    return this.caps_.get(key);
  }

  /**
   * Returns the JSON representation of this object, which is just the string
   * session ID.
   * @return {string} The JSON representation of this Session.
   */
  toJSON() {
    return this.getId();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.ThenableWebDriver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>ThenableWebDriver (...args)](#apidoc.element.selenium-webdriver.ThenableWebDriver)
- description and source-code
```javascript
class ThenableWebDriver {
<span class="apidocCodeCommentSpan">  /** @param {...?} args */
</span>  static createSession(...args) {}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.TouchSequence"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>TouchSequence (driver)](#apidoc.element.selenium-webdriver.TouchSequence)
- description and source-code
```javascript
class TouchSequence {
<span class="apidocCodeCommentSpan">  /**
   * @param {!./webdriver.WebDriver} driver The driver that should be used to
   *     perform this action sequence.
   */
</span>  constructor(driver) {
    /** @private {!./webdriver.WebDriver} */
    this.driver_ = driver;

    /** @private {!Array<{description: string, command: !command.Command}>} */
    this.actions_ = [];
  }

  /**
   * Schedules an action to be executed each time {@link #perform} is called on
   * this instance.
   * @param {string} description A description of the command.
   * @param {!command.Command} command The command.
   * @private
   */
  schedule_(description, command) {
    this.actions_.push({
      description: description,
      command: command
    });
  }

  /**
   * Executes this action sequence.
   * @return {!./promise.Thenable} A promise that will be resolved once
   *     this sequence has completed.
   */
  perform() {
    // Make a protected copy of the scheduled actions. This will protect against
    // users defining additional commands before this sequence is actually
    // executed.
    let actions = this.actions_.concat();
    let driver = this.driver_;
    return driver.controlFlow().execute(function() {
      let results = actions.map(action => {
        return driver.schedule(action.command, action.description);
      });
      return Promise.all(results);
    }, 'TouchSequence.perform');
  }

  /**
   * Taps an element.
   *
   * @param {!./webdriver.WebElement} elem The element to tap.
   * @return {!TouchSequence} A self reference.
   */
  tap(elem) {
    let cmd = new command.Command(command.Name.TOUCH_SINGLE_TAP).
        setParameter('element', elem.getId());

    this.schedule_('tap', cmd);
    return this;
  }

  /**
   * Double taps an element.
   *
   * @param {!./webdriver.WebElement} elem The element to double tap.
   * @return {!TouchSequence} A self reference.
   */
  doubleTap(elem) {
    let cmd = new command.Command(command.Name.TOUCH_DOUBLE_TAP).
        setParameter('element', elem.getId());

    this.schedule_('doubleTap', cmd);
    return this;
  }

  /**
   * Long press on an element.
   *
   * @param {!./webdriver.WebElement} elem The element to long press.
   * @return {!TouchSequence} A self reference.
   */
  longPress(elem) {
    let cmd = new command.Command(command.Name.TOUCH_LONG_PRESS).
        setParameter('element', elem.getId());

    this.schedule_('longPress', cmd);
    return this;
  }

  /**
   * Touch down at the given location.
   *
   * @param {{x: number, y: number}} location The location to touch down at.
   * @return {!TouchSequence} A self reference.
   */
  tapAndHold(location) {
    let cmd = new command.Command(command.Name.TOUCH_DOWN).
        setParameter('x', location.x).
        setParameter('y', location.y);

    this.schedule_('tapAndHold', cmd);
    return this;
  }

  /**
   * Move a held {@linkplain #tapAndHold touch} to the specified location.
   *
   * @param {{x: number, y: number}} location The location to move to.
   * @return {!TouchSequence} A self reference.
   */
  move(location) {
    let cmd = new command.Command(command.Name.TOUCH_MOVE).
        setParameter('x', location.x).
        setParameter('y', location.y);

    this.schedule_('move', cmd);
    return this;
  }

  /**
   * Release a held {@linkplain #tapAndHold touch} at the specified location.
   *
   * @param {{x: number, y: number}} location The location to release at.
   * @return {!TouchSequence} A self reference.
   */
  release(location) {
    let cmd = new command.Command(command.Name.TOUCH_UP).
        setParameter('x', location.x).
        setParameter('y', location.y);

    this.schedule_('release', cmd);
    return this;
  }

  /**
   * Scrolls the touch screen by the given offset.
   *
   * @param {{x: number, y: number}} offset The offset to scroll to.
   * @return {!TouchSequence} A self reference.
   */
  scroll(offset) {
    let cmd = new command.Command(command.Name.TOUCH_SCROLL).
        setParameter('xoffset', offset.x).
        setParameter('yoffset', offset.y);

    this.schedule_('scroll', cmd); ...
```
- example usage
```shell
...
/** @override */
actions() {
  return new actions.ActionSequence(this);
}

/** @override */
touchActions() {
  return new actions.TouchSequence(this);
}

/** @override */
executeScript(script, var_args) {
  if (typeof script === 'function') {
    script = 'return (' + script + ').apply(null, arguments);';
  }
...
```

#### <a name="apidoc.element.selenium-webdriver.WebDriver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>WebDriver (Session|IThenable<!Session>)](#apidoc.element.selenium-webdriver.WebDriver)
- description and source-code
```javascript
class WebDriver {
<span class="apidocCodeCommentSpan">  /**
   * @param {!(Session|IThenable<!Session>)} session Either a known session or a
   *     promise that will be resolved to a session.
   * @param {!command.Executor} executor The executor to use when sending
   *     commands to the browser.
   * @param {promise.ControlFlow=} opt_flow The flow to
   *     schedule commands through. Defaults to the active flow object.
   * @param {(function(this: void): ?)=} opt_onQuit A function to call, if any,
   *     when the session is terminated.
   */
</span>  constructor(session, executor, opt_flow, opt_onQuit) {
    /** @private {!promise.ControlFlow} */
    this.flow_ = opt_flow || promise.controlFlow();

    /** @private {!promise.Thenable<!Session>} */
    this.session_ = this.flow_.promise(resolve => resolve(session));

    /** @private {!command.Executor} */
    this.executor_ = executor;

    /** @private {input.FileDetector} */
    this.fileDetector_ = null;

    /** @private @const {(function(this: void): ?|undefined)} */
    this.onQuit_ = opt_onQuit;
  }

  /**
   * Creates a new WebDriver client for an existing session.
   * @param {!command.Executor} executor Command executor to use when querying
   *     for session details.
   * @param {string} sessionId ID of the session to attach to.
   * @param {promise.ControlFlow=} opt_flow The control flow all
   *     driver commands should execute under. Defaults to the
   *     {@link promise.controlFlow() currently active}  control flow.
   * @return {!WebDriver} A new client for the specified session.
   */
  static attachToSession(executor, sessionId, opt_flow) {
    let flow = opt_flow || promise.controlFlow();
    let cmd = new command.Command(command.Name.DESCRIBE_SESSION)
        .setParameter('sessionId', sessionId);
    let session = flow.execute(
        () => executeCommand(executor, cmd).catch(err => {
          // The DESCRIBE_SESSION command is not supported by the W3C spec, so
          // if we get back an unknown command, just return a session with
          // unknown capabilities.
          if (err instanceof error.UnknownCommandError) {
            return new Session(sessionId, new Capabilities);
          }
          throw err;
        }),
        'WebDriver.attachToSession()');
    return new WebDriver(session, executor, flow);
  }

  /**
   * Creates a new WebDriver session.
   *
   * By default, the requested session 'capabilities' are merely "desired" and
   * the remote end will still create a new session even if it cannot satisfy
   * all of the requested capabilities. You can query which capabilities a
   * session actually has using the
   * {@linkplain #getCapabilities() getCapabilities()} method on the returned
   * WebDriver instance.
   *
   * To define _required capabilities_, provide the 'capabilities' as an object
   * literal with 'required' and 'desired' keys. The 'desired' key may be
   * omitted if all capabilities are required, and vice versa. If the server
   * cannot create a session with all of the required capabilities, it will
   * return an {@linkplain error.SessionNotCreatedError}.
   *
   *     let required = new Capabilities().set('browserName', 'firefox');
   *     let desired = new Capabilities().set('version', '45');
   *     let driver = WebDriver.createSession(executor, {required, desired});
   *
   * This function will always return a WebDriver instance. If there is an error
   * creating the session, such as the aforementioned SessionNotCreatedError,
   * the driver will have a rejected {@linkplain #getSession session} promise.
   * It is recommended that this promise is left _unhandled_ so it will
   * propagate through the {@linkplain promise.ControlFlow control flow} and
   * cause subsequent commands to fail.
   *
   *     let required = Capabilities.firefox();
   *     let driver = WebDriver.createSession(executor, {required});
   *
   *     // If the createSession operation failed, then this command will also
   *     // also fail, propagating the creation failure.
   *     driver.get('http://www.google.com').catch(e => console.log(e));
   * ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.WebElement"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>WebElement (!IThenable<string>|string)](#apidoc.element.selenium-webdriver.WebElement)
- description and source-code
```javascript
class WebElement {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver the parent WebDriver instance for this element.
   * @param {(!IThenable<string>|string)} id The server-assigned opaque ID for
   *     the underlying DOM element.
   */
</span>  constructor(driver, id) {
    /** @private {!WebDriver} */
    this.driver_ = driver;

    /** @private {!promise.Thenable<string>} */
    this.id_ = driver.controlFlow().promise(resolve => resolve(id));
  }

  /**
   * @param {string} id The raw ID.
   * @param {boolean=} opt_noLegacy Whether to exclude the legacy element key.
   * @return {!Object} The element ID for use with WebDriver's wire protocol.
   */
  static buildId(id, opt_noLegacy) {
    return opt_noLegacy
        ? {[ELEMENT_ID_KEY]: id}
        : {[ELEMENT_ID_KEY]: id, [LEGACY_ELEMENT_ID_KEY]: id};
  }

  /**
   * Extracts the encoded WebElement ID from the object.
   *
   * @param {?} obj The object to extract the ID from.
   * @return {string} the extracted ID.
   * @throws {TypeError} if the object is not a valid encoded ID.
   */
  static extractId(obj) {
    if (obj && typeof obj === 'object') {
      if (typeof obj[ELEMENT_ID_KEY] === 'string') {
        return obj[ELEMENT_ID_KEY];
      } else if (typeof obj[LEGACY_ELEMENT_ID_KEY] === 'string') {
        return obj[LEGACY_ELEMENT_ID_KEY];
      }
    }
    throw new TypeError('object is not a WebElement ID');
  }

  /**
   * @param {?} obj the object to test.
   * @return {boolean} whether the object is a valid encoded WebElement ID.
   */
  static isId(obj) {
    return obj && typeof obj === 'object'
        && (typeof obj[ELEMENT_ID_KEY] === 'string'
            || typeof obj[LEGACY_ELEMENT_ID_KEY] === 'string');
  }

  /**
   * Compares two WebElements for equality.
   *
   * @param {!WebElement} a A WebElement.
   * @param {!WebElement} b A WebElement.
   * @return {!promise.Thenable<boolean>} A promise that will be
   *     resolved to whether the two WebElements are equal.
   */
  static equals(a, b) {
    if (a === b) {
      return a.driver_.controlFlow().promise(resolve => resolve(true));
    }
    let ids = [a.getId(), b.getId()];
    return promise.all(ids).then(function(ids) {
      // If the two element's have the same ID, they should be considered
      // equal. Otherwise, they may still be equivalent, but we'll need to
      // ask the server to check for us.
      if (ids[0] === ids[1]) {
        return true;
      }

      let cmd = new command.Command(command.Name.ELEMENT_EQUALS);
      cmd.setParameter('id', ids[0]);
      cmd.setParameter('other', ids[1]);
      return a.driver_.schedule(cmd, 'WebElement.equals()');
    });
  }

  /** @return {!WebDriver} The parent driver for this instance. */
  getDriver() {
    return this.driver_;
  }

  /**
   * @return {!promise.Thenable<string>} A promise that resolves to
   *     the server-assigned opaque ID assigned to this element.
   */
  getId() {
    return this.id_;
  }

  /**
   * @return {!Object} Returns the serialized representation of this WebElement.
   */
  [Symbols.serialize]() {
    return this.getId().then(WebElement.buildId);
  }

  /**
   * Schedules a command that targets this element with the parent WebDriver
   * instance. Will ensure this element's ID is included in the command
   * parameters under the "id" key.
   *
   * @param {!command.Command} command The command to schedule.
   * @param {string} description A description of the command for debugging.
   * @return {!promise.Thenable<T>} A promise that will be resolved
   *     with the command result.
   * @template T
   * @see WebDriver#schedule
   * @private
   */
  schedule_(command, description) {
    command.setParameter('id', this);
    return this.driver_.schedule(command, description);
  }

  /**
   * Schedule a command to find a descendant of this element. If the element
   * cannot be found, the returned promise will be rejected with a
   * {@linkplain error.NoSuchElementError NoSuchElementError}.
   *
   * The search criteria for an element may be defined using one of the static
   * factories on the {@link by.By} class, or ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.WebElementCondition"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>WebElementCondition (!WebDriver)](#apidoc.element.selenium-webdriver.WebElementCondition)
- description and source-code
```javascript
class WebElementCondition extends Condition {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} message A descriptive error message. Should complete the
   *     sentence "Waiting [...]"
   * @param {function(!WebDriver): !(WebElement|IThenable<!WebElement>)}
   *     fn The condition function to evaluate on each iteration of the wait
   *     loop.
   */
</span>  constructor(message, fn) {
    super(message, fn);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.WebElementPromise"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>WebElementPromise (driver, el)](#apidoc.element.selenium-webdriver.WebElementPromise)
- description and source-code
```javascript
class WebElementPromise extends WebElement {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The parent WebDriver instance for this
   *     element.
   * @param {!promise.Thenable<!WebElement>} el A promise
   *     that will resolve to the promised element.
   */
</span>  constructor(driver, el) {
    super(driver, 'unused');

    /**
     * Cancel operation is only supported if the wrapped thenable is also
     * cancellable.
     * @param {(string|Error)=} opt_reason
     * @override
     */
    this.cancel = function(opt_reason) {
      if (promise.CancellableThenable.isImplementation(el)) {
        /** @type {!promise.CancellableThenable} */(el).cancel(opt_reason);
      }
    };

    /** @override */
    this.then = el.then.bind(el);

    /** @override */
    this.catch = el.catch.bind(el);

    /**
     * Defers returning the element ID until the wrapped WebElement has been
     * resolved.
     * @override
     */
    this.getId = function() {
      return el.then(function(el) {
        return el.getId();
      });
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.assert"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>assert (value)](#apidoc.element.selenium-webdriver.assert)
- description and source-code
```javascript
function assertThat(value) {
  return new Assertion(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.exec"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>exec (command, opt_options)](#apidoc.element.selenium-webdriver.exec)
- description and source-code
```javascript
function exec(command, opt_options) {
  var options = opt_options || {};

  var proc = childProcess.spawn(command, options.args || [], {
    env: options.env || process.env,
    stdio: options.stdio || 'ignore'
  });

  // This process should not wait on the spawned child, however, we do
  // want to ensure the child is killed when this process exits.
  proc.unref();
  process.once('exit', onProcessExit);

  let result = new Promise(resolve => {
    proc.once('exit', (code, signal) => {
      proc = null;
      process.removeListener('exit', onProcessExit);
      resolve(new Result(code, signal));
    });
  });
  return new Command(result, killCommand);

  function onProcessExit() {
    killCommand('SIGTERM');
  }

  function killCommand(signal) {
    process.removeListener('exit', onProcessExit);
    if (proc) {
      proc.kill(signal);
      proc = null;
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.Key"></a>[module selenium-webdriver.Key](#apidoc.module.selenium-webdriver.Key)

#### <a name="apidoc.element.selenium-webdriver.Key.chord"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.Key.</span>chord (var_args)](#apidoc.element.selenium-webdriver.Key.chord)
- description and source-code
```javascript
chord = function (var_args) {
  return Array.prototype.slice.call(arguments, 0).join('') + Key.NULL;
}
```
- example usage
```shell
...
*   simulate common keyboard shortcuts:
*
*         element.sendKeys("text was",
*                          Key.CONTROL, "a", Key.NULL,
*                          "now text is");
*         // Alternatively:
*         element.sendKeys("text was",
*                          Key.chord(Key.CONTROL, "a"),
*                          "now text is");
*
* - The end of the key sequence is encountered. When there are no more keys
*   to type, all depressed modifier keys are released (with accompanying
*   keyup events).
*
* If this element is a file input ({@code <input type="file">}), the
...
```



# <a name="apidoc.module.selenium-webdriver.actions"></a>[module selenium-webdriver.actions](#apidoc.module.selenium-webdriver.actions)

#### <a name="apidoc.element.selenium-webdriver.actions.ActionSequence"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.actions.</span>ActionSequence (driver)](#apidoc.element.selenium-webdriver.actions.ActionSequence)
- description and source-code
```javascript
class ActionSequence {
<span class="apidocCodeCommentSpan">  /**
   * @param {!./webdriver.WebDriver} driver The driver that should be used to
   *     perform this action sequence.
   */
</span>  constructor(driver) {
    /** @private {!./webdriver.WebDriver} */
    this.driver_ = driver;

    /** @private {!Array<{description: string, command: !command.Command}>} */
    this.actions_ = [];
  }

  /**
   * Schedules an action to be executed each time {@link #perform} is called on
   * this instance.
   *
   * @param {string} description A description of the command.
   * @param {!command.Command} command The command.
   * @private
   */
  schedule_(description, command) {
    this.actions_.push({
      description: description,
      command: command
    });
  }

  /**
   * Executes this action sequence.
   *
   * @return {!./promise.Thenable} A promise that will be resolved once
   *     this sequence has completed.
   */
  perform() {
    // Make a protected copy of the scheduled actions. This will protect against
    // users defining additional commands before this sequence is actually
    // executed.
    let actions = this.actions_.concat();
    let driver = this.driver_;
    return driver.controlFlow().execute(function() {
      let results = actions.map(action => {
        return driver.schedule(action.command, action.description);
      });
      return Promise.all(results);
    }, 'ActionSequence.perform');
  }

  /**
   * Moves the mouse. The location to move to may be specified in terms of the
   * mouse's current location, an offset relative to the top-left corner of an
   * element, or an element (in which case the middle of the element is used).
   *
   * @param {(!./webdriver.WebElement|{x: number, y: number})} location The
   *     location to drag to, as either another WebElement or an offset in
   *     pixels.
   * @param {{x: number, y: number}=} opt_offset If the target {@code location}
   *     is defined as a {@link ./webdriver.WebElement}, this parameter defines
   *     an offset within that element. The offset should be specified in pixels
   *     relative to the top-left corner of the element's bounding box. If
   *     omitted, the element's center will be used as the target offset.
   * @return {!ActionSequence} A self reference.
   */
  mouseMove(location, opt_offset) {
    let cmd = new command.Command(command.Name.MOVE_TO);

    if (typeof location.x === 'number') {
      setOffset(/** @type {{x: number, y: number}} */(location));
    } else {
      cmd.setParameter('element', location.getId());
      if (opt_offset) {
        setOffset(opt_offset);
      }
    }

    this.schedule_('mouseMove', cmd);
    return this;

    /** @param {{x: number, y: number}} offset The offset to use. */
    function setOffset(offset) {
      cmd.setParameter('xoffset', offset.x || 0);
      cmd.setParameter('yoffset', offset.y || 0);
    }
  }

  /**
   * Schedules a mouse action.
   * @param {string} description A simple descriptive label for the scheduled
   *     action.
   * @param {!command.Name} commandName The name of the command.
   * @param {(./webdriver.WebElement|input.Button)=} opt_elementOrButton Either
   *     the element to interact with or the button to click with.
   *     Defaults to {@link input.Button.LEFT} if neither an element nor
   *     button is specified.
   * @param {input.Button=} opt_button The button to use. Defaults to
   *     {@link input.Button.LEFT}. Ignored if the previous argument is
   *     provided as a button.
   * @return {!ActionSequence} A self reference.
   * @private
   */
  scheduleMouseAction_(
      description, commandName, opt_elementOrButton, opt_button) {
    let button;
    if (typeof opt_elementOrButton === 'number') {
      button = opt_elementOrButton;
    } else {
      if (opt_elementOrButton) {
        this.mouseMove(
            /** @type {!./webdriver.WebElement} */ (opt_elementOrButton));
      }
      button = opt_button !== void(0) ? opt_button : input.Button.LEFT;
    }

    let cmd = new command.Command(commandName).
        setParameter('button', button);
    this.schedule_(de ...
```
- example usage
```shell
...
      return this.onQuit_.call(void 0);
    }
  }));
}

/** @override */
actions() {
  return new actions.ActionSequence(this);
}

/** @override */
touchActions() {
  return new actions.TouchSequence(this);
}
...
```

#### <a name="apidoc.element.selenium-webdriver.actions.TouchSequence"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.actions.</span>TouchSequence (driver)](#apidoc.element.selenium-webdriver.actions.TouchSequence)
- description and source-code
```javascript
class TouchSequence {
<span class="apidocCodeCommentSpan">  /**
   * @param {!./webdriver.WebDriver} driver The driver that should be used to
   *     perform this action sequence.
   */
</span>  constructor(driver) {
    /** @private {!./webdriver.WebDriver} */
    this.driver_ = driver;

    /** @private {!Array<{description: string, command: !command.Command}>} */
    this.actions_ = [];
  }

  /**
   * Schedules an action to be executed each time {@link #perform} is called on
   * this instance.
   * @param {string} description A description of the command.
   * @param {!command.Command} command The command.
   * @private
   */
  schedule_(description, command) {
    this.actions_.push({
      description: description,
      command: command
    });
  }

  /**
   * Executes this action sequence.
   * @return {!./promise.Thenable} A promise that will be resolved once
   *     this sequence has completed.
   */
  perform() {
    // Make a protected copy of the scheduled actions. This will protect against
    // users defining additional commands before this sequence is actually
    // executed.
    let actions = this.actions_.concat();
    let driver = this.driver_;
    return driver.controlFlow().execute(function() {
      let results = actions.map(action => {
        return driver.schedule(action.command, action.description);
      });
      return Promise.all(results);
    }, 'TouchSequence.perform');
  }

  /**
   * Taps an element.
   *
   * @param {!./webdriver.WebElement} elem The element to tap.
   * @return {!TouchSequence} A self reference.
   */
  tap(elem) {
    let cmd = new command.Command(command.Name.TOUCH_SINGLE_TAP).
        setParameter('element', elem.getId());

    this.schedule_('tap', cmd);
    return this;
  }

  /**
   * Double taps an element.
   *
   * @param {!./webdriver.WebElement} elem The element to double tap.
   * @return {!TouchSequence} A self reference.
   */
  doubleTap(elem) {
    let cmd = new command.Command(command.Name.TOUCH_DOUBLE_TAP).
        setParameter('element', elem.getId());

    this.schedule_('doubleTap', cmd);
    return this;
  }

  /**
   * Long press on an element.
   *
   * @param {!./webdriver.WebElement} elem The element to long press.
   * @return {!TouchSequence} A self reference.
   */
  longPress(elem) {
    let cmd = new command.Command(command.Name.TOUCH_LONG_PRESS).
        setParameter('element', elem.getId());

    this.schedule_('longPress', cmd);
    return this;
  }

  /**
   * Touch down at the given location.
   *
   * @param {{x: number, y: number}} location The location to touch down at.
   * @return {!TouchSequence} A self reference.
   */
  tapAndHold(location) {
    let cmd = new command.Command(command.Name.TOUCH_DOWN).
        setParameter('x', location.x).
        setParameter('y', location.y);

    this.schedule_('tapAndHold', cmd);
    return this;
  }

  /**
   * Move a held {@linkplain #tapAndHold touch} to the specified location.
   *
   * @param {{x: number, y: number}} location The location to move to.
   * @return {!TouchSequence} A self reference.
   */
  move(location) {
    let cmd = new command.Command(command.Name.TOUCH_MOVE).
        setParameter('x', location.x).
        setParameter('y', location.y);

    this.schedule_('move', cmd);
    return this;
  }

  /**
   * Release a held {@linkplain #tapAndHold touch} at the specified location.
   *
   * @param {{x: number, y: number}} location The location to release at.
   * @return {!TouchSequence} A self reference.
   */
  release(location) {
    let cmd = new command.Command(command.Name.TOUCH_UP).
        setParameter('x', location.x).
        setParameter('y', location.y);

    this.schedule_('release', cmd);
    return this;
  }

  /**
   * Scrolls the touch screen by the given offset.
   *
   * @param {{x: number, y: number}} offset The offset to scroll to.
   * @return {!TouchSequence} A self reference.
   */
  scroll(offset) {
    let cmd = new command.Command(command.Name.TOUCH_SCROLL).
        setParameter('xoffset', offset.x).
        setParameter('yoffset', offset.y);

    this.schedule_('scroll', cmd); ...
```
- example usage
```shell
...
/** @override */
actions() {
  return new actions.ActionSequence(this);
}

/** @override */
touchActions() {
  return new actions.TouchSequence(this);
}

/** @override */
executeScript(script, var_args) {
  if (typeof script === 'function') {
    script = 'return (' + script + ').apply(null, arguments);';
  }
...
```



# <a name="apidoc.module.selenium-webdriver.assert"></a>[module selenium-webdriver.assert](#apidoc.module.selenium-webdriver.assert)

#### <a name="apidoc.element.selenium-webdriver.assert.assert"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>assert (value)](#apidoc.element.selenium-webdriver.assert.assert)
- description and source-code
```javascript
function assertThat(value) {
  return new Assertion(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.assert.Assertion"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.assert.</span>Assertion (subject, opt_invert)](#apidoc.element.selenium-webdriver.assert.Assertion)
- description and source-code
```javascript
class Assertion {
<span class="apidocCodeCommentSpan">  /**
   * @param {?} subject The subject of this assertion.
   * @param {boolean=} opt_invert Whether to invert any assertions performed by
   *     this instance.
   */
</span>  constructor(subject, opt_invert) {
    /** @private {?} */
    this.subject_ = subject;
    /** @private {boolean} */
    this.invert_ = !!opt_invert;
  }

  /**
   * @param {number} expected The minimum permissible value (inclusive).
   * @param {string=} opt_message An optional failure message.
   * @return {(Promise|undefined)} The result of this assertion, if the subject
   *     is a promised-value. Otherwise, the assertion is performed immediately
   *     and nothing is returned.
   */
  atLeast(expected, opt_message) {
    checkNumber(expected);
    return evaluate(this.subject_, function(actual) {
      if (!isNumber(actual) || actual < expected) {
        assert.fail(actual, expected, opt_message, '>=');
      }
    });
  }

  /**
   * @param {number} expected The maximum permissible value (inclusive).
   * @param {string=} opt_message An optional failure message.
   * @return {(Promise|undefined)} The result of this assertion, if the subject
   *     is a promised-value. Otherwise, the assertion is performed immediately
   *     and nothing is returned.
   */
  atMost(expected, opt_message) {
    checkNumber(expected);
    return evaluate(this.subject_, function (actual) {
      if (!isNumber(actual) || actual > expected) {
        assert.fail(actual, expected, opt_message, '<=');
      }
    });
  }

  /**
   * @param {number} expected The maximum permissible value (exclusive).
   * @param {string=} opt_message An optional failure message.
   * @return {(Promise|undefined)} The result of this assertion, if the subject
   *     is a promised-value. Otherwise, the assertion is performed immediately
   *     and nothing is returned.
   */
  greaterThan(expected, opt_message) {
    checkNumber(expected);
    return evaluate(this.subject_, function(actual) {
      if (!isNumber(actual) || actual <= expected) {
        assert.fail(actual, expected, opt_message, '>');
      }
    });
  }

  /**
   * @param {number} expected The minimum permissible value (exclusive).
   * @param {string=} opt_message An optional failure message.
   * @return {(Promise|undefined)} The result of this assertion, if the subject
   *     is a promised-value. Otherwise, the assertion is performed immediately
   *     and nothing is returned.
   */
  lessThan(expected, opt_message) {
    checkNumber(expected);
    return evaluate(this.subject_,  function (actual) {
      if (!isNumber(actual) || actual >= expected) {
        assert.fail(actual, expected, opt_message, '<');
      }
    });
  }

  /**
   * @param {number} expected The desired value.
   * @param {number} epsilon The maximum distance from the desired value.
   * @param {string=} opt_message An optional failure message.
   * @return {(Promise|undefined)} The result of this assertion, if the subject
   *     is a promised-value. Otherwise, the assertion is performed immediately
   *     and nothing is returned.
   */
  closeTo(expected, epsilon, opt_message) {
    checkNumber(expected);
    checkNumber(epsilon);
    return evaluate(this.subject_, function(actual) {
      checkNumber(actual);
      if (Math.abs(expected - actual) > epsilon) {
        assert.fail(opt_message || '${actual} === ${expected} (± ${epsilon})');
      }
    });
  }

  /**
   * @param {function(new: ?)} ctor The exptected type's constructor.
   * @param {string=} opt_message An optional failure message.
   * @return {(Promise|undefined)} The result of this assertion, if the subject
   *     is a promised-value. Otherwise, the assertion is performed immediately
   *     and nothing is returned.
   */
  instanceOf(ctor, opt_message) {
    checkFunction(ctor);
    return evaluate(this.subject_, function(actual) {
      if (!(actual instanceof ctor)) {
        assert.fail(
            opt_message
                || '${describe(actual)} instanceof ${ctor.name || ctor}');
      }
    });
  }

  /**
   * @param {string=} opt_ ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.binary"></a>[module selenium-webdriver.binary](#apidoc.module.selenium-webdriver.binary)

#### <a name="apidoc.element.selenium-webdriver.binary.Binary"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.binary.</span>Binary (string|Channel)](#apidoc.element.selenium-webdriver.binary.Binary)
- description and source-code
```javascript
class Binary {
<span class="apidocCodeCommentSpan">  /**
   * @param {?(string|Channel)=} opt_exeOrChannel Either the path to a specific
   *     Firefox binary to use, or a {@link Channel} instance that describes
   *     how to locate the desired Firefox version.
   */
</span>  constructor(opt_exeOrChannel) {
    /** @private {?(string|Channel)} */
    this.exe_ = opt_exeOrChannel || null;

    /** @private {!Array.<string>} */
    this.args_ = [];

    /** @private {!Object<string, string>} */
    this.env_ = {};
    Object.assign(this.env_, process.env, {
      MOZ_CRASHREPORTER_DISABLE: '1',
      MOZ_NO_REMOTE: '1',
      NO_EM_RESTART: '1'
    });

    /** @private {boolean} */
    this.devEdition_ = false;
  }

  /**
   * @return {(string|undefined)} The path to the Firefox executable to use, or
   *     'undefined' if WebDriver should attempt to locate Firefox automatically
   *     on the current system.
   */
  getExe() {
    return typeof this.exe_ === 'string' ? this.exe_ : undefined;
  }

  /**
   * Add arguments to the command line used to start Firefox.
   * @param {...(string|!Array.<string>)} var_args Either the arguments to add
   *     as varargs, or the arguments as an array.
   */
  addArguments(var_args) {
    for (var i = 0; i < arguments.length; i++) {
      if (Array.isArray(arguments[i])) {
        this.args_ = this.args_.concat(arguments[i]);
      } else {
        this.args_.push(arguments[i]);
      }
    }
  }

  /**
   * @return {!Array<string>} The command line arguments to use when starting
   *     the browser.
   */
  getArguments() {
    return this.args_;
  }

  /**
   * Specifies whether to use Firefox Developer Edition instead of the normal
   * stable channel. Setting this option has no effect if this instance was
   * created with a path to a specific Firefox binary.
   *
   * This method has no effect on Unix systems where the Firefox application
   * has the same (default) name regardless of version.
   *
   * @param {boolean=} opt_use Whether to use the developer edition. Defaults to
   *     true.
   * @deprecated Use the {@link Channel} class to indicate the desired Firefox
   *     version when creating a new binary: 'new Binary(Channel.AURORA)'.
   */
  useDevEdition(opt_use) {
    this.devEdition_ = opt_use === undefined || !!opt_use;
  }

  /**
   * Returns a promise for the Firefox executable used by this instance. The
   * returned promise will be immediately resolved if the user supplied an
   * executable path when this instance was created. Otherwise, an attempt will
   * be made to find Firefox on the current system.
   *
   * @return {!Promise<string>} a promise for the path to the Firefox executable
   *     used by this instance.
   */
  locate() {
    if (typeof this.exe_ === 'string') {
      return Promise.resolve(this.exe_);
    } else if (this.exe_ instanceof Channel) {
      return this.exe_.locate();
    }
    let channel = this.devEdition_ ? Channel.AURORA : Channel.RELEASE;
    return channel.locate();
  }

  /**
   * Launches Firefox and returns a promise that will be fulfilled when the
   * process terminates.
   * @param {string} profile Path to the profile directory to use.
   * @return {!Promise<!exec.Command>} A promise for the handle to the started
   *     subprocess.
   */
  launch(profile) {
    let env = {};
    Object.assign(env, this.env_, {XRE_PROFILE_PATH: profile});

    let args = ['-foreground'].concat(this.args_);

    return this.locate().then(function(firefox) {
      if (process.platform === 'win32' || process.platform === 'darwin') {
        return exec(firefox, {args: args, env: env});
      }
      return installNoFocusLibs(profile).then(function(ldLibraryPath) {
        env['LD_LIBRARY_PATH'] = ldLibraryPath + ':' + env['LD_LIBRARY_PATH'];
        env['LD_PRELOAD'] = X_IGNORE_NO_FOCUS_LIB;
        return exec(firefox, {args: args, env: env});
      });
    });
  }

  /**
   * Returns a promise for the wire representation of this binary. Note: the
   * FirefoxDriver only supports passing the path to the binary executable over
   * the wire; all command line arguments and ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.binary.Channel"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.binary.</span>Channel (darwin, win32)](#apidoc.element.selenium-webdriver.binary.Channel)
- description and source-code
```javascript
class Channel {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} darwin The path to check when running on MacOS.
   * @param {string} win32 The path to check when running on Windows.
   */
</span>  constructor(darwin, win32) {
    /** @private @const */ this.darwin_ = darwin;
    /** @private @const */ this.win32_ = win32;
    /** @private {Promise<string>} */
    this.found_ = null;
  }

  /**
   * Attempts to locate the Firefox executable for this release channel. This
   * will first check the default installation location for the channel before
   * checking the user's PATH. The returned promise will be rejected if Firefox
   * can not be found.
   *
   * @return {!Promise<string>} A promise for the location of the located
   *     Firefox executable.
   */
  locate() {
    if (this.found_) {
      return this.found_;
    }

    let found;
    switch (process.platform) {
      case 'darwin':
        found = io.exists(this.darwin_)
            .then(exists => exists ? this.darwin_ : io.findInPath('firefox'));
        break;

      case 'win32':
        found = findInProgramFiles(this.win32_)
            .then(found => found || io.findInPath('firefox.exe'));
        break;

      default:
        found = Promise.resolve(io.findInPath('firefox'));
        break;
    }

    this.found_ = found.then(found => {
      if (found) {
        // TODO: verify version info.
        return found;
      }
      throw Error('Could not locate Firefox on the current system');
    });
    return this.found_;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.by"></a>[module selenium-webdriver.by](#apidoc.module.selenium-webdriver.by)

#### <a name="apidoc.element.selenium-webdriver.by.By"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.by.</span>By (using, value)](#apidoc.element.selenium-webdriver.by.By)
- description and source-code
```javascript
class By {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} using the name of the location strategy to use.
   * @param {string} value the value to search for.
   */
</span>  constructor(using, value) {
    /** @type {string} */
    this.using = using;

    /** @type {string} */
    this.value = value;
  }

  /**
   * Locates elements that have a specific class name.
   *
   * @param {string} name The class name to search for.
   * @return {!By} The new locator.
   * @see http://www.w3.org/TR/2011/WD-html5-20110525/elements.html#classes
   * @see http://www.w3.org/TR/CSS2/selector.html#class-html
   */
  static className(name) {
    let names = name.split(/\s+/g)
        .filter(s => s.length > 0)
        .map(s => escapeCss(s));
    return By.css('.' + names.join('.'));
  }

  /**
   * Locates elements using a CSS selector.
   *
   * @param {string} selector The CSS selector to use.
   * @return {!By} The new locator.
   * @see http://www.w3.org/TR/CSS2/selector.html
   */
  static css(selector) {
    return new By('css selector', selector);
  }

  /**
   * Locates elements by the ID attribute. This locator uses the CSS selector
   * '*[id="$ID"]', _not_ 'document.getElementById'.
   *
   * @param {string} id The ID to search for.
   * @return {!By} The new locator.
   */
  static id(id) {
    return By.css('*[id="' + escapeCss(id) + '"]');
  }

  /**
   * Locates link elements whose
   * {@linkplain webdriver.WebElement#getText visible text} matches the given
   * string.
   *
   * @param {string} text The link text to search for.
   * @return {!By} The new locator.
   */
  static linkText(text) {
    return new By('link text', text);
  }

  /**
   * Locates an elements by evaluating a
   * {@linkplain webdriver.WebDriver#executeScript JavaScript expression}.
   * The result of this expression must be an element or list of elements.
   *
   * @param {!(string|Function)} script The script to execute.
   * @param {...*} var_args The arguments to pass to the script.
   * @return {function(!./webdriver.WebDriver): !./promise.Promise}
   *     A new JavaScript-based locator function.
   */
  static js(script, var_args) {
    let args = Array.prototype.slice.call(arguments, 0);
    return function(driver) {
      return driver.executeScript.apply(driver, args);
    };
  }

  /**
   * Locates elements whose 'name' attribute has the given value.
   *
   * @param {string} name The name attribute to search for.
   * @return {!By} The new locator.
   */
  static name(name) {
    return By.css('*[name="' + escapeCss(name) + '"]');
  }

  /**
   * Locates link elements whose
   * {@linkplain webdriver.WebElement#getText visible text} contains the given
   * substring.
   *
   * @param {string} text The substring to check for in a link's visible text.
   * @return {!By} The new locator.
   */
  static partialLinkText(text) {
    return new By('partial link text', text);
  }

  /**
   * Locates elements with a given tag name.
   *
   * @param {string} name The tag name to search for.
   * @return {!By} The new locator.
   * @deprecated Use {@link By.css() By.css(tagName)} instead.
   */
  static tagName(name) {
    return By.css(name);
  }

  /**
   * Locates elements matching a XPath selector. Care should be taken when
   * using an XPath selector with a {@link webdriver.WebElement} as WebDriver
   * will respect the context in the specified in the selector. For example,
   * given the selector '//div', WebDriver will search from the document root
   * regardless of whether the locator was used with a WebElement.
   *
   * @param {string} xpath The XPath selector to use.
   * @return {!By} The new locator.
   * @see http://www.w3.org/TR/xpath/
   */
  static xpath(xpath) {
    return new By('xpath', xpath);
  }

  /** @override */
  toString() {
    // The static By.name() overrides this.constructor.name.  Shame...
    return 'By(${this.using}, ${this.value})';
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.by.checkedLocator"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.by.</span>checkedLocator (locator)](#apidoc.element.selenium-webdriver.by.checkedLocator)
- description and source-code
```javascript
function check(locator) {
  if (locator instanceof By || typeof locator === 'function') {
    return locator;
  }
  for (let key in locator) {
    if (locator.hasOwnProperty(key) && By.hasOwnProperty(key)) {
      return By[key](locator[key]);
    }
  }
  throw new TypeError('Invalid locator');
}
```
- example usage
```shell
...
  return this.schedule(new command.Command(command.Name.GET_TITLE),
                       'WebDriver.getTitle()');
}

/** @override */
findElement(locator) {
  let id;
  locator = by.checkedLocator(locator);
  if (typeof locator === 'function') {
    id = this.findElementInternal_(locator, this);
  } else {
    let cmd = new command.Command(command.Name.FIND_ELEMENT).
        setParameter('using', locator.using).
        setParameter('value', locator.value);
    id = this.schedule(cmd, 'WebDriver.findElement(' + locator + ')');
...
```



# <a name="apidoc.module.selenium-webdriver.capabilities"></a>[module selenium-webdriver.capabilities](#apidoc.module.selenium-webdriver.capabilities)

#### <a name="apidoc.element.selenium-webdriver.capabilities.Capabilities"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.capabilities.</span>Capabilities (Capabilities|Map<string, ?>|Object)](#apidoc.element.selenium-webdriver.capabilities.Capabilities)
- description and source-code
```javascript
class Capabilities extends Map {
<span class="apidocCodeCommentSpan">  /**
   * @param {(Capabilities|Map<string, ?>|Object)=} opt_other Another set of
   *     capabilities to initialize this instance from.
   */
</span>  constructor(opt_other) {
    if (opt_other && !(opt_other instanceof Map)) {
      opt_other = toMap(opt_other);
    }
    super(opt_other);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Android.
   */
  static android() {
    return new Capabilities()
        .set(Capability.BROWSER_NAME, Browser.ANDROID)
        .set(Capability.PLATFORM, 'ANDROID');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Chrome.
   */
  static chrome() {
    return new Capabilities().set(Capability.BROWSER_NAME, Browser.CHROME);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Microsoft Edge.
   */
  static edge() {
    return new Capabilities()
        .set(Capability.BROWSER_NAME, Browser.EDGE)
        .set(Capability.PLATFORM, 'WINDOWS');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Firefox.
   */
  static firefox() {
    return new Capabilities().set(Capability.BROWSER_NAME, Browser.FIREFOX);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Internet Explorer.
   */
  static ie() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.INTERNET_EXPLORER).
        set(Capability.PLATFORM, 'WINDOWS');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for iPad.
   */
  static ipad() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.IPAD).
        set(Capability.PLATFORM, 'MAC');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for iPhone.
   */
  static iphone() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.IPHONE).
        set(Capability.PLATFORM, 'MAC');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Opera.
   */
  static opera() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.OPERA);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for PhantomJS.
   */
  static phantomjs() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.PHANTOM_JS);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for Safari.
   */
  static safari() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.SAFARI).
        set(Capability.PLATFORM, 'MAC');
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for HTMLUnit.
   */
  static htmlunit() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.HTMLUNIT);
  }

  /**
   * @return {!Capabilities} A basic set of capabilities for HTMLUnit
   *     with enabled Javascript.
   */
  static htmlunitwithjs() {
    return new Capabilities().
        set(Capability.BROWSER_NAME, Browser.HTMLUNIT).
        set(Capability.SUPPORTS_JAVASCRIPT, true);
  }

  /**
   * @return {!Object<string, ?>} The JSON representation of this instance.
   *     Note, the returned object may contain nested promised values.
   * @suppress {checkTypes} Suppress [] access on a struct (state inherited from
   *     Map).
   */
  [Symbols.serialize]() {
    return serialize(this);
  }

  /**
   * Merges another set of capabilities into this instance.
   * @param {!(Capabilities|Map<String, ?>|Object<string, ?>)} other The other
   *     set of capabilities to merge.
   * @return {!Capabilities} A self reference.
   */
  merge(other) {
    if (!other) {
      throw new TypeError('no capabilities provided for merge');
    }

    if (!(other instanceof Map)) {
      other = toMap(other);
    }

    for (let key of other.keys()) {
      this.set(key, other.get(key));
    }

    return this;
  }

  /**
   * @param {string} key The capability key.
   * @param {*} value The capability value.
   * @return {!Capabilities} A self reference.
   * @throws {TypeError} If the 'key' is not a string.
   * @override
   */
  set(key, value) {
    if (typeof key !== 'string') { ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.capabilities.ProxyConfig"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.capabilities.</span>ProxyConfig ()](#apidoc.element.selenium-webdriver.capabilities.ProxyConfig)
- description and source-code
```javascript
function ProxyConfig() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.chrome"></a>[module selenium-webdriver.chrome](#apidoc.module.selenium-webdriver.chrome)

#### <a name="apidoc.element.selenium-webdriver.chrome.Driver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>Driver (Capabilities|Options)](#apidoc.element.selenium-webdriver.chrome.Driver)
- description and source-code
```javascript
class Driver extends webdriver.WebDriver {

<span class="apidocCodeCommentSpan">  /**
   * Creates a new session with the ChromeDriver.
   *
   * @param {(Capabilities|Options)=} opt_config The configuration options.
   * @param {(remote.DriverService|http.Executor)=} opt_serviceExecutor Either
   *     a  DriverService to use for the remote end, or a preconfigured executor
   *     for an externally managed endpoint. If neither is provided, the
   *     {@linkplain ##getDefaultService default service} will be used by
   *     default.
   * @param {promise.ControlFlow=} opt_flow The control flow to use, or 'null'
   *     to use the currently active flow.
   * @return {!Driver} A new driver instance.
   */
</span>  static createSession(opt_config, opt_serviceExecutor, opt_flow) {
    let executor;
    if (opt_serviceExecutor instanceof http.Executor) {
      executor = opt_serviceExecutor;
      configureExecutor(executor);
    } else {
      let service = opt_serviceExecutor || getDefaultService();
      executor = createExecutor(service.start());
    }

    let caps =
        opt_config instanceof Options ? opt_config.toCapabilities() :
        (opt_config || Capabilities.chrome());

    return /** @type {!Driver} */(
        webdriver.WebDriver.createSession(executor, caps, opt_flow, this));
  }

  /**
   * This function is a no-op as file detectors are not supported by this
   * implementation.
   * @override
   */
  setFileDetector() {}

  /**
   * Schedules a command to launch Chrome App with given ID.
   * @param {string} id ID of the App to launch.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when app is launched.
   */
  launchApp(id) {
    return this.schedule(
        new command.Command(Command.LAUNCH_APP).setParameter('id', id),
        'Driver.launchApp()');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.chrome.Options"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>Options ()](#apidoc.element.selenium-webdriver.chrome.Options)
- description and source-code
```javascript
class Options {
  constructor() {
<span class="apidocCodeCommentSpan">    /** @private {!Object} */
</span>    this.options_ = {};

    /** @private {!Array<(string|!Buffer)>} */
    this.extensions_ = [];

    /** @private {?logging.Preferences} */
    this.logPrefs_ = null;

    /** @private {?./lib/capabilities.ProxyConfig} */
    this.proxy_ = null;
  }

  /**
   * Extracts the ChromeDriver specific options from the given capabilities
   * object.
   * @param {!Capabilities} caps The capabilities object.
   * @return {!Options} The ChromeDriver options.
   */
  static fromCapabilities(caps) {
    let options = new Options();

    let o = caps.get(OPTIONS_CAPABILITY_KEY);
    if (o instanceof Options) {
      options = o;
    } else if (o) {
      options.
          addArguments(o.args || []).
          addExtensions(o.extensions || []).
          detachDriver(o.detach).
          excludeSwitches(o.excludeSwitches || []).
          setChromeBinaryPath(o.binary).
          setChromeLogFile(o.logPath).
          setChromeMinidumpPath(o.minidumpPath).
          setLocalState(o.localState).
          setMobileEmulation(o.mobileEmulation).
          setUserPreferences(o.prefs).
          setPerfLoggingPrefs(o.perfLoggingPrefs);
    }

    if (caps.has(Capability.PROXY)) {
      options.setProxy(caps.get(Capability.PROXY));
    }

    if (caps.has(Capability.LOGGING_PREFS)) {
      options.setLoggingPrefs(
          caps.get(Capability.LOGGING_PREFS));
    }

    return options;
  }

  /**
   * Add additional command line arguments to use when launching the Chrome
   * browser.  Each argument may be specified with or without the "--" prefix
   * (e.g. "--foo" and "foo"). Arguments with an associated value should be
   * delimited by an "=": "foo=bar".
   * @param {...(string|!Array<string>)} var_args The arguments to add.
   * @return {!Options} A self reference.
   */
  addArguments(var_args) {
    let args = this.options_.args || [];
    args = args.concat.apply(args, arguments);
    if (args.length) {
      this.options_.args = args;
    }
    return this;
  }

  /**
   * List of Chrome command line switches to exclude that ChromeDriver by default
   * passes when starting Chrome.  Do not prefix switches with "--".
   *
   * @param {...(string|!Array<string>)} var_args The switches to exclude.
   * @return {!Options} A self reference.
   */
  excludeSwitches(var_args) {
    let switches = this.options_.excludeSwitches || [];
    switches = switches.concat.apply(switches, arguments);
    if (switches.length) {
      this.options_.excludeSwitches = switches;
    }
    return this;
  }

  /**
   * Add additional extensions to install when launching Chrome. Each extension
   * should be specified as the path to the packed CRX file, or a Buffer for an
   * extension.
   * @param {...(string|!Buffer|!Array<(string|!Buffer)>)} var_args The
   *     extensions to add.
   * @return {!Options} A self reference.
   */
  addExtensions(var_args) {
    this.extensions_ =
        this.extensions_.concat.apply(this.extensions_, arguments);
    return this;
  }

  /**
   * Sets the path to the Chrome binary to use. On Mac OS X, this path should
   * reference the actual Chrome executable, not just the application binary
   * (e.g. "/Applications/Google Chrome.app/Contents/MacOS/Google Chrome").
   *
   * The binary path be absolute or relative to the chromedriver server
   * executable, but it must exist on the machine that will launch Chrome.
   *
   * @param {string} path The path to the Chrome binary to use.
   * @return {!Options} A self reference.
   */
  setChromeBinaryPath(path) {
    this.options_.binary = path;
    return this;
  }

  /**
   * Sets whether to leave the started Chrome browser running if the controlling
   * ChromeDriver service is killed before {@link webdriver.WebDriver#quit()} is
   * called.
   * @param {boolean} detach Whether to leave the browser running if the
   *     chromedriver service is killed before the session.
   * @return {!Options} A self reference.
   */
  detachDriver(detach) {
    this.options_.detach = detach;
    return this;
  } ...
```
- example usage
```shell
...
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
*     let driver = chrome.Driver.createSession(options, service);
*
* Users should only instantiate the {@link Driver} class directly when they
* need a custom driver service configuration (as shown above). For normal
* operation, users should start Chrome using the
...
```

#### <a name="apidoc.element.selenium-webdriver.chrome.ServiceBuilder"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>ServiceBuilder (opt_exe)](#apidoc.element.selenium-webdriver.chrome.ServiceBuilder)
- description and source-code
```javascript
class ServiceBuilder extends remote.DriverService.Builder {
<span class="apidocCodeCommentSpan">  /**
   * @param {string=} opt_exe Path to the server executable to use. If omitted,
   *     the builder will attempt to locate the chromedriver on the current
   *     PATH.
   * @throws {Error} If provided executable does not exist, or the chromedriver
   *     cannot be found on the PATH.
   */
</span>  constructor(opt_exe) {
    let exe = opt_exe || io.findInPath(CHROMEDRIVER_EXE, true);
    if (!exe) {
      throw Error(
          'The ChromeDriver could not be found on the current PATH. Please ' +
          'download the latest version of the ChromeDriver from ' +
          'http://chromedriver.storage.googleapis.com/index.html and ensure ' +
          'it can be found on your PATH.');
    }

    super(exe);
    this.setLoopback(true);  // Required
  }

  /**
   * Sets which port adb is listening to. _The ChromeDriver will connect to adb
   * if an {@linkplain Options#androidPackage Android session} is requested, but
   * adb **must** be started beforehand._
   *
   * @param {number} port Which port adb is running on.
   * @return {!ServiceBuilder} A self reference.
   */
  setAdbPort(port) {
    return this.addArguments('--adb-port=' + port);
  }

  /**
   * Sets the path of the log file the driver should log to. If a log file is
   * not specified, the driver will log to stderr.
   * @param {string} path Path of the log file to use.
   * @return {!ServiceBuilder} A self reference.
   */
  loggingTo(path) {
    return this.addArguments('--log-path=' + path);
  }

  /**
   * Enables verbose logging.
   * @return {!ServiceBuilder} A self reference.
   */
  enableVerboseLogging() {
    return this.addArguments('--verbose');
  }

  /**
   * Sets the number of threads the driver should use to manage HTTP requests.
   * By default, the driver will use 4 threads.
   * @param {number} n The number of threads to use.
   * @return {!ServiceBuilder} A self reference.
   */
  setNumHttpThreads(n) {
    return this.addArguments('--http-threads=' + n);
  }

  /**
   * @override
   */
  setPath(path) {
    super.setPath(path);
    return this.addArguments('--url-base=' + path);
  }
}
```
- example usage
```shell
...
* with {@link #setDefaultService setDefaultService()}.
*
* You may also create a {@link Driver} with its own driver service. This is
* useful if you need to capture the server's log output for a specific session:
*
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
...
```

#### <a name="apidoc.element.selenium-webdriver.chrome.getDefaultService"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>getDefaultService ()](#apidoc.element.selenium-webdriver.chrome.getDefaultService)
- description and source-code
```javascript
function getDefaultService() {
  if (!defaultService) {
    defaultService = new ServiceBuilder().build();
  }
  return defaultService;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.chrome.setDefaultService"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.chrome.</span>setDefaultService (service)](#apidoc.element.selenium-webdriver.chrome.setDefaultService)
- description and source-code
```javascript
function setDefaultService(service) {
  if (defaultService && defaultService.isRunning()) {
    throw Error(
        'The previously configured ChromeDriver service is still running. ' +
        'You must shut it down before you may adjust its configuration.');
  }
  defaultService = service;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.command"></a>[module selenium-webdriver.command](#apidoc.module.selenium-webdriver.command)

#### <a name="apidoc.element.selenium-webdriver.command.Command"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.command.</span>Command (name)](#apidoc.element.selenium-webdriver.command.Command)
- description and source-code
```javascript
class Command {
<span class="apidocCodeCommentSpan">  /** @param {string} name The name of this command. */
</span>  constructor(name) {
    /** @private {string} */
    this.name_ = name;

    /** @private {!Object<*>} */
    this.parameters_ = {};
  }

  /** @return {string} This command's name. */
  getName() {
    return this.name_;
  }

  /**
   * Sets a parameter to send with this command.
   * @param {string} name The parameter name.
   * @param {*} value The parameter value.
   * @return {!Command} A self reference.
   */
  setParameter(name, value) {
    this.parameters_[name] = value;
    return this;
  }

  /**
   * Sets the parameters for this command.
   * @param {!Object<*>} parameters The command parameters.
   * @return {!Command} A self reference.
   */
  setParameters(parameters) {
    this.parameters_ = parameters;
    return this;
  }

  /**
   * Returns a named command parameter.
   * @param {string} key The parameter key to look up.
   * @return {*} The parameter value, or undefined if it has not been set.
   */
  getParameter(key) {
    return this.parameters_[key];
  }

  /**
   * @return {!Object<*>} The parameters to send with this command.
   */
  getParameters() {
    return this.parameters_;
  }
}
```
- example usage
```shell
...
   * Schedules a command to launch Chrome App with given ID.
   * @param {string} id ID of the App to launch.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when app is launched.
   */
  launchApp(id) {
    return this.schedule(
        new command.Command(Command.LAUNCH_APP).setParameter('id', id),
        'Driver.launchApp()');
  }
}


// PUBLIC API
...
```

#### <a name="apidoc.element.selenium-webdriver.command.Executor"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.command.</span>Executor (command)](#apidoc.element.selenium-webdriver.command.Executor)
- description and source-code
```javascript
class Executor {
<span class="apidocCodeCommentSpan">  /**
   * Executes the given {@code command}. If there is an error executing the
   * command, the provided callback will be invoked with the offending error.
   * Otherwise, the callback will be invoked with a null Error and non-null
   * response object.
   *
   * @param {!Command} command The command to execute.
   * @return {!Promise<?>} A promise that will be fulfilled with the command
   *     result.
   */
</span>  execute(command) {}
}
```
- example usage
```shell
...
}
    }

    if (url) {
this.log_.fine('Creating session on remote server');
let client = Promise.resolve(url)
    .then(url => new _http.HttpClient(url, this.agent_, this.proxy_));
let executor = new _http.Executor(client);

if (browser === Browser.CHROME) {
  const driver = ensureFileDetectorsAreEnabled(chrome.Driver);
  return createDriver(
      driver, capabilities, executor, this.flow_);
}
...
```



# <a name="apidoc.module.selenium-webdriver.edge"></a>[module selenium-webdriver.edge](#apidoc.module.selenium-webdriver.edge)

#### <a name="apidoc.element.selenium-webdriver.edge.Driver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>Driver (capabilities.Capabilities|Options)](#apidoc.element.selenium-webdriver.edge.Driver)
- description and source-code
```javascript
class Driver extends webdriver.WebDriver {
<span class="apidocCodeCommentSpan">  /**
   * Creates a new browser session for Microsoft's Edge browser.
   *
   * @param {(capabilities.Capabilities|Options)=} opt_config The configuration
   *     options.
   * @param {remote.DriverService=} opt_service The session to use; will use
   *     the {@linkplain #getDefaultService default service} by default.
   * @param {promise.ControlFlow=} opt_flow The control flow to use, or
   *     {@code null} to use the currently active flow.
   * @return {!Driver} A new driver instance.
   */
</span>  static createSession(opt_config, opt_service, opt_flow) {
    var service = opt_service || getDefaultService();
    var client = service.start().then(url => new http.HttpClient(url));
    var executor = new http.Executor(client);

    var caps =
        opt_config instanceof Options ? opt_config.toCapabilities() :
        (opt_config || capabilities.Capabilities.edge());

    return /** @type {!Driver} */(webdriver.WebDriver.createSession(
        executor, caps, opt_flow, this, () => service.kill()));
  }

  /**
   * This function is a no-op as file detectors are not supported by this
   * implementation.
   * @override
   */
  setFileDetector() {}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.edge.Options"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>Options ()](#apidoc.element.selenium-webdriver.edge.Options)
- description and source-code
```javascript
class Options {
  constructor() {
<span class="apidocCodeCommentSpan">    /** @private {!Object} */
</span>    this.options_ = {};

    /** @private {?capabilities.ProxyConfig} */
    this.proxy_ = null;
  }

  /**
   * Extracts the MicrosoftEdgeDriver specific options from the given
   * capabilities object.
   * @param {!capabilities.Capabilities} caps The capabilities object.
   * @return {!Options} The MicrosoftEdgeDriver options.
   */
  static fromCapabilities(caps) {
    var options = new Options();
    var map = options.options_;

    Object.keys(CAPABILITY_KEY).forEach(function(key) {
      key = CAPABILITY_KEY[key];
      if (caps.has(key)) {
        map[key] = caps.get(key);
      }
    });

    if (caps.has(capabilities.Capability.PROXY)) {
      options.setProxy(caps.get(capabilities.Capability.PROXY));
    }

    return options;
  }

  /**
   * Sets the proxy settings for the new session.
   * @param {capabilities.ProxyConfig} proxy The proxy configuration to use.
   * @return {!Options} A self reference.
   */
  setProxy(proxy) {
    this.proxy_ = proxy;
    return this;
  }

  /**
   * Sets the page load strategy for Edge.
   * Supported values are "normal", "eager", and "none";
   *
   * @param {string} pageLoadStrategy The page load strategy to use.
   * @return {!Options} A self reference.
   */
  setPageLoadStrategy(pageLoadStrategy) {
    this.options_[CAPABILITY_KEY.PAGE_LOAD_STRATEGY] =
      pageLoadStrategy.toLowerCase();
    return this;
  }

  /**
   * Converts this options instance to a {@link capabilities.Capabilities}
   * object.
   * @param {capabilities.Capabilities=} opt_capabilities The capabilities to
   *     merge these options into, if any.
   * @return {!capabilities.Capabilities} The capabilities.
   */
  toCapabilities(opt_capabilities) {
    var caps = opt_capabilities || capabilities.Capabilities.edge();
    if (this.proxy_) {
      caps.set(capabilities.Capability.PROXY, this.proxy_);
    }
    Object.keys(this.options_).forEach(function(key) {
      caps.set(key, this.options_[key]);
    }, this);
    return caps;
  }

  /**
   * Converts this instance to its JSON wire protocol representation. Note this
   * function is an implementation not intended for general use.
   * @return {{pageLoadStrategy: (string|undefined)}}
   *   The JSON wire protocol representation of this instance.
   */
  [Symbols.serialize]() {
    var json = {};
    for (var key in this.options_) {
      if (this.options_[key] != null) {
        json[key] = this.options_[key];
      }
    }
    return json;
  }
}
```
- example usage
```shell
...
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
*     let driver = chrome.Driver.createSession(options, service);
*
* Users should only instantiate the {@link Driver} class directly when they
* need a custom driver service configuration (as shown above). For normal
* operation, users should start Chrome using the
...
```

#### <a name="apidoc.element.selenium-webdriver.edge.ServiceBuilder"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>ServiceBuilder (opt_exe)](#apidoc.element.selenium-webdriver.edge.ServiceBuilder)
- description and source-code
```javascript
class ServiceBuilder extends remote.DriverService.Builder {
<span class="apidocCodeCommentSpan">  /**
   * @param {string=} opt_exe Path to the server executable to use. If omitted,
   *   the builder will attempt to locate the MicrosoftEdgeDriver on the current
   *   PATH.
   * @throws {Error} If provided executable does not exist, or the
   *   MicrosoftEdgeDriver cannot be found on the PATH.
   */
</span>  constructor(opt_exe) {
    let exe = opt_exe || io.findInPath(EDGEDRIVER_EXE, true);
    if (!exe) {
      throw Error(
        'The ' + EDGEDRIVER_EXE + ' could not be found on the current PATH. ' +
        'Please download the latest version of the MicrosoftEdgeDriver from ' +
        'https://www.microsoft.com/en-us/download/details.aspx?id=48212 and ' +
        'ensure it can be found on your PATH.');
    }

    super(exe);

    // Binding to the loopback address will fail if not running with
    // administrator privileges. Since we cannot test for that in script
    // (or can we?), force the DriverService to use "localhost".
    this.setHostname('localhost');
  }
}
```
- example usage
```shell
...
* with {@link #setDefaultService setDefaultService()}.
*
* You may also create a {@link Driver} with its own driver service. This is
* useful if you need to capture the server's log output for a specific session:
*
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
...
```

#### <a name="apidoc.element.selenium-webdriver.edge.getDefaultService"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>getDefaultService ()](#apidoc.element.selenium-webdriver.edge.getDefaultService)
- description and source-code
```javascript
function getDefaultService() {
  if (!defaultService) {
    defaultService = new ServiceBuilder().build();
  }
  return defaultService;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.edge.setDefaultService"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.edge.</span>setDefaultService (service)](#apidoc.element.selenium-webdriver.edge.setDefaultService)
- description and source-code
```javascript
function setDefaultService(service) {
  if (defaultService && defaultService.isRunning()) {
    throw Error(
      'The previously configured EdgeDriver service is still running. ' +
      'You must shut it down before you may adjust its configuration.');
  }
  defaultService = service;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.error"></a>[module selenium-webdriver.error](#apidoc.module.selenium-webdriver.error)

#### <a name="apidoc.element.selenium-webdriver.error.ElementNotSelectableError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>ElementNotSelectableError (opt_error)](#apidoc.element.selenium-webdriver.error.ElementNotSelectableError)
- description and source-code
```javascript
class ElementNotSelectableError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.ElementNotVisibleError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>ElementNotVisibleError (opt_error)](#apidoc.element.selenium-webdriver.error.ElementNotVisibleError)
- description and source-code
```javascript
class ElementNotVisibleError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.InvalidArgumentError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidArgumentError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidArgumentError)
- description and source-code
```javascript
class InvalidArgumentError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
...
* Checks that a key is a modifier key.
* @param {!input.Key} key The key to check.
* @throws {error.InvalidArgumentError} If the key is not a modifier key.
* @private
*/
function checkModifierKey(key) {
 if (!MODIFIER_KEYS.has(key)) {
   throw new error.InvalidArgumentError('Not a modifier key');
 }
}


/**
* Class for defining sequences of complex user interactions. Each sequence
* will not be executed until {@link #perform} is called.
...
```

#### <a name="apidoc.element.selenium-webdriver.error.InvalidCookieDomainError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidCookieDomainError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidCookieDomainError)
- description and source-code
```javascript
class InvalidCookieDomainError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.InvalidElementCoordinatesError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidElementCoordinatesError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidElementCoordinatesError)
- description and source-code
```javascript
class InvalidElementCoordinatesError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.InvalidElementStateError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidElementStateError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidElementStateError)
- description and source-code
```javascript
class InvalidElementStateError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.InvalidSelectorError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>InvalidSelectorError (opt_error)](#apidoc.element.selenium-webdriver.error.InvalidSelectorError)
- description and source-code
```javascript
class InvalidSelectorError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.JavascriptError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>JavascriptError (opt_error)](#apidoc.element.selenium-webdriver.error.JavascriptError)
- description and source-code
```javascript
class JavascriptError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.MoveTargetOutOfBoundsError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>MoveTargetOutOfBoundsError (opt_error)](#apidoc.element.selenium-webdriver.error.MoveTargetOutOfBoundsError)
- description and source-code
```javascript
class MoveTargetOutOfBoundsError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.NoSuchAlertError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchAlertError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchAlertError)
- description and source-code
```javascript
class NoSuchAlertError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.NoSuchElementError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchElementError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchElementError)
- description and source-code
```javascript
class NoSuchElementError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.NoSuchFrameError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchFrameError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchFrameError)
- description and source-code
```javascript
class NoSuchFrameError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.NoSuchSessionError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchSessionError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchSessionError)
- description and source-code
```javascript
class NoSuchSessionError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
...
    var result = this.schedule(
  new command.Command(command.Name.QUIT),
  'WebDriver.quit()');
    // Delete our session ID when the quit command finishes; this will allow us
    // to throw an error when attempting to use a driver post-quit.
    return /** @type {!promise.Thenable} */(promise.finally(result, () => {
this.session_ = this.flow_.promise((_, reject) => {
  reject(new error.NoSuchSessionError(
      'This driver instance does not have a valid session ID ' +
      '(did you call WebDriver.quit()?) and may no longer be used.'));
});

// Only want the session rejection to bubble if accessed.
this.session_.catch(function() {});
...
```

#### <a name="apidoc.element.selenium-webdriver.error.NoSuchWindowError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>NoSuchWindowError (opt_error)](#apidoc.element.selenium-webdriver.error.NoSuchWindowError)
- description and source-code
```javascript
class NoSuchWindowError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.ScriptTimeoutError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>ScriptTimeoutError (opt_error)](#apidoc.element.selenium-webdriver.error.ScriptTimeoutError)
- description and source-code
```javascript
class ScriptTimeoutError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.SessionNotCreatedError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>SessionNotCreatedError (opt_error)](#apidoc.element.selenium-webdriver.error.SessionNotCreatedError)
- description and source-code
```javascript
class SessionNotCreatedError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.StaleElementReferenceError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>StaleElementReferenceError (opt_error)](#apidoc.element.selenium-webdriver.error.StaleElementReferenceError)
- description and source-code
```javascript
class StaleElementReferenceError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.TimeoutError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>TimeoutError (opt_error)](#apidoc.element.selenium-webdriver.error.TimeoutError)
- description and source-code
```javascript
class TimeoutError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.UnableToCaptureScreenError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnableToCaptureScreenError (opt_error)](#apidoc.element.selenium-webdriver.error.UnableToCaptureScreenError)
- description and source-code
```javascript
class UnableToCaptureScreenError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.UnableToSetCookieError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnableToSetCookieError (opt_error)](#apidoc.element.selenium-webdriver.error.UnableToSetCookieError)
- description and source-code
```javascript
class UnableToSetCookieError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.UnexpectedAlertOpenError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnexpectedAlertOpenError (opt_error, opt_text)](#apidoc.element.selenium-webdriver.error.UnexpectedAlertOpenError)
- description and source-code
```javascript
class UnexpectedAlertOpenError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /**
   * @param {string=} opt_error the error message, if any.
   * @param {string=} opt_text the text of the open dialog, if available.
   */
</span>  constructor(opt_error, opt_text) {
    super(opt_error);

    /** @private {(string|undefined)} */
    this.text_ = opt_text;
  }

  /**
   * @return {(string|undefined)} The text displayed with the unhandled alert,
   *     if available.
   */
  getAlertText() {
    return this.text_;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.UnknownCommandError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnknownCommandError (opt_error)](#apidoc.element.selenium-webdriver.error.UnknownCommandError)
- description and source-code
```javascript
class UnknownCommandError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
...
}

spec = COMMAND_MAP.get(command.getName());
if (spec) {
  return toHttpRequest(spec);
}
return Promise.reject(
    new error.UnknownCommandError(
        'Unrecognized command: ' + command.getName()));

/**
 * @param {CommandSpec} resource
 * @return {!Promise<!Request>}
 */
function toHttpRequest(resource) {
...
```

#### <a name="apidoc.element.selenium-webdriver.error.UnknownMethodError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnknownMethodError (opt_error)](#apidoc.element.selenium-webdriver.error.UnknownMethodError)
- description and source-code
```javascript
class UnknownMethodError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.UnsupportedOperationError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>UnsupportedOperationError (opt_error)](#apidoc.element.selenium-webdriver.error.UnsupportedOperationError)
- description and source-code
```javascript
class UnsupportedOperationError extends WebDriverError {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);
  }
}
```
- example usage
```shell
...
  }

  let value = httpResponse.body.replace(/\r\n/g, '\n');

  // 404 represents an unknown command; anything else > 399 is a generic unknown
  // error.
  if (httpResponse.status == 404) {
    throw new error.UnsupportedOperationError(value);
  } else if (httpResponse.status >= 400) {
    throw new error.WebDriverError(value);
  }

  return value || null;
}
...
```

#### <a name="apidoc.element.selenium-webdriver.error.WebDriverError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>WebDriverError (opt_error)](#apidoc.element.selenium-webdriver.error.WebDriverError)
- description and source-code
```javascript
class WebDriverError extends Error {
<span class="apidocCodeCommentSpan">  /** @param {string=} opt_error the error message, if any. */
</span>  constructor(opt_error) {
    super(opt_error);

    /** @override */
    this.name = this.constructor.name;
  }
}
```
- example usage
```shell
...
        let parsed =
  parseHttpResponse(
      command, /** @type {!Response} */ (response), this.w3c);

        if (command.getName() === cmd.Name.NEW_SESSION
  || command.getName() === cmd.Name.DESCRIBE_SESSION) {
if (!parsed || !parsed['sessionId']) {
  throw new error.WebDriverError(
      'Unable to parse new session response: ' + response.body);
}

// The remote end is a W3C compliant server if there is no 'status'
// field in the response. This is not applicable for the DESCRIBE_SESSION
// command, which is not defined in the W3C spec.
if (command.getName() === cmd.Name.NEW_SESSION) {
...
```

#### <a name="apidoc.element.selenium-webdriver.error.checkLegacyResponse"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>checkLegacyResponse (responseObj)](#apidoc.element.selenium-webdriver.error.checkLegacyResponse)
- description and source-code
```javascript
function checkLegacyResponse(responseObj) {
  // Handle the legacy Selenium error response format.
  if (responseObj
      && typeof responseObj === 'object'
      && typeof responseObj['status'] === 'number'
      && responseObj['status'] !== 0) {
    let status = responseObj['status'];
    let ctor = LEGACY_ERROR_CODE_TO_TYPE.get(status) || WebDriverError;

    let value = responseObj['value'];

    if (!value || typeof value !== 'object') {
      throw new ctor(value + '');
    } else {
      let message = value['message'] + '';
      if (ctor !== UnexpectedAlertOpenError) {
        throw new ctor(message);
      }

      let text = '';
      if (value['alert'] && typeof value['alert']['text'] === 'string') {
        text = value['alert']['text'];
      }
      throw new UnexpectedAlertOpenError(message, text);
    }
  }
  return responseObj;
}
```
- example usage
```shell
...
  if (httpResponse.status > 399
      && (command.getName() == cmd.Name.NEW_SESSION
          || command.getName() === cmd.Name.DESCRIBE_SESSION)
      && error.isErrorResponse(parsed)) {
    error.throwDecodedError(parsed);
  }

  error.checkLegacyResponse(parsed);
  return parsed;
}

let value = httpResponse.body.replace(/\r\n/g, '\n');

// 404 represents an unknown command; anything else > 399 is a generic unknown
// error.
...
```

#### <a name="apidoc.element.selenium-webdriver.error.checkResponse"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>checkResponse (data)](#apidoc.element.selenium-webdriver.error.checkResponse)
- description and source-code
```javascript
function checkResponse(data) {
  if (data && typeof data.error === 'string') {
    let ctor = ERROR_CODE_TO_TYPE.get(data.error) || WebDriverError;
    throw new ctor(data.message);
  }
  return data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.encodeError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>encodeError (err)](#apidoc.element.selenium-webdriver.error.encodeError)
- description and source-code
```javascript
function encodeError(err) {
  let type = WebDriverError;
  if (err instanceof WebDriverError
      && TYPE_TO_ERROR_CODE.has(err.constructor)) {
    type = err.constructor;
  }

  let message = err instanceof Error
      ? err.message
      : err + '';

  let code = /** @type {string} */(TYPE_TO_ERROR_CODE.get(type));
  return {'error': code, 'message': message};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.error.isErrorResponse"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>isErrorResponse (data)](#apidoc.element.selenium-webdriver.error.isErrorResponse)
- description and source-code
```javascript
function isErrorResponse(data) {
  return data && typeof data === 'object' && typeof data.error === 'string';
}
```
- example usage
```shell
...

  // If this is a new session command, we need to check for a W3C compliant
  // error object. This is necessary since a successful new session command
  // is what puts the executor into W3C mode.
  if (httpResponse.status > 399
      && (command.getName() == cmd.Name.NEW_SESSION
          || command.getName() === cmd.Name.DESCRIBE_SESSION)
      && error.isErrorResponse(parsed)) {
    error.throwDecodedError(parsed);
  }

  error.checkLegacyResponse(parsed);
  return parsed;
}
...
```

#### <a name="apidoc.element.selenium-webdriver.error.throwDecodedError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.error.</span>throwDecodedError (data)](#apidoc.element.selenium-webdriver.error.throwDecodedError)
- description and source-code
```javascript
function throwDecodedError(data) {
  if (isErrorResponse(data)) {
    let ctor = ERROR_CODE_TO_TYPE.get(data.error) || WebDriverError;
    throw new ctor(data.message);
  }
  throw new WebDriverError('Unknown error: ' + JSON.stringify(data));
}
```
- example usage
```shell
...
  // users report it.
  throw new error.WebDriverError(
      'Unexpected HTTP response:\n${httpResponse}');
}

if (w3c) {
  if (httpResponse.status > 399) {
    error.throwDecodedError(parsed);
  }
  return parsed;
}

// If this is a new session command, we need to check for a W3C compliant
// error object. This is necessary since a successful new session command
// is what puts the executor into W3C mode.
...
```



# <a name="apidoc.module.selenium-webdriver.events"></a>[module selenium-webdriver.events](#apidoc.module.selenium-webdriver.events)

#### <a name="apidoc.element.selenium-webdriver.events.EventEmitter"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.events.</span>EventEmitter (type, var_args)](#apidoc.element.selenium-webdriver.events.EventEmitter)
- description and source-code
```javascript
class EventEmitter {
<span class="apidocCodeCommentSpan">  /**
   * Fires an event and calls all listeners.
   * @param {string} type The type of event to emit.
   * @param {...*} var_args Any arguments to pass to each listener.
   */
</span>  emit(type, var_args) {
    let events = EVENTS.get(this);
    if (!events) {
      return;
    }

    let args = Array.prototype.slice.call(arguments, 1);

    let listeners = events.get(type);
    if (listeners) {
      for (let listener of listeners) {
        listener.fn.apply(listener.scope, args);
        if (listener.oneshot) {
          listeners.delete(listener);
        }
      }
    }
  }

  /**
   * Returns a mutable list of listeners for a specific type of event.
   * @param {string} type The type of event to retrieve the listeners for.
   * @return {!Set<!Listener>} The registered listeners for the given event
   *     type.
   */
  listeners(type) {
    let events = EVENTS.get(this);
    if (!events) {
      events = new Map;
      EVENTS.set(this, events);
    }

    let listeners = events.get(type);
    if (!listeners) {
      listeners = new Set;
      events.set(type, listeners);
    }
    return listeners;
  }

  /**
   * Registers a listener.
   * @param {string} type The type of event to listen for.
   * @param {!Function} fn The function to invoke when the event is fired.
   * @param {Object=} opt_self The object in whose scope to invoke the listener.
   * @param {boolean=} opt_oneshot Whether the listener should b (e removed after
   *    the first event is fired.
   * @return {!EventEmitter} A self reference.
   * @private
   */
  addListener_(type, fn, opt_self, opt_oneshot) {
    let listeners = this.listeners(type);
    for (let listener of listeners) {
      if (listener.fn === fn) {
        return this;
      }
    }
    listeners.add(new Listener(fn, opt_self || undefined, !!opt_oneshot));
    return this;
  }

  /**
   * Registers a listener.
   * @param {string} type The type of event to listen for.
   * @param {!Function} fn The function to invoke when the event is fired.
   * @param {Object=} opt_self The object in whose scope to invoke the listener.
   * @return {!EventEmitter} A self reference.
   */
  addListener(type, fn, opt_self) {
    return this.addListener_(type, fn, opt_self, false);
  }

  /**
   * Registers a one-time listener which will be called only the first time an
   * event is emitted, after which it will be removed.
   * @param {string} type The type of event to listen for.
   * @param {!Function} fn The function to invoke when the event is fired.
   * @param {Object=} opt_self The object in whose scope to invoke the listener.
   * @return {!EventEmitter} A self reference.
   */
  once(type, fn, opt_self) {
    return this.addListener_(type, fn, opt_self, true);
  }

  /**
   * An alias for {@link #addListener() addListener()}.
   * @param {string} type The type of event to listen for.
   * @param {!Function} fn The function to invoke when the event is fired.
   * @param {Object=} opt_self The object in whose scope to invoke the listener.
   * @return {!EventEmitter} A self reference.
   */
  on(type, fn, opt_self) {
    return this.addListener(type, fn, opt_self);
  }

  /**
   * Removes a previously registered event listener.
   * @param {string} type The type of event to unregister.
   * @param {!Function} listenerFn The handler function to remove.
   * @return {!EventEmitter} A self reference.
   */
  removeListener(type, listenerFn) {
    if (typeof type !== 'string' || typeof listenerFn !== 'function') {
      throw TypeError('invalid args: expected (string, function), got ('
          + (typeof type) + ', ' + (typeof listenerFn) + ')');
    }

    let events = EVENTS.get(this);
    if (!events) {
      return this;
    }

    let listeners = events.get(type);
    if (!listeners) {
      return this;
    }

    let match;
    for (let listener of listeners) {
      if (listener.fn === listenerFn) {
        match = listener;
        break;
      }
    }
    if (match) {
      listeners.delete(match);
      if (!listeners.size) {
        events.delete(type);
      } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.events.Listener"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.events.</span>Listener (Object|undefined)](#apidoc.element.selenium-webdriver.events.Listener)
- description and source-code
```javascript
class Listener {
<span class="apidocCodeCommentSpan">  /**
   * @param {!Function} fn The actual listener function.
   * @param {(Object|undefined)} scope The object in whose scope to invoke the
   *     listener.
   * @param {boolean} oneshot Whether this listener should only be used once.
   */
</span>  constructor(fn, scope, oneshot) {
    this.fn = fn;
    this.scope = scope;
    this.oneshot = oneshot;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.exec"></a>[module selenium-webdriver.exec](#apidoc.module.selenium-webdriver.exec)

#### <a name="apidoc.element.selenium-webdriver.exec.exec"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.</span>exec (command, opt_options)](#apidoc.element.selenium-webdriver.exec.exec)
- description and source-code
```javascript
function exec(command, opt_options) {
  var options = opt_options || {};

  var proc = childProcess.spawn(command, options.args || [], {
    env: options.env || process.env,
    stdio: options.stdio || 'ignore'
  });

  // This process should not wait on the spawned child, however, we do
  // want to ensure the child is killed when this process exits.
  proc.unref();
  process.once('exit', onProcessExit);

  let result = new Promise(resolve => {
    proc.once('exit', (code, signal) => {
      proc = null;
      process.removeListener('exit', onProcessExit);
      resolve(new Result(code, signal));
    });
  });
  return new Command(result, killCommand);

  function onProcessExit() {
    killCommand('SIGTERM');
  }

  function killCommand(signal) {
    process.removeListener('exit', onProcessExit);
    if (proc) {
      proc.kill(signal);
      proc = null;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.exec.Command"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.exec.</span>Command (string)](#apidoc.element.selenium-webdriver.exec.Command)
- description and source-code
```javascript
class Command {
<span class="apidocCodeCommentSpan">  /**
   * @param {!Promise<!Result>} result The command result.
   * @param {function(string)} onKill The function to call when {@link #kill()}
   *     is called.
   */
</span>  constructor(result, onKill) {
    COMMAND_RESULT.set(this, result);
    KILL_HOOK.set(this, onKill);
  }

  /**
   * @return {!Promise<!Result>} A promise for the result of this
   *     command.
   */
  result() {
    return /** @type {!Promise<!Result>} */(COMMAND_RESULT.get(this));
  }

  /**
   * Sends a signal to the underlying process.
   * @param {string=} opt_signal The signal to send; defaults to 'SIGTERM'.
   */
  kill(opt_signal) {
    KILL_HOOK.get(this)(opt_signal || 'SIGTERM');
  }
}
```
- example usage
```shell
...
   * Schedules a command to launch Chrome App with given ID.
   * @param {string} id ID of the App to launch.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when app is launched.
   */
  launchApp(id) {
    return this.schedule(
        new command.Command(Command.LAUNCH_APP).setParameter('id', id),
        'Driver.launchApp()');
  }
}


// PUBLIC API
...
```

#### <a name="apidoc.element.selenium-webdriver.exec.Result"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.exec.</span>Result (code, signal)](#apidoc.element.selenium-webdriver.exec.Result)
- description and source-code
```javascript
class Result {
<span class="apidocCodeCommentSpan">  /**
   * @param {?number} code The exit code, or {@code null} if the command did not
   *     exit normally.
   * @param {?string} signal The signal used to kill the command, or
   *     {@code null}.
   */
</span>  constructor(code, signal) {
    /** @type {?number} */
    this.code = code;

    /** @type {?string} */
    this.signal = signal;
  }

  /** @override */
  toString() {
    return 'Result(code=${this.code}, signal=${this.signal})';
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.extension"></a>[module selenium-webdriver.extension](#apidoc.module.selenium-webdriver.extension)

#### <a name="apidoc.element.selenium-webdriver.extension.install"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.extension.</span>install (extension, dir)](#apidoc.element.selenium-webdriver.extension.install)
- description and source-code
```javascript
function install(extension, dir) {
  return getDetails(extension).then(function(details) {
    var dst = path.join(dir, details.id);
    if (extension.slice(-4) === '.xpi') {
      if (!details.unpack) {
        return io.copy(extension, dst + '.xpi').then(() => details.id);
      } else {
        return Promise.resolve().then(function() {
          // TODO: find an async library for inflating a zip archive.
          new AdmZip(extension).extractAllTo(dst, true);
          return details.id;
        });
      }
    } else {
      return io.copyDir(extension, dst).then(() => details.id);
    }
  });
}
```
- example usage
```shell
...
        }
      } else {
        install(extensions[next++]);
      }
    }

    function install(ext) {
      extension.install(ext, extensionDir).then(function(id) {
        hasWebDriver = hasWebDriver || (id === WEBDRIVER_EXTENSION_NAME);
        installNext();
      }, reject);
    }
  });
}
...
```



# <a name="apidoc.module.selenium-webdriver.http"></a>[module selenium-webdriver.http](#apidoc.module.selenium-webdriver.http)

#### <a name="apidoc.element.selenium-webdriver.http.Client"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>Client (httpRequest)](#apidoc.element.selenium-webdriver.http.Client)
- description and source-code
```javascript
class Client {

<span class="apidocCodeCommentSpan">  /**
   * Sends a request to the server. The client will automatically follow any
   * redirects returned by the server, fulfilling the returned promise with the
   * final response.
   *
   * @param {!Request} httpRequest The request to send.
   * @return {!Promise<Response>} A promise that will be fulfilled with the
   *     server's response.
   */
</span>  send(httpRequest) {}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.http.Executor"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>Executor (Client|IThenable<!Client>)](#apidoc.element.selenium-webdriver.http.Executor)
- description and source-code
```javascript
class Executor {
<span class="apidocCodeCommentSpan">  /**
   * @param {!(Client|IThenable<!Client>)} client The client to use for sending
   *     requests to the server, or a promise-like object that will resolve to
   *     to the client.
   */
</span>  constructor(client) {
    CLIENTS.set(this, client);

    /**
     * Whether this executor should use the W3C wire protocol. The executor
     * will automatically switch if the remote end sends a compliant response
     * to a new session command, however, this property may be directly set to
     * 'true' to force the executor into W3C mode.
     * @type {boolean}
     */
    this.w3c = false;

    /** @private {Map<string, CommandSpec>} */
    this.customCommands_ = null;

    /** @private {!logging.Logger} */
    this.log_ = logging.getLogger('webdriver.http.Executor');
  }

  /**
   * Defines a new command for use with this executor. When a command is sent,
   * the {@code path} will be preprocessed using the command's parameters; any
   * path segments prefixed with ":" will be replaced by the parameter of the
   * same name. For example, given "/person/:name" and the parameters
   * "{name: 'Bob'}", the final command path will be "/person/Bob".
   *
   * @param {string} name The command name.
   * @param {string} method The HTTP method to use when sending this command.
   * @param {string} path The path to send the command to, relative to
   *     the WebDriver server's command root and of the form
   *     "/path/:variable/segment".
   */
  defineCommand(name, method, path) {
    if (!this.customCommands_) {
      this.customCommands_ = new Map;
    }
    this.customCommands_.set(name, {method, path});
  }

  /** @override */
  execute(command) {
    let request = buildRequest(this.customCommands_, this.w3c, command);
    return request.then(request => {
      this.log_.finer(() => '>>> ${request.method} ${request.path}');
      return doSend(this, request).then(response => {
        this.log_.finer(() => '>>>\n${request}\n<<<\n${response}');

        let parsed =
            parseHttpResponse(
                command, /** @type {!Response} */ (response), this.w3c);

        if (command.getName() === cmd.Name.NEW_SESSION
            || command.getName() === cmd.Name.DESCRIBE_SESSION) {
          if (!parsed || !parsed['sessionId']) {
            throw new error.WebDriverError(
                'Unable to parse new session response: ' + response.body);
          }

          // The remote end is a W3C compliant server if there is no 'status'
          // field in the response. This is not applicable for the DESCRIBE_SESSION
          // command, which is not defined in the W3C spec.
          if (command.getName() === cmd.Name.NEW_SESSION) {
            this.w3c = this.w3c || !('status' in parsed);
          }

          return new Session(parsed['sessionId'], parsed['value']);
        }

        if (parsed
            && typeof parsed === 'object'
            && 'value' in parsed) {
          let value = parsed['value'];
          return typeof value === 'undefined' ? null : value;
        }
        return parsed;
      });
    });
  }
}
```
- example usage
```shell
...
}
    }

    if (url) {
this.log_.fine('Creating session on remote server');
let client = Promise.resolve(url)
    .then(url => new _http.HttpClient(url, this.agent_, this.proxy_));
let executor = new _http.Executor(client);

if (browser === Browser.CHROME) {
  const driver = ensureFileDetectorsAreEnabled(chrome.Driver);
  return createDriver(
      driver, capabilities, executor, this.flow_);
}
...
```

#### <a name="apidoc.element.selenium-webdriver.http.Request"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>Request (method, path, opt_data)](#apidoc.element.selenium-webdriver.http.Request)
- description and source-code
```javascript
class Request {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} method The HTTP method to use for the request.
   * @param {string} path The path on the server to send the request to.
   * @param {Object=} opt_data This request's non-serialized JSON payload data.
   */
</span>  constructor(method, path, opt_data) {
    this.method = /** string */method;
    this.path = /** string */path;
    this.data = /** Object */opt_data;
    this.headers = /** !Map<string, string> */new Map(
        [['Accept', 'application/json; charset=utf-8']]);
  }

  /** @override */
  toString() {
    let ret = '${this.method} ${this.path} HTTP/1.1\n';
    ret += headersToString(this.headers) + '\n\n';
    if (this.data) {
      ret += JSON.stringify(this.data);
    }
    return ret;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.http.Response"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>Response (status, headers, body)](#apidoc.element.selenium-webdriver.http.Response)
- description and source-code
```javascript
class Response {
<span class="apidocCodeCommentSpan">  /**
   * @param {number} status The response code.
   * @param {!Object<string>} headers The response headers. All header names
   *     will be converted to lowercase strings for consistent lookups.
   * @param {string} body The response body.
   */
</span>  constructor(status, headers, body) {
    this.status = /** number */status;
    this.body = /** string */body;
    this.headers = /** !Map<string, string>*/new Map;
    for (let header in headers) {
      this.headers.set(header.toLowerCase(), headers[header]);
    }
  }

  /** @override */
  toString() {
    let ret = 'HTTP/1.1 ${this.status}\n${headersToString(this.headers)}\n\n';
    if (this.body) {
      ret += this.body;
    }
    return ret;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.http.buildPath"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.http.</span>buildPath (path, parameters)](#apidoc.element.selenium-webdriver.http.buildPath)
- description and source-code
```javascript
function buildPath(path, parameters) {
  let pathParameters = path.match(/\/:(\w+)\b/g);
  if (pathParameters) {
    for (let i = 0; i < pathParameters.length; ++i) {
      let key = pathParameters[i].substring(2);  // Trim the /:
      if (key in parameters) {
        let value = parameters[key];
        if (WebElement.isId(value)) {
          // When inserting a WebElement into the URL, only use its ID value,
          // not the full JSON.
          value = WebElement.extractId(value);
        }
        path = path.replace(pathParameters[i], '/' + value);
        delete parameters[key];
      } else {
        throw new error.InvalidArgumentError(
            'Missing required parameter: ' + key);
      }
    }
  }
  return path;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.ie"></a>[module selenium-webdriver.ie](#apidoc.module.selenium-webdriver.ie)

#### <a name="apidoc.element.selenium-webdriver.ie.Driver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.ie.</span>Driver (capabilities.Capabilities|Options)](#apidoc.element.selenium-webdriver.ie.Driver)
- description and source-code
```javascript
class Driver extends webdriver.WebDriver {
<span class="apidocCodeCommentSpan">  /**
   * Creates a new session for Microsoft's Internet Explorer.
   *
   * @param {(capabilities.Capabilities|Options)=} opt_config The configuration
   *     options.
   * @param {promise.ControlFlow=} opt_flow The control flow to use,
   *     or {@code null} to use the currently active flow.
   * @return {!Driver} A new driver instance.
   */
</span>  static createSession(opt_config, opt_flow) {
    var caps = opt_config instanceof Options ?
        opt_config.toCapabilities() :
        (opt_config || capabilities.Capabilities.ie());

    var service = createServiceFromCapabilities(caps);
    var client = service.start().then(url => new http.HttpClient(url));
    var executor = new http.Executor(client);

    return /** @type {!Driver} */(webdriver.WebDriver.createSession(
        executor, caps, opt_flow, this, () => service.kill()));
  }

  /**
   * This function is a no-op as file detectors are not supported by this
   * implementation.
   * @override
   */
  setFileDetector() {}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.ie.Options"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.ie.</span>Options ()](#apidoc.element.selenium-webdriver.ie.Options)
- description and source-code
```javascript
class Options {
  constructor() {
<span class="apidocCodeCommentSpan">    /** @private {!Object<(boolean|number|string|!Array<string>)>} */
</span>    this.options_ = {};

    /** @private {(capabilities.ProxyConfig|null)} */
    this.proxy_ = null;
  }

  /**
   * Extracts the IEDriver specific options from the given capabilities
   * object.
   * @param {!capabilities.Capabilities} caps The capabilities object.
   * @return {!Options} The IEDriver options.
   */
  static fromCapabilities(caps) {
    var options = new Options();
    var map = options.options_;

    Object.keys(Key).forEach(function(key) {
      key = Key[key];
      if (caps.has(key)) {
        map[key] = caps.get(key);
      }
    });

    if (caps.has(capabilities.Capability.PROXY)) {
      options.setProxy(caps.get(capabilities.Capability.PROXY));
    }

    return options;
  }

  /**
   * Whether to disable the protected mode settings check when the session is
   * created. Disbling this setting may lead to significant instability as the
   * browser may become unresponsive/hang. Only "best effort" support is provided
   * when using this capability.
   *
   * For more information, refer to the IEDriver's
   * [required system configuration](http://goo.gl/eH0Yi3).
   *
   * @param {boolean} ignoreSettings Whether to ignore protected mode settings.
   * @return {!Options} A self reference.
   */
  introduceFlakinessByIgnoringProtectedModeSettings(ignoreSettings) {
    this.options_[Key.IGNORE_PROTECTED_MODE_SETTINGS] = !!ignoreSettings;
    return this;
  }

  /**
   * Indicates whether to skip the check that the browser's zoom level is set to
   * 100%.
   *
   * @param {boolean} ignore Whether to ignore the browser's zoom level settings.
   * @return {!Options} A self reference.
   */
  ignoreZoomSetting(ignore) {
    this.options_[Key.IGNORE_ZOOM_SETTING] = !!ignore;
    return this;
  }

  /**
   * Sets the initial URL loaded when IE starts. This is intended to be used with
   * {@link #ignoreProtectedModeSettings} to allow the user to initialize IE in
   * the proper Protected Mode zone. Setting this option may cause browser
   * instability or flaky and unresponsive code. Only "best effort" support is
   * provided when using this option.
   *
   * @param {string} url The initial browser URL.
   * @return {!Options} A self reference.
   */
  initialBrowserUrl(url) {
    this.options_[Key.INITIAL_BROWSER_URL] = url;
    return this;
  }

  /**
   * Configures whether to enable persistent mouse hovering (true by default).
   * Persistent hovering is achieved by continuously firing mouse over events at
   * the last location the mouse cursor has been moved to.
   *
   * @param {boolean} enable Whether to enable persistent hovering.
   * @return {!Options} A self reference.
   */
  enablePersistentHover(enable) {
    this.options_[Key.ENABLE_PERSISTENT_HOVER] = !!enable;
    return this;
  }

  /**
   * Configures whether the driver should attempt to remove obsolete
   * {@linkplain webdriver.WebElement WebElements} from its internal cache on
   * page navigation (true by default). Disabling this option will cause the
   * driver to run with a larger memory footprint.
   *
   * @param {boolean} enable Whether to enable element reference cleanup.
   * @return {!Options} A self reference.
   */
  enableElementCacheCleanup(enable) {
    this.options_[Key.ENABLE_ELEMENT_CACHE_CLEANUP] = !!enable;
    return this;
  }

  /**
   * Configures whether to require the IE window to have input focus before
   * performing any user interactions (i.e. mouse or keyboard events). This
   * option is disabled by default, but delivers much more accurate interaction
   * events when enabled.
   *
   * @param {boolean} require Whether to require window focus.
   * @return {!Options} A self reference.
   */
  requireWindowFocus(require) {
    this.options_[Key.REQUIRE_WINDOW_FOCUS] = !!require;
    return this;
  }

  /**
   * Configures the timeout, in milliseconds, that the driver will attempt to
   * located and attach to a newly opened instance of Internet Explorer. The
   * default is zero, which indicates ...
```
- example usage
```shell
...
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
*     let driver = chrome.Driver.createSession(options, service);
*
* Users should only instantiate the {@link Driver} class directly when they
* need a custom driver service configuration (as shown above). For normal
* operation, users should start Chrome using the
...
```



# <a name="apidoc.module.selenium-webdriver.input"></a>[module selenium-webdriver.input](#apidoc.module.selenium-webdriver.input)

#### <a name="apidoc.element.selenium-webdriver.input.FileDetector"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.input.</span>FileDetector (driver, path)](#apidoc.element.selenium-webdriver.input.FileDetector)
- description and source-code
```javascript
class FileDetector {

<span class="apidocCodeCommentSpan">  /**
   * Handles the file specified by the given path, preparing it for use with
   * the current browser. If the path does not refer to a valid file, it will
   * be returned unchanged, otherwise a path suitable for use with the current
   * browser will be returned.
   *
   * This default implementation is a no-op. Subtypes may override this function
   * for custom tailored file handling.
   *
   * @param {!./webdriver.WebDriver} driver The driver for the current browser.
   * @param {string} path The path to process.
   * @return {!Promise<string>} A promise for the processed file path.
   * @package
   */
</span>  handleFile(driver, path) {
    return Promise.resolve(path);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.logging"></a>[module selenium-webdriver.logging](#apidoc.module.selenium-webdriver.logging)

#### <a name="apidoc.element.selenium-webdriver.logging.Entry"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Entry (!Level|string|number)](#apidoc.element.selenium-webdriver.logging.Entry)
- description and source-code
```javascript
class Entry {
<span class="apidocCodeCommentSpan">  /**
   * @param {(!Level|string|number)} level The entry level.
   * @param {string} message The log message.
   * @param {number=} opt_timestamp The time this entry was generated, in
   *     milliseconds since 0:00:00, January 1, 1970 UTC. If omitted, the
   *     current time will be used.
   * @param {string=} opt_type The log type, if known.
   */
</span>  constructor(level, message, opt_timestamp, opt_type) {
    this.level = level instanceof Level ? level : getLevel(level);
    this.message = message;
    this.timestamp =
        typeof opt_timestamp === 'number' ? opt_timestamp : Date.now();
    this.type = opt_type || '';
  }

  /**
   * @return {{level: string, message: string, timestamp: number,
   *           type: string}} The JSON representation of this entry.
   */
  toJSON() {
    return {
      'level': this.level.name,
      'message': this.message,
      'timestamp': this.timestamp,
      'type': this.type
    };
  }
}
```
- example usage
```shell
...
  let cmd = new command.Command(command.Name.GET_LOG).
      setParameter('type', type);
  return this.driver_.schedule(
      cmd, 'WebDriver.manage().logs().get(' + type + ')').
      then(function(entries) {
        return entries.map(function(entry) {
          if (!(entry instanceof logging.Entry)) {
            return new logging.Entry(
                entry['level'], entry['message'], entry['timestamp'],
                entry['type']);
          }
          return entry;
        });
      });
}
...
```

#### <a name="apidoc.element.selenium-webdriver.logging.Level"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Level (name, level)](#apidoc.element.selenium-webdriver.logging.Level)
- description and source-code
```javascript
class Level {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} name the level's name.
   * @param {number} level the level's numeric value.
   */
</span>  constructor(name, level) {
    if (level < 0) {
      throw new TypeError('Level must be >= 0');
    }

    /** @private {string} */
    this.name_ = name;

    /** @private {number} */
    this.value_ = level;
  }

  /** This logger's name. */
  get name() {
    return this.name_;
  }

  /** The numeric log level. */
  get value() {
    return this.value_;
  }

  /** @override */
  toString() {
    return this.name;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.logging.LogManager"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>LogManager ()](#apidoc.element.selenium-webdriver.logging.LogManager)
- description and source-code
```javascript
class LogManager {
  constructor() {
<span class="apidocCodeCommentSpan">    /** @private {!Map<string, !Logger>} */
</span>    this.loggers_ = new Map;
    this.root_ = new Logger('', Level.OFF);
  }

  /**
   * Retrieves a named logger, creating it in the process. This function will
   * implicitly create the requested logger, and any of its parents, if they
   * do not yet exist.
   *
   * @param {string} name the logger's name.
   * @return {!Logger} the requested logger.
   */
  getLogger(name) {
    if (!name) {
      return this.root_;
    }
    let parent = this.root_;
    for (let i = name.indexOf('.'); i != -1; i = name.indexOf('.', i + 1)) {
      let parentName = name.substr(0, i);
      parent = this.createLogger_(parentName, parent);
    }
    return this.createLogger_(name, parent);
  }

  /**
   * Creates a new logger.
   *
   * @param {string} name the logger's name.
   * @param {!Logger} parent the logger's parent.
   * @return {!Logger} the new logger.
   * @private
   */
  createLogger_(name, parent) {
    if (this.loggers_.has(name)) {
      return /** @type {!Logger} */(this.loggers_.get(name));
    }
    let logger = new Logger(name, null);
    logger.parent_ = parent;
    this.loggers_.set(name, logger);
    return logger;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.logging.Logger"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Logger (name, opt_level)](#apidoc.element.selenium-webdriver.logging.Logger)
- description and source-code
```javascript
class Logger {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} name the name of this logger.
   * @param {Level=} opt_level the initial level for this logger.
   */
</span>  constructor(name, opt_level) {
    /** @private {string} */
    this.name_ = name;

    /** @private {Level} */
    this.level_ = opt_level || null;

    /** @private {Logger} */
    this.parent_ = null;

    /** @private {Set<function(!Entry)>} */
    this.handlers_ = null;
  }

  /** @return {string} the name of this logger. */
  getName() {
    return this.name_;
  }

  /**
   * @param {Level} level the new level for this logger, or 'null' if the logger
   *     should inherit its level from its parent logger.
   */
  setLevel(level) {
    this.level_ = level;
  }

  /** @return {Level} the log level for this logger. */
  getLevel() {
    return this.level_;
  }

  /**
   * @return {!Level} the effective level for this logger.
   */
  getEffectiveLevel() {
    let logger = this;
    let level;
    do {
      level = logger.level_;
      logger = logger.parent_;
    } while (logger && !level);
    return level || Level.OFF;
  }

  /**
   * @param {!Level} level the level to check.
   * @return {boolean} whether messages recorded at the given level are loggable
   *     by this instance.
   */
  isLoggable(level) {
    return level.value !== Level.OFF.value
        && level.value >= this.getEffectiveLevel().value;
  }

  /**
   * Adds a handler to this logger. The handler will be invoked for each message
   * logged with this instance, or any of its descendants.
   *
   * @param {function(!Entry)} handler the handler to add.
   */
  addHandler(handler) {
    if (!this.handlers_) {
      this.handlers_ = new Set;
    }
    this.handlers_.add(handler);
  }

  /**
   * Removes a handler from this logger.
   *
   * @param {function(!Entry)} handler the handler to remove.
   * @return {boolean} whether a handler was successfully removed.
   */
  removeHandler(handler) {
    if (!this.handlers_) {
      return false;
    }
    return this.handlers_.delete(handler);
  }

  /**
   * Logs a message at the given level. The message may be defined as a string
   * or as a function that will return the message. If a function is provided,
   * it will only be invoked if this logger's
   * {@linkplain #getEffectiveLevel() effective log level} includes the given
   * 'level'.
   *
   * @param {!Level} level the level at which to log the message.
   * @param {(string|function(): string)} loggable the message to log, or a
   *     function that will return the message.
   */
  log(level, loggable) {
    if (!this.isLoggable(level)) {
      return;
    }
    let message = '[' + this.name_ + '] '
        + (typeof loggable === 'function' ? loggable() : loggable);
    let entry = new Entry(level, message, Date.now());
    for (let logger = this; !!logger; logger = logger.parent_) {
      if (logger.handlers_) {
        for (let handler of logger.handlers_) {
          handler(entry);
        }
      }
    }
  }

  /**
   * Logs a message at the {@link Level.SEVERE} log level.
   * @param {(string|function(): string)} loggable the message to log, or a
   *     function that will return the message.
   */
  severe(loggable) {
    this.log(Level.SEVERE, loggable);
  }

  /**
   * Logs a message at the {@link Level.WARNING} log level.
   * @param {(string|function(): string)} loggable the message to log, or a
   *     function that will return the message.
   */
  warning(loggable) {
    this.log(Level.WARNING, loggable);
  }

  /**
   * Logs a message at the {@link Level.INFO} log level.
   * @param {(string|function(): string)} loggable the message to log, or a
   *     function that will return the message.
   */
  info(loggable) {
    this.log(Level.INFO, loggable);
  }

  /**
   * Logs a message at the {@link Level.DEBUG} log level.
   * @param {(string|function(): string)} loggable the message to log, or a
   *     function that will return the message.
   */
  debug(loggable) {
    this.log(Level.DEBUG, loggable);
  }

  /**
   * Logs a message at the {@link Level.FINE} log level.
   * @param { ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.logging.Preferences"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>Preferences ()](#apidoc.element.selenium-webdriver.logging.Preferences)
- description and source-code
```javascript
class Preferences {
  constructor() {
<span class="apidocCodeCommentSpan">    /** @private {!Map<string, !Level>} */
</span>    this.prefs_ = new Map;
  }

  /**
   * Sets the desired logging level for a particular log type.
   * @param {(string|Type)} type The log type.
   * @param {(!Level|string|number)} level The desired log level.
   * @throws {TypeError} if 'type' is not a 'string'.
   */
  setLevel(type, level) {
    if (typeof type !== 'string') {
      throw TypeError('specified log type is not a string: ' + typeof type);
    }
    this.prefs_.set(type, level instanceof Level ? level : getLevel(level));
  }

  /**
   * Converts this instance to its JSON representation.
   * @return {!Object<string, string>} The JSON representation of this set of
   *     preferences.
   */
  toJSON() {
    let json = {};
    for (let key of this.prefs_.keys()) {
      json[key] = this.prefs_.get(key).name;
    }
    return json;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.logging.addConsoleHandler"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>addConsoleHandler (opt_logger)](#apidoc.element.selenium-webdriver.logging.addConsoleHandler)
- description and source-code
```javascript
function addConsoleHandler(opt_logger) {
  let logger = opt_logger || logManager.root_;
  logger.addHandler(consoleHandler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.logging.getLevel"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>getLevel (nameOrValue)](#apidoc.element.selenium-webdriver.logging.getLevel)
- description and source-code
```javascript
function getLevel(nameOrValue) {
  if (typeof nameOrValue === 'string') {
    return LEVELS_BY_NAME.get(nameOrValue) || Level.ALL;
  }
  if (typeof nameOrValue !== 'number') {
    throw new TypeError('not a string or number');
  }
  for (let level of ALL_LEVELS) {
    if (nameOrValue >= level.value) {
      return level;
    }
  }
  return Level.ALL;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.logging.getLogger"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>getLogger (name)](#apidoc.element.selenium-webdriver.logging.getLogger)
- description and source-code
```javascript
function getLogger(name) {
  return logManager.getLogger(name);
}
```
- example usage
```shell
...
 *     SELENIUM_BROWSER=chrome:36:LINUX \
 *     SELENIUM_SERVER_JAR=/path/to/selenium-server-standalone.jar \
 *     node mytest.js
 */
class Builder {
  constructor() {
/** @private @const */
this.log_ = logging.getLogger('webdriver.Builder');

/** @private {promise.ControlFlow} */
this.flow_ = null;

/** @private {string} */
this.url_ = '';
...
```

#### <a name="apidoc.element.selenium-webdriver.logging.installConsoleHandler"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>installConsoleHandler ()](#apidoc.element.selenium-webdriver.logging.installConsoleHandler)
- description and source-code
```javascript
function installConsoleHandler() {
  addConsoleHandler(logManager.root_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.logging.removeConsoleHandler"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.logging.</span>removeConsoleHandler (opt_logger)](#apidoc.element.selenium-webdriver.logging.removeConsoleHandler)
- description and source-code
```javascript
function removeConsoleHandler(opt_logger) {
  let logger = opt_logger || logManager.root_;
  logger.removeHandler(consoleHandler);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.opera"></a>[module selenium-webdriver.opera](#apidoc.module.selenium-webdriver.opera)

#### <a name="apidoc.element.selenium-webdriver.opera.Driver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>Driver (capabilities.Capabilities|Options)](#apidoc.element.selenium-webdriver.opera.Driver)
- description and source-code
```javascript
class Driver extends webdriver.WebDriver {
<span class="apidocCodeCommentSpan">  /**
   * Creates a new session for Opera.
   *
   * @param {(capabilities.Capabilities|Options)=} opt_config The configuration
   *     options.
   * @param {remote.DriverService=} opt_service The session to use; will use
   *     the {@link getDefaultService default service} by default.
   * @param {promise.ControlFlow=} opt_flow The control flow to use,
   *     or {@code null} to use the currently active flow.
   * @return {!Driver} A new driver instance.
   */
</span>  static createSession(opt_config, opt_service, opt_flow) {
    var service = opt_service || getDefaultService();
    var client = service.start().then(url => new http.HttpClient(url));
    var executor = new http.Executor(client);

    var caps =
        opt_config instanceof Options ? opt_config.toCapabilities() :
        (opt_config || capabilities.Capabilities.opera());

    // On Linux, the OperaDriver does not look for Opera on the PATH, so we
    // must explicitly find it. See: operachromiumdriver #9.
    if (process.platform === 'linux') {
      var options = Options.fromCapabilities(caps);
      if (!options.binary_) {
        let exe = io.findInPath('opera', true);
        if (!exe) {
          throw Error(
              'The opera executable could not be found on the current PATH');
        }
        options.setOperaBinaryPath(exe);
      }
      caps = options.toCapabilities(caps);
    }

    return /** @type {!Driver} */(
        webdriver.WebDriver.createSession(executor, caps, opt_flow, this));
  }

  /**
   * This function is a no-op as file detectors are not supported by this
   * implementation.
   * @override
   */
  setFileDetector() {}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.opera.Options"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>Options ()](#apidoc.element.selenium-webdriver.opera.Options)
- description and source-code
```javascript
class Options {
  constructor() {
<span class="apidocCodeCommentSpan">    /** @private {!Array.<string>} */
</span>    this.args_ = [];

    /** @private {?string} */
    this.binary_ = null;

    /** @private {!Array.<(string|!Buffer)>} */
    this.extensions_ = [];

    /** @private {./lib/logging.Preferences} */
    this.logPrefs_ = null;

    /** @private {?capabilities.ProxyConfig} */
    this.proxy_ = null;
  }

  /**
   * Extracts the OperaDriver specific options from the given capabilities
   * object.
   * @param {!capabilities.Capabilities} caps The capabilities object.
   * @return {!Options} The OperaDriver options.
   */
  static fromCapabilities(caps) {
    var options;
    var o = caps.get(OPTIONS_CAPABILITY_KEY);
    if (o instanceof Options) {
      options = o;
    } else if (o) {
      options = new Options()
          .addArguments(o.args || [])
          .addExtensions(o.extensions || [])
          .setOperaBinaryPath(o.binary);
    } else {
      options = new Options;
    }

    if (caps.has(capabilities.Capability.PROXY)) {
      options.setProxy(caps.get(capabilities.Capability.PROXY));
    }

    if (caps.has(capabilities.Capability.LOGGING_PREFS)) {
      options.setLoggingPrefs(
          caps.get(capabilities.Capability.LOGGING_PREFS));
    }

    return options;
  }

  /**
   * Add additional command line arguments to use when launching the Opera
   * browser.  Each argument may be specified with or without the "--" prefix
   * (e.g. "--foo" and "foo"). Arguments with an associated value should be
   * delimited by an "=": "foo=bar".
   * @param {...(string|!Array.<string>)} var_args The arguments to add.
   * @return {!Options} A self reference.
   */
  addArguments(var_args) {
    this.args_ = this.args_.concat.apply(this.args_, arguments);
    return this;
  }

  /**
   * Add additional extensions to install when launching Opera. Each extension
   * should be specified as the path to the packed CRX file, or a Buffer for an
   * extension.
   * @param {...(string|!Buffer|!Array.<(string|!Buffer)>)} var_args The
   *     extensions to add.
   * @return {!Options} A self reference.
   */
  addExtensions(var_args) {
    this.extensions_ = this.extensions_.concat.apply(
        this.extensions_, arguments);
    return this;
  }

  /**
   * Sets the path to the Opera binary to use. On Mac OS X, this path should
   * reference the actual Opera executable, not just the application binary. The
   * binary path be absolute or relative to the operadriver server executable, but
   * it must exist on the machine that will launch Opera.
   *
   * @param {string} path The path to the Opera binary to use.
   * @return {!Options} A self reference.
   */
  setOperaBinaryPath(path) {
    this.binary_ = path;
    return this;
  }

  /**
   * Sets the logging preferences for the new session.
   * @param {!./lib/logging.Preferences} prefs The logging preferences.
   * @return {!Options} A self reference.
   */
  setLoggingPrefs(prefs) {
    this.logPrefs_ = prefs;
    return this;
  }

  /**
   * Sets the proxy settings for the new session.
   * @param {capabilities.ProxyConfig} proxy The proxy configuration to use.
   * @return {!Options} A self reference.
   */
  setProxy(proxy) {
    this.proxy_ = proxy;
    return this;
  }

  /**
   * Converts this options instance to a {@link capabilities.Capabilities}
   *     object.
   * @param {capabilities.Capabilities=} opt_capabilities The capabilities to
   *     merge these options into, if any.
   * @return {!capabilities.Capabilities} The capabilities.
   */
  toCapabilities(opt_capabilities) {
    var caps = opt_capabilities || capabilities.Capabilities.opera();
    caps.
        set(capabilities.Capability.PROXY, this.proxy_).
        set(capabilities.Capability.LOGGING_PREFS, this.logPrefs_).
        set(OPTIONS_CAPABILITY_KEY, this);
    return caps;
  }

  /**
   * Converts this instance to its JSON wire protocol representation. Note this
   * function is an implementation not intended for general use.
   * @return {!Object} The JSON wire protocol representation of this instance.
   */
  [Symbols. ...
```
- example usage
```shell
...
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
*     let driver = chrome.Driver.createSession(options, service);
*
* Users should only instantiate the {@link Driver} class directly when they
* need a custom driver service configuration (as shown above). For normal
* operation, users should start Chrome using the
...
```

#### <a name="apidoc.element.selenium-webdriver.opera.ServiceBuilder"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>ServiceBuilder (opt_exe)](#apidoc.element.selenium-webdriver.opera.ServiceBuilder)
- description and source-code
```javascript
class ServiceBuilder extends remote.DriverService.Builder {
<span class="apidocCodeCommentSpan">  /**
   * @param {string=} opt_exe Path to the server executable to use. If omitted,
   *     the builder will attempt to locate the operadriver on the current
   *     PATH.
   * @throws {Error} If provided executable does not exist, or the operadriver
   *     cannot be found on the PATH.
   */
</span>  constructor(opt_exe) {
    let exe = opt_exe || io.findInPath(OPERADRIVER_EXE, true);
    if (!exe) {
      throw Error(
          'The OperaDriver could not be found on the current PATH. Please ' +
          'download the latest version of the OperaDriver from ' +
          'https://github.com/operasoftware/operachromiumdriver/releases and ' +
          'ensure it can be found on your PATH.');
    }

    super(exe);
    this.setLoopback(true);
  }

  /**
   * Sets the path of the log file the driver should log to. If a log file is
   * not specified, the driver will log to stderr.
   * @param {string} path Path of the log file to use.
   * @return {!ServiceBuilder} A self reference.
   */
  loggingTo(path) {
    return this.addArguments('--log-path=' + path);
  }

  /**
   * Enables verbose logging.
   * @return {!ServiceBuilder} A self reference.
   */
  enableVerboseLogging() {
    return this.addArguments('--verbose');
  }

  /**
   * Silence sthe drivers output.
   * @return {!ServiceBuilder} A self reference.
   */
  silent() {
    return this.addArguments('--silent');
  }
}
```
- example usage
```shell
...
* with {@link #setDefaultService setDefaultService()}.
*
* You may also create a {@link Driver} with its own driver service. This is
* useful if you need to capture the server's log output for a specific session:
*
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
...
```

#### <a name="apidoc.element.selenium-webdriver.opera.getDefaultService"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>getDefaultService ()](#apidoc.element.selenium-webdriver.opera.getDefaultService)
- description and source-code
```javascript
function getDefaultService() {
  if (!defaultService) {
    defaultService = new ServiceBuilder().build();
  }
  return defaultService;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.opera.setDefaultService"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.opera.</span>setDefaultService (service)](#apidoc.element.selenium-webdriver.opera.setDefaultService)
- description and source-code
```javascript
function setDefaultService(service) {
  if (defaultService && defaultService.isRunning()) {
    throw Error(
        'The previously configured OperaDriver service is still running. ' +
        'You must shut it down before you may adjust its configuration.');
  }
  defaultService = service;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.phantomjs"></a>[module selenium-webdriver.phantomjs](#apidoc.module.selenium-webdriver.phantomjs)

#### <a name="apidoc.element.selenium-webdriver.phantomjs.Driver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.phantomjs.</span>Driver (opt_capabilities, opt_flow, opt_logFile)](#apidoc.element.selenium-webdriver.phantomjs.Driver)
- description and source-code
```javascript
class Driver extends webdriver.WebDriver {
<span class="apidocCodeCommentSpan">  /**
   * Creates a new PhantomJS session.
   *
   * @param {capabilities.Capabilities=} opt_capabilities The desired
   *     capabilities.
   * @param {promise.ControlFlow=} opt_flow The control flow to use,
   *     or {@code null} to use the currently active flow.
   * @param {string=} opt_logFile Path to the log file for the phantomjs
   *     executable's output. For convenience, this may be set at runtime with
   *     the 'SELENIUM_PHANTOMJS_LOG' environment variable.
   * @return {!Driver} A new driver reference.
   */
</span>  static createSession(opt_capabilities, opt_flow, opt_logFile) {
    // TODO: add an Options class for consistency with the other driver types.

    var caps = opt_capabilities || capabilities.Capabilities.phantomjs();
    var exe = findExecutable(caps.get(BINARY_PATH_CAPABILITY));
    var args = [];

    var logPrefs = caps.get(capabilities.Capability.LOGGING_PREFS);
    if (logPrefs instanceof logging.Preferences) {
      logPrefs = logPrefs.toJSON();
    }

    if (logPrefs && logPrefs[logging.Type.DRIVER]) {
      let level = WEBDRIVER_TO_PHANTOMJS_LEVEL.get(
          logPrefs[logging.Type.DRIVER]);
      if (level) {
        args.push('--webdriver-loglevel=' + level);
      }
    }

    opt_logFile = process.env['SELENIUM_PHANTOMJS_LOG'] || opt_logFile;
    if (typeof opt_logFile === 'string') {
      args.push('--webdriver-logfile=' + opt_logFile);
    }

    var proxy = caps.get(capabilities.Capability.PROXY);
    if (proxy) {
      switch (proxy.proxyType) {
        case 'manual':
          if (proxy.httpProxy) {
            args.push(
                '--proxy-type=http',
                '--proxy=' + proxy.httpProxy);
            console.log(args);
          }
          break;
        case 'pac':
          throw Error('PhantomJS does not support Proxy PAC files');
        case 'system':
          args.push('--proxy-type=system');
          break;
        case 'direct':
          args.push('--proxy-type=none');
          break;
      }
    }
    args = args.concat(caps.get(CLI_ARGS_CAPABILITY) || []);

    var port = portprober.findFreePort();
    var service = new remote.DriverService(exe, {
      port: port,
      args: Promise.resolve(port).then(function(port) {
        args.push('--webdriver=' + port);
        return args;
      })
    });

    var executor = createExecutor(service.start());
    return /** @type {!Driver} */(webdriver.WebDriver.createSession(
        executor, caps, opt_flow, this, () => service.kill()));
  }

  /**
   * This function is a no-op as file detectors are not supported by this
   * implementation.
   * @override
   */
  setFileDetector() {}

  /**
   * Executes a PhantomJS fragment. This method is similar to
   * {@link #executeScript}, except it exposes the
   * <a href="http://phantomjs.org/api/">PhantomJS API</a> to the injected
   * script.
   *
   * <p>The injected script will execute in the context of PhantomJS's
   * {@code page} variable. If a page has not been loaded before calling this
   * method, one will be created.</p>
   *
   * <p>Be sure to wrap callback definitions in a try/catch block, as failures
   * may cause future WebDriver calls to fail.</p>
   *
   * <p>Certain callbacks are used by GhostDriver (the PhantomJS WebDriver
   * implementation) and overriding these may cause the script to fail. It is
   * recommended that you check for existing callbacks before defining your own.
   * </p>
   *
   * As with {@link #executeScript}, the injected script may be defined as
   * a string for an anonymous function body (e.g. "return 123;"), or as a
   * function. If a function is provided, it will be decompiled to its original
   * source. Note that injecting functions is provided as a convenience to
   * simplify defining complex scripts. Care must be taken that the function
   * only references variables that will be defined in the page's scope and
   * that the function does not override {@code Function.prototype.toString}
   * (overriding toString() will interfere with how the function is
   * de ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.portprober"></a>[module selenium-webdriver.portprober](#apidoc.module.selenium-webdriver.portprober)

#### <a name="apidoc.element.selenium-webdriver.portprober.findFreePort"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.portprober.</span>findFreePort (opt_host)](#apidoc.element.selenium-webdriver.portprober.findFreePort)
- description and source-code
```javascript
function findFreePort(opt_host) {
  return findSystemPortRange().then(function(range) {
    var attempts = 0;
    return new Promise((resolve, reject) => {
      findPort();

      function findPort() {
        attempts += 1;
        if (attempts > 10) {
          reject(Error('Unable to find a free port'));
        }

        var port = Math.floor(
            Math.random() * (range.max - range.min) + range.min);
        isFree(port, opt_host).then(function(isFree) {
          if (isFree) {
            resolve(port);
          } else {
            findPort();
          }
        });
      }
    });
  });
}
```
- example usage
```shell
...
if (capabilities.has(Key.EXTRACT_PATH)) {
  args.push('--extract-path=' + capabilities.get(Key.EXTRACT_PATH));
}
if (capabilities.get(Key.SILENT)) {
  args.push('--silent');
}

var port = portprober.findFreePort();
return new remote.DriverService(exe, {
  loopback: true,
  port: port,
  args: port.then(function(port) {
    return args.concat('--port=' + port);
  }),
  stdio: 'ignore'
...
```

#### <a name="apidoc.element.selenium-webdriver.portprober.isFree"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.portprober.</span>isFree (port, opt_host)](#apidoc.element.selenium-webdriver.portprober.isFree)
- description and source-code
```javascript
function isFree(port, opt_host) {
  return new Promise((resolve, reject) => {
    let server = net.createServer().on('error', function(e) {
      if (e.code === 'EADDRINUSE') {
        resolve(false);
      } else {
        reject(e);
      }
    });

    server.listen(port, opt_host, function() {
      server.close(() => resolve(true));
    });
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.profile"></a>[module selenium-webdriver.profile](#apidoc.module.selenium-webdriver.profile)

#### <a name="apidoc.element.selenium-webdriver.profile.Profile"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.profile.</span>Profile (opt_dir)](#apidoc.element.selenium-webdriver.profile.Profile)
- description and source-code
```javascript
class Profile {
<span class="apidocCodeCommentSpan">  /**
   * @param {string=} opt_dir Path to an existing Firefox profile directory to
   *     use a template for this profile. If not specified, a blank profile will
   *     be used.
   */
</span>  constructor(opt_dir) {
    /** @private {!Object} */
    this.preferences_ = {};

    /** @private {boolean} */
    this.nativeEventsEnabled_ = true;

    /** @private {(string|undefined)} */
    this.template_ = opt_dir;

    /** @private {number} */
    this.port_ = 0;

    /** @private {!Array<string>} */
    this.extensions_ = [];
  }

  /**
   * @return {(string|undefined)} Path to an existing Firefox profile directory
   *     to use as a template when writing this Profile to disk.
   */
  getTemplateDir() {
    return this.template_;
  }

  /**
   * Registers an extension to be included with this profile.
   * @param {string} extension Path to the extension to include, as either an
   *     unpacked extension directory or the path to a xpi file.
   */
  addExtension(extension) {
    this.extensions_.push(extension);
  }

  /**
   * @return {!Array<string>} A list of extensions to install in this profile.
   */
  getExtensions() {
    return this.extensions_;
  }

  /**
   * Sets a desired preference for this profile.
   * @param {string} key The preference key.
   * @param {(string|number|boolean)} value The preference value.
   * @throws {Error} If attempting to set a frozen preference.
   */
  setPreference(key, value) {
    var frozen = getDefaultPreferences()['frozen'];
    if (frozen.hasOwnProperty(key) && frozen[key] !== value) {
      throw Error('You may not set ' + key + '=' + JSON.stringify(value)
          + '; value is frozen for proper WebDriver functionality ('
          + key + '=' + JSON.stringify(frozen[key]) + ')');
    }
    this.preferences_[key] = value;
  }

  /**
   * Returns the currently configured value of a profile preference. This does
   * not include any defaults defined in the profile's template directory user.js
   * file (if a template were specified on construction).
   * @param {string} key The desired preference.
   * @return {(string|number|boolean|undefined)} The current value of the
   *     requested preference.
   */
  getPreference(key) {
    return this.preferences_[key];
  }

  /**
   * @return {!Object} A copy of all currently configured preferences.
   */
  getPreferences() {
    return Object.assign({}, this.preferences_);
  }

  /**
   * Specifies which host the driver should listen for commands on. If not
   * specified, the driver will default to "localhost". This option should be
   * specified when "localhost" is not mapped to the loopback address
   * (127.0.0.1) in '/etc/hosts'.
   *
   * @param {string} host the host the driver should listen for commands on
   */
  setHost(host) {
    this.preferences_['webdriver_firefox_allowed_hosts'] = host;
  }

  /**
   * @return {number} The port this profile is currently configured to use, or
   *     0 if the port will be selected at random when the profile is written
   *     to disk.
   */
  getPort() {
    return this.port_;
  }

  /**
   * Sets the port to use for the WebDriver extension loaded by this profile.
   * @param {number} port The desired port, or 0 to use any free port.
   */
  setPort(port) {
    this.port_ = port;
  }

  /**
   * @return {boolean} Whether the FirefoxDriver is configured to automatically
   *     accept untrusted SSL certificates.
   */
  acceptUntrustedCerts() {
    return !!this.preferences_['webdriver_accept_untrusted_certs'];
  }

  /**
   * Sets whether the FirefoxDriver should automatically accept untrusted SSL
   * certificates.
   * @param {boolean} value .
   */
  setAcceptUntrustedCerts(value) {
    this.preferences_['webdriver_accept_untrusted_certs'] = !!value;
  }

  /**
   * Sets whether to assume untrusted certificates come from untrusted issuers.
   * @param {boolean} value .
   */
  setAssumeUntrustedCertIssuer(value) {
    this.preferences_['webdriver_assume_untrusted_issuer'] = !!value;
  }

  /**
   * @return {boolean} Whether to assume untrusted certs come from ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.profile.decode"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.profile.</span>decode (data)](#apidoc.element.selenium-webdriver.profile.decode)
- description and source-code
```javascript
function decode(data) {
  return io.tmpFile().then(function(file) {
    var buf = new Buffer(data, 'base64');
    return io.write(file, buf)
        .then(io.tmpDir)
        .then(function(dir) {
          var zip = new AdmZip(file);
          zip.extractAllTo(dir);  // Sync only? Why?? :-(
          return dir;
        });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.profile.loadUserPrefs"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.profile.</span>loadUserPrefs (f)](#apidoc.element.selenium-webdriver.profile.loadUserPrefs)
- description and source-code
```javascript
function loadUserPrefs(f) {
  return io.read(f).then(
      function onSuccess(contents) {
        var prefs = {};
        var context = vm.createContext({
          'user_pref': function(key, value) {
            prefs[key] = value;
          }
        });
        vm.runInContext(contents.toString(), context, f);
        return prefs;
      },
      function onError(err) {
        if (err && err.code === 'ENOENT') {
          return {};
        }
        throw err;
      });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.promise"></a>[module selenium-webdriver.promise](#apidoc.module.selenium-webdriver.promise)

#### <a name="apidoc.element.selenium-webdriver.promise.CancellableThenable"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>CancellableThenable (new: CancellableThenable, ...?)](#apidoc.element.selenium-webdriver.promise.CancellableThenable)
- description and source-code
```javascript
class CancellableThenable {
<span class="apidocCodeCommentSpan">  /**
   * @param {function(new: CancellableThenable, ...?)} ctor
   */
</span>  static addImplementation(ctor) {
    Thenable.addImplementation(ctor);
    addMarkerSymbol(ctor, CANCELLABLE_SYMBOL);
  }

  /**
   * @param {*} object
   * @return {boolean}
   */
  static isImplementation(object) {
    return hasMarkerSymbol(object, CANCELLABLE_SYMBOL);
  }

  /**
   * Requests the cancellation of the computation of this promise's value,
   * rejecting the promise in the process. This method is a no-op if the promise
   * has already been resolved.
   *
   * @param {(string|Error)=} opt_reason The reason this promise is being
   *     cancelled. This value will be wrapped in a {@link CancellationError}.
   */
  cancel(opt_reason) {}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.CancellationError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>CancellationError (opt_msg)](#apidoc.element.selenium-webdriver.promise.CancellationError)
- description and source-code
```javascript
class CancellationError extends Error {
<span class="apidocCodeCommentSpan">  /**
   * @param {string=} opt_msg The cancellation message.
   */
</span>  constructor(opt_msg) {
    super(opt_msg);

    /** @override */
    this.name = this.constructor.name;

    /** @private {boolean} */
    this.silent_ = false;
  }

  /**
   * Wraps the given error in a CancellationError.
   *
   * @param {*} error The error to wrap.
   * @param {string=} opt_msg The prefix message to use.
   * @return {!CancellationError} A cancellation error.
   */
  static wrap(error, opt_msg) {
    var message;
    if (error instanceof CancellationError) {
      return new CancellationError(
          opt_msg ? (opt_msg + ': ' + error.message) : error.message);
    } else if (opt_msg) {
      message = opt_msg;
      if (error) {
        message += ': ' + error;
      }
      return new CancellationError(message);
    }
    if (error) {
      message = error + '';
    }
    return new CancellationError(message);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.ControlFlow"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>ControlFlow ()](#apidoc.element.selenium-webdriver.promise.ControlFlow)
- description and source-code
```javascript
class ControlFlow extends events.EventEmitter {
  constructor() {
    if (!usePromiseManager()) {
      throw TypeError(
          'Cannot instantiate control flow when the promise manager has'
              + ' been disabled');
    }

    super();

<span class="apidocCodeCommentSpan">    /** @private {boolean} */
</span>    this.propagateUnhandledRejections_ = true;

    /** @private {TaskQueue} */
    this.activeQueue_ = null;

    /** @private {Set<TaskQueue>} */
    this.taskQueues_ = null;

    /**
     * Microtask that controls shutting down the control flow. Upon shut down,
     * the flow will emit an
     * {@link ControlFlow.EventType.IDLE} event. Idle events
     * always follow a brief timeout in order to catch latent errors from the
     * last completed task. If this task had a callback registered, but no
     * errback, and the task fails, the unhandled failure would not be reported
     * by the promise system until the next turn of the event loop:
     *
     *   // Schedule 1 task that fails.
     *   var result = promise.controlFlow().execute(
     *       () => promise.rejected('failed'), 'example');
     *   // Set a callback on the result. This delays reporting the unhandled
     *   // failure for 1 turn of the event loop.
     *   result.then(function() {});
     *
     * @private {MicroTask}
     */
    this.shutdownTask_ = null;

    /**
     * ID for a long running interval used to keep a Node.js process running
     * while a control flow's event loop is still working. This is a cheap hack
     * required since JS events are only scheduled to run when there is
     * _actually_ something to run. When a control flow is waiting on a task,
     * there will be nothing in the JS event loop and the process would
     * terminate without this.
     * @private
     */
    this.hold_ = null;
  }

  /**
   * Returns a string representation of this control flow, which is its current
   * {@linkplain #getSchedule() schedule}, sans task stack traces.
   * @return {string} The string representation of this control flow.
   * @override
   */
  toString() {
    return this.getSchedule();
  }

  /**
   * Sets whether any unhandled rejections should propagate up through the
   * control flow stack and cause rejections within parent tasks. If error
   * propagation is disabled, tasks will not be aborted when an unhandled
   * promise rejection is detected, but the rejection _will_ trigger an
   * {@link ControlFlow.EventType.UNCAUGHT_EXCEPTION} event.
   *
   * The default behavior is to propagate all unhandled rejections. _The use
   * of this option is highly discouraged._
   *
   * @param {boolean} propagate whether to propagate errors.
   */
  setPropagateUnhandledRejections(propagate) {
    this.propagateUnhandledRejections_ = propagate;
  }

  /**
   * @return {boolean} Whether this flow is currently idle.
   */
  isIdle() {
    return !this.shutdownTask_ && (!this.taskQueues_ || !this.taskQueues_.size);
  }

  /**
   * Resets this instance, clearing its queue and removing all event listeners.
   */
  reset() {
    this.cancelQueues_(new FlowResetError);
    this.emit(ControlFlow.EventType.RESET);
    this.removeAllListeners();
    this.cancelShutdown_();
  }

  /**
   * Generates an annotated string describing the internal state of this control
   * flow, including the currently executing as well as pending tasks. If
   * {@code opt_includeStackTraces === true}, the string will include the
   * stack trace from when each task was scheduled.
   * @param {string=} opt_includeStackTraces Whether to include the stack traces
   * from when each task was scheduled. Defaults to false.
   * @return {string} String representation of this flow's internal state.
   */
  getSchedule(opt_includeStackTraces) {
    var ret = 'ControlFlow::' + getUid(this);
    var activeQueue = this.activeQueue_;
    if (!this.taskQueues_ || !this.taskQueues_.size) {
      return ret;
    }
    var childIndent = '| ';
    for (var q of this.taskQueues_) {
      ret += '\n' + printQ(q, childIndent);
    }
    return ret;

    function printQ(q, indent) {
      var ret = q.toStri ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.Deferred"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Deferred (opt_flow, opt_skipLog)](#apidoc.element.selenium-webdriver.promise.Deferred)
- description and source-code
```javascript
class Deferred {
<span class="apidocCodeCommentSpan">  /**
   * @param {ControlFlow=} opt_flow The control flow this instance was
   *     created under. This should only be provided during unit tests.
   * @param {?=} opt_skipLog An internal parameter used to skip logging the
   *     creation of this promise. This parameter has no effect unless it is
   *     strictly equal to an internal symbol. In other words, this parameter
   *     is always ignored for external code.
   */
</span>  constructor(opt_flow, opt_skipLog) {
    var fulfill, reject;

    /** @type {!ManagedPromise<T>} */
    this.promise = new ManagedPromise(function(f, r) {
      fulfill = f;
      reject = r;
    }, opt_flow, opt_skipLog);

    var self = this;
    var checkNotSelf = function(value) {
      if (value === self) {
        throw new TypeError('May not resolve a Deferred with itself');
      }
    };

    /**
     * Resolves this deferred with the given value. It is safe to call this as a
     * normal function (with no bound "this").
     * @param {(T|IThenable<T>|Thenable)=} opt_value The fulfilled value.
     * @const
     */
    this.resolve = function(opt_value) {
      checkNotSelf(opt_value);
      fulfill(opt_value);
    };

    /**
     * An alias for {@link #resolve}.
     * @const
     */
    this.fulfill = this.resolve;

    /**
     * Rejects this promise with the given reason. It is safe to call this as a
     * normal function (with no bound "this").
     * @param {*=} opt_reason The rejection reason.
     * @const
     */
    this.reject = function(opt_reason) {
      checkNotSelf(opt_reason);
      reject(opt_reason);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.MultipleUnhandledRejectionError"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>MultipleUnhandledRejectionError (Set<*>)](#apidoc.element.selenium-webdriver.promise.MultipleUnhandledRejectionError)
- description and source-code
```javascript
class MultipleUnhandledRejectionError extends Error {
<span class="apidocCodeCommentSpan">  /**
   * @param {!(Set<*>)} errors The errors to report.
   */
</span>  constructor(errors) {
    super('Multiple unhandled promise rejections reported');

    /** @override */
    this.name = this.constructor.name;

    /** @type {!Set<*>} */
    this.errors = errors;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.Promise"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Promise ( * function((T|IThenable<T>|Thenable)](#apidoc.element.selenium-webdriver.promise.Promise)
- description and source-code
```javascript
class ManagedPromise {
<span class="apidocCodeCommentSpan">  /**
   * @param {function( * function((T|IThenable<T>|Thenable)=),
   *           function(*=))} resolver
   *     Function that is invoked immediately to begin computation of this
   *     promise's value. The function should accept a pair of callback
   *     functions, one for fulfilling the promise and another for rejecting it.
   * @param {ControlFlow=} opt_flow The control flow
   *     this instance was created under. Defaults to the currently active flow.
   * @param {?=} opt_skipLog An internal parameter used to skip logging the
   *     creation of this promise. This parameter has no effect unless it is
   *     strictly equal to an internal symbol. In other words, this parameter
   *     is always ignored for external code.
   */
</span>  constructor(resolver, opt_flow, opt_skipLog) {
    if (!usePromiseManager()) {
      throw TypeError(
        'Unable to create a managed promise instance: the promise manager has'
            + ' been disabled by the SELENIUM_PROMISE_MANAGER environment'
            + ' variable: ' + process.env['SELENIUM_PROMISE_MANAGER']);
    } else if (opt_skipLog !== SKIP_LOG) {
      FLOW_LOG.warning(() => {
        let e =
            captureStackTrace(
                'ManagedPromiseError',
                'Creating a new managed Promise. This call will fail when the'
                    + ' promise manager is disabled',
            ManagedPromise)
        return e.stack;
      });
    }

    getUid(this);

    /** @private {!ControlFlow} */
    this.flow_ = opt_flow || controlFlow();

    /** @private {Error} */
    this.stack_ = null;
    if (LONG_STACK_TRACES) {
      this.stack_ = captureStackTrace('ManagedPromise', 'new', this.constructor);
    }

    /** @private {Thenable<?>} */
    this.parent_ = null;

    /** @private {Array<!Task>} */
    this.callbacks_ = null;

    /** @private {PromiseState} */
    this.state_ = PromiseState.PENDING;

    /** @private {boolean} */
    this.handled_ = false;

    /** @private {*} */
    this.value_ = undefined;

    /** @private {TaskQueue} */
    this.queue_ = null;

    try {
      var self = this;
      resolver(function(value) {
        self.resolve_(PromiseState.FULFILLED, value);
      }, function(reason) {
        self.resolve_(PromiseState.REJECTED, reason);
      });
    } catch (ex) {
      this.resolve_(PromiseState.REJECTED, ex);
    }
  }

  /**
   * Creates a promise that is immediately resolved with the given value.
   *
   * @param {T=} opt_value The value to resolve.
   * @return {!ManagedPromise<T>} A promise resolved with the given value.
   * @template T
   */
  static resolve(opt_value) {
    if (opt_value instanceof ManagedPromise) {
      return opt_value;
    }
    return new ManagedPromise(resolve => resolve(opt_value));
  }

  /**
   * Creates a promise that is immediately rejected with the given reason.
   *
   * @param {*=} opt_reason The rejection reason.
   * @return {!ManagedPromise<?>} A new rejected promise.
   */
  static reject(opt_reason) {
    return new ManagedPromise((_, reject) => reject(opt_reason));
  }

  /** @override */
  toString() {
    return 'ManagedPromise::' + getUid(this) +
      ' {[[PromiseStatus]]: "' + this.state_ + '"}';
  }

  /**
   * Resolves this promise. If the new value is itself a promise, this function
   * will wait for it to be resolved before notifying the registered listeners.
   * @param {PromiseState} newState The promise's new state.
   * @param {*} newValue The promise's new value.
   * @throws {TypeError} If {@code newValue === this}.
   * @private
   */
  resolve_(newState, newValue) {
    if (PromiseState.PENDING !== this.state_) {
      return;
    }

    if (newValue === this) {
      // See promise a+, 2.3.1
      // http://promises-aplus.github.io/promises-spec/#point-48
      newValue = new TypeError('A promise may not resolve to itself');
      newState = PromiseState.REJECTED;
    }

    this.parent_ = null;
    this.state_ = PromiseState.BLOCKED;

    if (newState !== PromiseState.REJECTED) {
      if (Thenable.isImplementat ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.Resolver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Resolver ()](#apidoc.element.selenium-webdriver.promise.Resolver)
- description and source-code
```javascript
function Resolver() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.Scheduler"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Scheduler ()](#apidoc.element.selenium-webdriver.promise.Scheduler)
- description and source-code
```javascript
class Scheduler {
<span class="apidocCodeCommentSpan">  /**
   * Schedules a task for execution. If the task function is a generator, the
   * task will be executed using {@link ./promise.consume consume()}.
   *
   * @param {function(): (T|IThenable<T>)} fn The function to call to start the
   *     task.
   * @param {string=} opt_description A description of the task for debugging
   *     purposes.
   * @return {!Thenable<T>} A promise that will be resolved with the task
   *     result.
   * @template T
   */
</span>  execute(fn, opt_description) {}

  /**
   * Creates a new promise using the given resolver function.
   *
   * @param {function(
   *             function((T|IThenable<T>|Thenable|null)=),
   *             function(*=))} resolver
   * @return {!Thenable<T>}
   * @template T
   */
  promise(resolver) {}

  /**
   * Schedules a 'setTimeout' call.
   *
   * @param {number} ms The timeout delay, in milliseconds.
   * @param {string=} opt_description A description to accompany the timeout.
   * @return {!Thenable<void>} A promise that will be resolved when the timeout
   *     fires.
   */
  timeout(ms, opt_description) {}

  /**
   * Schedules a task to wait for a condition to hold.
   *
   * If the condition is defined as a function, it may return any value. Promise
   * will be resolved before testing if the condition holds (resolution time
   * counts towards the timeout). Once resolved, values are always evaluated as
   * booleans.
   *
   * If the condition function throws, or returns a rejected promise, the
   * wait task will fail.
   *
   * If the condition is defined as a promise, the scheduler will wait for it to
   * settle. If the timeout expires before the promise settles, the promise
   * returned by this function will be rejected.
   *
   * If this function is invoked with 'timeout === 0', or the timeout is
   * omitted, this scheduler will wait indefinitely for the condition to be
   * satisfied.
   *
   * @param {(!IThenable<T>|function())} condition The condition to poll,
   *     or a promise to wait on.
   * @param {number=} opt_timeout How long to wait, in milliseconds, for the
   *     condition to hold before timing out. If omitted, the flow will wait
   *     indefinitely.
   * @param {string=} opt_message An optional error message to include if the
   *     wait times out; defaults to the empty string.
   * @return {!Thenable<T>} A promise that will be fulfilled
   *     when the condition has been satisfied. The promise shall be rejected
   *     if the wait times out waiting for the condition.
   * @throws {TypeError} If condition is not a function or promise or if timeout
   *     is not a number >= 0.
   * @template T
   */
  wait(condition, opt_timeout, opt_message) {}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.Thenable"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>Thenable (new: Thenable, ...?)](#apidoc.element.selenium-webdriver.promise.Thenable)
- description and source-code
```javascript
class Thenable {
<span class="apidocCodeCommentSpan">  /**
   * Adds a property to a class prototype to allow runtime checks of whether
   * instances of that class implement the Thenable interface.
   * @param {function(new: Thenable, ...?)} ctor The
   *     constructor whose prototype to modify.
   */
</span>  static addImplementation(ctor) {
    addMarkerSymbol(ctor, IMPLEMENTED_BY_SYMBOL);
  }

  /**
   * Checks if an object has been tagged for implementing the Thenable
   * interface as defined by {@link Thenable.addImplementation}.
   * @param {*} object The object to test.
   * @return {boolean} Whether the object is an implementation of the Thenable
   *     interface.
   */
  static isImplementation(object) {
    return hasMarkerSymbol(object, IMPLEMENTED_BY_SYMBOL);
  }

  /**
   * Registers listeners for when this instance is resolved.
   *
   * @param {?(function(T): (R|IThenable<R>))=} opt_callback The
   *     function to call if this promise is successfully resolved. The function
   *     should expect a single argument: the promise's resolved value.
   * @param {?(function(*): (R|IThenable<R>))=} opt_errback
   *     The function to call if this promise is rejected. The function should
   *     expect a single argument: the rejection reason.
   * @return {!Thenable<R>} A new promise which will be resolved with the result
   *     of the invoked callback.
   * @template R
   */
  then(opt_callback, opt_errback) {}

  /**
   * Registers a listener for when this promise is rejected. This is synonymous
   * with the {@code catch} clause in a synchronous API:
   *
   *     // Synchronous API:
   *     try {
   *       doSynchronousWork();
   *     } catch (ex) {
   *       console.error(ex);
   *     }
   *
   *     // Asynchronous promise API:
   *     doAsynchronousWork().catch(function(ex) {
   *       console.error(ex);
   *     });
   *
   * @param {function(*): (R|IThenable<R>)} errback The
   *     function to call if this promise is rejected. The function should
   *     expect a single argument: the rejection reason.
   * @return {!Thenable<R>} A new promise which will be resolved with the result
   *     of the invoked callback.
   * @template R
   */
  catch(errback) {}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.all"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>all (arr)](#apidoc.element.selenium-webdriver.promise.all)
- description and source-code
```javascript
function all(arr) {
  return createPromise(function(fulfill, reject) {
    var n = arr.length;
    var values = [];

    if (!n) {
      fulfill(values);
      return;
    }

    var toFulfill = n;
    var onFulfilled = function(index, value) {
      values[index] = value;
      toFulfill--;
      if (toFulfill == 0) {
        fulfill(values);
      }
    };

    function processPromise(index) {
      asap(arr[index], function(value) {
        onFulfilled(index, value);
      }, reject);
    }

    for (var i = 0; i < n; ++i) {
      processPromise(i);
    }
  });
}
```
- example usage
```shell
...
  // executed.
  let actions = this.actions_.concat();
  let driver = this.driver_;
  return driver.controlFlow().execute(function() {
    let results = actions.map(action => {
      return driver.schedule(action.command, action.description);
    });
    return Promise.all(results);
  }, 'ActionSequence.perform');
}

/**
 * Moves the mouse. The location to move to may be specified in terms of the
 * mouse's current location, an offset relative to the top-left corner of an
 * element, or an element (in which case the middle of the element is used).
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.asap"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>asap (value, callback, opt_errback)](#apidoc.element.selenium-webdriver.promise.asap)
- description and source-code
```javascript
function asap(value, callback, opt_errback) {
  if (isPromise(value)) {
    value.then(callback, opt_errback);

  } else if (callback) {
    callback(value);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.captureStackTrace"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>captureStackTrace (name, msg, opt_topFn)](#apidoc.element.selenium-webdriver.promise.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace(name, msg, opt_topFn) {
  var e = Error(msg);
  e.name = name;
  if (Error.captureStackTrace) {
    Error.captureStackTrace(e, opt_topFn);
  } else {
    var stack = Error().stack;
    if (stack) {
      e.stack = e.toString();
      e.stack += '\n' + stack;
    }
  }
  return e;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.checkedNodeCall"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>checkedNodeCall (fn, var_args)](#apidoc.element.selenium-webdriver.promise.checkedNodeCall)
- description and source-code
```javascript
function checkedNodeCall(fn, var_args) {
  let args = Array.prototype.slice.call(arguments, 1);
  return createPromise(function(fulfill, reject) {
    try {
      args.push(function(error, value) {
        error ? reject(error) : fulfill(value);
      });
      fn.apply(undefined, args);
    } catch (ex) {
      reject(ex);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.consume"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>consume (generatorFn, opt_self, ...var_args)](#apidoc.element.selenium-webdriver.promise.consume)
- description and source-code
```javascript
function consume(generatorFn, opt_self, ...var_args) {
  if (!isGenerator(generatorFn)) {
    throw new TypeError('Input is not a GeneratorFunction: ' +
        generatorFn.constructor.name);
  }

  let ret;
  return ret = createPromise((resolve, reject) => {
    let generator = generatorFn.apply(opt_self, var_args);
    callNext();

<span class="apidocCodeCommentSpan">    /** @param {*=} opt_value . */
</span>    function callNext(opt_value) {
      pump(generator.next, opt_value);
    }

    /** @param {*=} opt_error . */
    function callThrow(opt_error) {
      pump(generator.throw, opt_error);
    }

    function pump(fn, opt_arg) {
      if (ret instanceof ManagedPromise && !isPending(ret)) {
        return;  // Deferred was cancelled; silently abort.
      }

      try {
        var result = fn.call(generator, opt_arg);
      } catch (ex) {
        reject(ex);
        return;
      }

      if (result.done) {
        resolve(result.value);
        return;
      }

      asap(result.value, callNext, callThrow);
    }
  });
}
```
- example usage
```shell
...
      'Wait condition must be a promise-like object, function, or a '
          + 'Condition object');
}

var driver = this;
var result = this.flow_.wait(function() {
  if (promise.isGenerator(fn)) {
    return promise.consume(fn, null, [driver]);
  }
  return fn(driver);
}, opt_timeout, message);

if (condition instanceof WebElementCondition) {
  result = new WebElementPromise(this, result.then(function(value) {
    if (!(value instanceof WebElement)) {
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.controlFlow"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>controlFlow ()](#apidoc.element.selenium-webdriver.promise.controlFlow)
- description and source-code
```javascript
function controlFlow() {
  if (!usePromiseManager()) {
    return SIMPLE_SCHEDULER;
  }

  if (activeFlows.length) {
    return activeFlows[activeFlows.length - 1];
  }

  if (!defaultFlow) {
    defaultFlow = new ControlFlow;
  }
  return defaultFlow;
}
```
- example usage
```shell
...
 */
perform() {
  // Make a protected copy of the scheduled actions. This will protect against
  // users defining additional commands before this sequence is actually
  // executed.
  let actions = this.actions_.concat();
  let driver = this.driver_;
  return driver.controlFlow().execute(function() {
    let results = actions.map(action => {
      return driver.schedule(action.command, action.description);
    });
    return Promise.all(results);
  }, 'ActionSequence.perform');
}
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.createFlow"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>createFlow (callback)](#apidoc.element.selenium-webdriver.promise.createFlow)
- description and source-code
```javascript
function createFlow(callback) {
  var flow = new ControlFlow;
  return flow.execute(function() {
    return callback(flow);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.createPromise"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>createPromise (resolver)](#apidoc.element.selenium-webdriver.promise.createPromise)
- description and source-code
```javascript
function createPromise(resolver) {
  let ctor = usePromiseManager() ? ManagedPromise : NativePromise;
  return new ctor(resolver);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.defer"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>defer ()](#apidoc.element.selenium-webdriver.promise.defer)
- description and source-code
```javascript
function defer() {
  if (usePromiseManager()) {
    return new Deferred();
  }
  let resolve, reject;
  let promise = new NativePromise((_resolve, _reject) => {
    resolve = _resolve;
    reject = _reject;
  });
  return {promise, resolve, reject};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.delayed"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>delayed (ms)](#apidoc.element.selenium-webdriver.promise.delayed)
- description and source-code
```javascript
function delayed(ms) {
  return createPromise(resolve => {
    setTimeout(() => resolve(), ms);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.filter"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>filter (arr, fn, opt_self)](#apidoc.element.selenium-webdriver.promise.filter)
- description and source-code
```javascript
function filter(arr, fn, opt_self) {
  return createPromise(resolve => resolve(arr)).then(v => {
    if (!Array.isArray(v)) {
      throw TypeError('not an array');
    }
    var arr = /** @type {!Array} */(v);
    return createPromise(function(fulfill, reject) {
      var n = arr.length;
      var values = [];
      var valuesLength = 0;
      (function processNext(i) {
        for (; i < n; i++) {
          if (i in arr) {
            break;
          }
        }
        if (i >= n) {
          fulfill(values);
          return;
        }
        try {
          var value = arr[i];
          var include = fn.call(opt_self, value, i, /** @type {!Array} */(arr));
          asap(include, function(include) {
            if (include) {
              values[valuesLength++] = value;
            }
            processNext(i + 1);
            }, reject);
        } catch (ex) {
          reject(ex);
        }
      })(0);
    });
  });
}
```
- example usage
```shell
...
 * @param {string} name The class name to search for.
 * @return {!By} The new locator.
 * @see http://www.w3.org/TR/2011/WD-html5-20110525/elements.html#classes
 * @see http://www.w3.org/TR/CSS2/selector.html#class-html
 */
static className(name) {
  let names = name.split(/\s+/g)
      .filter(s => s.length > 0)
      .map(s => escapeCss(s));
  return By.css('.' + names.join('.'));
}

/**
 * Locates elements using a CSS selector.
 *
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.finally"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>finally (promise, callback)](#apidoc.element.selenium-webdriver.promise.finally)
- description and source-code
```javascript
function thenFinally(promise, callback) {
  let error;
  let mustThrow = false;
  return promise.then(function() {
    return callback();
  }, function(err) {
    error = err;
    mustThrow = true;
    return callback();
  }).then(function() {
    if (mustThrow) {
      throw error;
    }
  });
}
```
- example usage
```shell
...
  /** @override */
  quit() {
    var result = this.schedule(
  new command.Command(command.Name.QUIT),
  'WebDriver.quit()');
    // Delete our session ID when the quit command finishes; this will allow us
    // to throw an error when attempting to use a driver post-quit.
    return /** @type {!promise.Thenable} */(promise.finally(result, () => {
this.session_ = this.flow_.promise((_, reject) => {
  reject(new error.NoSuchSessionError(
      'This driver instance does not have a valid session ID ' +
      '(did you call WebDriver.quit()?) and may no longer be used.'));
});

// Only want the session rejection to bubble if accessed.
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.fulfilled"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>fulfilled (opt_value)](#apidoc.element.selenium-webdriver.promise.fulfilled)
- description and source-code
```javascript
function fulfilled(opt_value) {
  let ctor = usePromiseManager() ? ManagedPromise : NativePromise;
  if (opt_value instanceof ctor) {
    return /** @type {!Thenable} */(opt_value);
  }

  if (usePromiseManager()) {
    // We can skip logging warnings about creating a managed promise because
    // this function will automatically switch to use a native promise when
    // the promise manager is disabled.
    return new ManagedPromise(
        resolve => resolve(opt_value), undefined, SKIP_LOG);
  }
  return NativePromise.resolve(opt_value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.fullyResolved"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>fullyResolved (value)](#apidoc.element.selenium-webdriver.promise.fullyResolved)
- description and source-code
```javascript
function fullyResolved(value) {
  if (isPromise(value)) {
    return fulfilled(value).then(fullyResolveValue);
  }
  return fullyResolveValue(value);
}
```
- example usage
```shell
...
      'WebDriver.executeScript()');
}

/** @override */
call(fn, opt_scope, var_args) {
  let args = Array.prototype.slice.call(arguments, 2);
  return this.flow_.execute(function() {
    return promise.fullyResolved(args).then(function(args) {
      if (promise.isGenerator(fn)) {
        args.unshift(fn, opt_scope);
        return promise.consume.apply(null, args);
      }
      return fn.apply(opt_scope, args);
    });
  }, 'WebDriver.call(' + (fn.name || 'function') + ')');
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.isGenerator"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>isGenerator (fn)](#apidoc.element.selenium-webdriver.promise.isGenerator)
- description and source-code
```javascript
function isGenerator(fn) {
  return fn.constructor.name === 'GeneratorFunction';
}
```
- example usage
```shell
...
}

/** @override */
call(fn, opt_scope, var_args) {
  let args = Array.prototype.slice.call(arguments, 2);
  return this.flow_.execute(function() {
    return promise.fullyResolved(args).then(function(args) {
      if (promise.isGenerator(fn)) {
        args.unshift(fn, opt_scope);
        return promise.consume.apply(null, args);
      }
      return fn.apply(opt_scope, args);
    });
  }, 'WebDriver.call(' + (fn.name || 'function') + ')');
}
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.isPromise"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>isPromise (value)](#apidoc.element.selenium-webdriver.promise.isPromise)
- description and source-code
```javascript
function isPromise(value) {
  try {
    // Use array notation so the Closure compiler does not obfuscate away our
    // contract.
    return value
        && (typeof value === 'object' || typeof value === 'function')
        && typeof value['then'] === 'function';
  } catch (ex) {
    return false;
  }
}
```
- example usage
```shell
...
 * Sends a request using the given executor.
 * @param {!Executor} executor
 * @param {!Request} request
 * @return {!Promise<Response>}
 */
function doSend(executor, request) {
const client = CLIENTS.get(executor);
if (promise.isPromise(client)) {
  return client.then(client => {
    CLIENTS.set(executor, client);
    return client.send(request);
  });
} else {
  return client.send(request);
}
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.map"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>map (arr, fn, opt_self)](#apidoc.element.selenium-webdriver.promise.map)
- description and source-code
```javascript
function map(arr, fn, opt_self) {
  return createPromise(resolve => resolve(arr)).then(v => {
    if (!Array.isArray(v)) {
      throw TypeError('not an array');
    }
    var arr = /** @type {!Array} */(v);
    return createPromise(function(fulfill, reject) {
      var n = arr.length;
      var values = new Array(n);
      (function processNext(i) {
        for (; i < n; i++) {
          if (i in arr) {
            break;
          }
        }
        if (i >= n) {
          fulfill(values);
          return;
        }
        try {
          asap(
              fn.call(opt_self, arr[i], i, /** @type {!Array} */(arr)),
              function(value) {
                values[i] = value;
                processNext(i + 1);
              },
              reject);
        } catch (ex) {
          reject(ex);
        }
      })(0);
    });
  });
}
```
- example usage
```shell
...
let json = {};
for (let key in this.options_) {
  if (this.options_[key] != null) {
    json[key] = this.options_[key];
  }
}
if (this.extensions_.length) {
  json.extensions = this.extensions_.map(function(extension) {
    if (Buffer.isBuffer(extension)) {
      return extension.toString('base64');
    }
    return io.read(/** @type {string} */(extension))
        .then(buffer => buffer.toString('base64'));
  });
}
...
```

#### <a name="apidoc.element.selenium-webdriver.promise.rejected"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>rejected (opt_reason)](#apidoc.element.selenium-webdriver.promise.rejected)
- description and source-code
```javascript
function rejected(opt_reason) {
  if (usePromiseManager()) {
    // We can skip logging warnings about creating a managed promise because
    // this function will automatically switch to use a native promise when
    // the promise manager is disabled.
    return new ManagedPromise(
        (_, reject) => reject(opt_reason), undefined, SKIP_LOG);
  }
  return NativePromise.reject(opt_reason);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.setDefaultFlow"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>setDefaultFlow (flow)](#apidoc.element.selenium-webdriver.promise.setDefaultFlow)
- description and source-code
```javascript
function setDefaultFlow(flow) {
  if (!usePromiseManager()) {
    throw Error(
        'You  may not change set the control flow when the promise'
            +' manager is disabled');
  }
  if (activeFlows.length) {
    throw Error('You may only change the default flow while it is active');
  }
  defaultFlow = flow;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.promise.when"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.promise.</span>when (value, opt_callback, opt_errback)](#apidoc.element.selenium-webdriver.promise.when)
- description and source-code
```javascript
function when(value, opt_callback, opt_errback) {
  return fulfilled(value).then(opt_callback, opt_errback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.proxy"></a>[module selenium-webdriver.proxy](#apidoc.module.selenium-webdriver.proxy)

#### <a name="apidoc.element.selenium-webdriver.proxy.direct"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>direct ()](#apidoc.element.selenium-webdriver.proxy.direct)
- description and source-code
```javascript
direct = function () {
  return {proxyType: 'direct'};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.proxy.manual"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>manual (options)](#apidoc.element.selenium-webdriver.proxy.manual)
- description and source-code
```javascript
manual = function (options) {
  // TODO(jleyba): Figure out why the Closure compiler does not think this is
  // a ProxyConfig record without the cast.
  return /** @type {!ProxyConfig} */({
    proxyType: 'manual',
    ftpProxy: options.ftp,
    httpProxy: options.http,
    sslProxy: options.https,
    noProxy: Array.isArray(options.bypass) ?
        options.bypass.join(',') : options.bypass
  });
}
```
- example usage
```shell
...

/**
 * @fileoverview Defines functions for configuring a webdriver proxy:
 *
 *     const Capabilities = require('./capabilities').Capabilities;
 *
 *     var capabilities = new Capabilities();
 *     capabilities.setProxy(proxy.manual({http: 'host:1234'});
 */

'use strict';

var ProxyConfig = require('./capabilities').ProxyConfig;
...
```

#### <a name="apidoc.element.selenium-webdriver.proxy.pac"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>pac (url)](#apidoc.element.selenium-webdriver.proxy.pac)
- description and source-code
```javascript
pac = function (url) {
  return {
    proxyType: 'pac',
    proxyAutoconfigUrl: url
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.proxy.socks"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>socks (host, username, password)](#apidoc.element.selenium-webdriver.proxy.socks)
- description and source-code
```javascript
socks = function (host, username, password) {
  return /** @type {!ProxyConfig} */({
    proxyType: 'manual',
    socksProxy: host,
    socksUsername: username,
    socksPassword: password
  });
}
```
- example usage
```shell
...
*
* __Example:__
*
*     const {Capabilities} = require('selenium-webdriver');
*     const proxy = require('selenium-webdriver/lib/proxy');
*
*     let capabilities = new Capabilities();
*     capabilities.setProxy(proxy.socks('localhost:1234', 'bob', 'password'));
*
*
* @param {string} host The proxy host, in the form 'hostname:port'.
* @param {string} username The user name to authenticate as.
* @param {string} password The password to authenticate with.
* @return {!ProxyConfig} A new proxy configuration object.
* @see https://en.wikipedia.org/wiki/SOCKS
...
```

#### <a name="apidoc.element.selenium-webdriver.proxy.system"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.proxy.</span>system ()](#apidoc.element.selenium-webdriver.proxy.system)
- description and source-code
```javascript
system = function () {
  return {proxyType: 'system'};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.safari"></a>[module selenium-webdriver.safari](#apidoc.module.selenium-webdriver.safari)

#### <a name="apidoc.element.selenium-webdriver.safari.Driver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.safari.</span>Driver (Options|Capabilities)](#apidoc.element.selenium-webdriver.safari.Driver)
- description and source-code
```javascript
class Driver extends webdriver.WebDriver {
<span class="apidocCodeCommentSpan">  /**
   * Creates a new Safari session.
   *
   * @param {(Options|Capabilities)=} opt_config The configuration
   *     options for the new session.
   * @param {promise.ControlFlow=} opt_flow The control flow to create
   *     the driver under.
   * @return {!Driver} A new driver instance.
   */
</span>  static createSession(opt_config, opt_flow) {
    let caps, exe;

    if (opt_config instanceof Options) {
      caps = opt_config.toCapabilities();
    } else {
      caps = opt_config || Capabilities.safari();
    }

    if (useTechnologyPreview(caps.get(OPTIONS_CAPABILITY_KEY))) {
      exe = SAFARIDRIVER_TECHNOLOGY_PREVIEW_EXE;
    }

    let service = new ServiceBuilder(exe).build();
    let executor = new http.Executor(
        service.start().then(url => new http.HttpClient(url)));

    return /** @type {!Driver} */(webdriver.WebDriver.createSession(
        executor, caps, opt_flow, this, () => service.kill()));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.safari.Options"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.safari.</span>Options ()](#apidoc.element.selenium-webdriver.safari.Options)
- description and source-code
```javascript
class Options {
  constructor() {
<span class="apidocCodeCommentSpan">    /** @private {Object<string, *>} */
</span>    this.options_ = null;

    /** @private {./lib/logging.Preferences} */
    this.logPrefs_ = null;

    /** @private {?./lib/capabilities.ProxyConfig} */
    this.proxy_ = null;
  }

  /**
   * Extracts the SafariDriver specific options from the given capabilities
   * object.
   * @param {!Capabilities} capabilities The capabilities object.
   * @return {!Options} The SafariDriver options.
   */
  static fromCapabilities(capabilities) {
    var options = new Options();
    var o = capabilities.get(OPTIONS_CAPABILITY_KEY);

    if (o instanceof Options) {
      options = o;
    } else if (o) {
      options.setCleanSession(o.cleanSession);
      options.setTechnologyPreview(o[TECHNOLOGY_PREVIEW_OPTIONS_KEY]);
    }

    if (capabilities.has(Capability.PROXY)) {
      options.setProxy(capabilities.get(Capability.PROXY));
    }

    if (capabilities.has(Capability.LOGGING_PREFS)) {
      options.setLoggingPrefs(capabilities.get(Capability.LOGGING_PREFS));
    }

    return options;
  }

  /**
   * Sets whether to force Safari to start with a clean session. Enabling this
   * option will cause all global browser data to be deleted.
   * @param {boolean} clean Whether to make sure the session has no cookies,
   *     cache entries, local storage, or databases.
   * @return {!Options} A self reference.
   */
  setCleanSession(clean) {
    if (!this.options_) {
      this.options_ = {};
    }
    this.options_['cleanSession'] = clean;
    return this;
  }

  /**
   * Sets the logging preferences for the new session.
   * @param {!./lib/logging.Preferences} prefs The logging preferences.
   * @return {!Options} A self reference.
   */
  setLoggingPrefs(prefs) {
    this.logPrefs_ = prefs;
    return this;
  }

  /**
   * Sets the proxy to use.
   *
   * @param {./lib/capabilities.ProxyConfig} proxy The proxy configuration to use.
   * @return {!Options} A self reference.
   */
  setProxy(proxy) {
    this.proxy_ = proxy;
    return this;
  }

  /**
   * Instruct the SafariDriver to use the Safari Technology Preview if true.
   * Otherwise, use the release version of Safari. Defaults to using the release version of Safari.
   *
   * @param {boolean} useTechnologyPreview
   * @return {!Options} A self reference.
   */
  setTechnologyPreview(useTechnologyPreview) {
    if (!this.options_) {
      this.options_ = {};
    }

    this.options_[TECHNOLOGY_PREVIEW_OPTIONS_KEY] = !!useTechnologyPreview;
    return this;
  }

  /**
   * Converts this options instance to a {@link Capabilities} object.
   * @param {Capabilities=} opt_capabilities The capabilities to
   *     merge these options into, if any.
   * @return {!Capabilities} The capabilities.
   */
  toCapabilities(opt_capabilities) {
    var caps = opt_capabilities || Capabilities.safari();
    if (this.logPrefs_) {
      caps.set(Capability.LOGGING_PREFS, this.logPrefs_);
    }
    if (this.proxy_) {
      caps.set(Capability.PROXY, this.proxy_);
    }
    if (this.options_) {
      caps.set(OPTIONS_CAPABILITY_KEY, this);
    }
    return caps;
  }

  /**
   * Converts this instance to its JSON wire protocol representation. Note this
   * function is an implementation detail not intended for general use.
   * @return {!Object<string, *>} The JSON wire protocol representation of this
   *     instance.
   */
  [Symbols.serialize]() {
    return this.options_ || {};
  }
}
```
- example usage
```shell
...
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
*     let driver = chrome.Driver.createSession(options, service);
*
* Users should only instantiate the {@link Driver} class directly when they
* need a custom driver service configuration (as shown above). For normal
* operation, users should start Chrome using the
...
```

#### <a name="apidoc.element.selenium-webdriver.safari.ServiceBuilder"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.safari.</span>ServiceBuilder (opt_exe)](#apidoc.element.selenium-webdriver.safari.ServiceBuilder)
- description and source-code
```javascript
class ServiceBuilder extends remote.DriverService.Builder {
<span class="apidocCodeCommentSpan">  /**
   * @param {string=} opt_exe Path to the server executable to use. If omitted,
   *     the builder will attempt to locate the safaridriver on the system PATH.
   */
</span>  constructor(opt_exe) {
    super(opt_exe || findSafariDriver());
    this.setLoopback(true);  // Required.
  }
}
```
- example usage
```shell
...
* with {@link #setDefaultService setDefaultService()}.
*
* You may also create a {@link Driver} with its own driver service. This is
* useful if you need to capture the server's log output for a specific session:
*
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
...
```



# <a name="apidoc.module.selenium-webdriver.session"></a>[module selenium-webdriver.session](#apidoc.module.selenium-webdriver.session)

#### <a name="apidoc.element.selenium-webdriver.session.Session"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.session.</span>Session (Object|Capabilities)](#apidoc.element.selenium-webdriver.session.Session)
- description and source-code
```javascript
class Session {

<span class="apidocCodeCommentSpan">  /**
   * @param {string} id The session ID.
   * @param {!(Object|Capabilities)} capabilities The session
   *     capabilities.
   */
</span>  constructor(id, capabilities) {
    /** @private {string} */
    this.id_ = id;

    /** @private {!Capabilities} */
    this.caps_ = capabilities instanceof Capabilities
        ? /** @type {!Capabilities} */(capabilities)
        : new Capabilities(capabilities);
  }

  /**
   * @return {string} This session's ID.
   */
  getId() {
    return this.id_;
  }

  /**
   * @return {!Capabilities} This session's capabilities.
   */
  getCapabilities() {
    return this.caps_;
  }

  /**
   * Retrieves the value of a specific capability.
   * @param {string} key The capability to retrieve.
   * @return {*} The capability value.
   */
  getCapability(key) {
    return this.caps_.get(key);
  }

  /**
   * Returns the JSON representation of this object, which is just the string
   * session ID.
   * @return {string} The JSON representation of this Session.
   */
  toJSON() {
    return this.getId();
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.until"></a>[module selenium-webdriver.until](#apidoc.module.selenium-webdriver.until)

#### <a name="apidoc.element.selenium-webdriver.until.ableToSwitchToFrame"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>ableToSwitchToFrame (frame)](#apidoc.element.selenium-webdriver.until.ableToSwitchToFrame)
- description and source-code
```javascript
function ableToSwitchToFrame(frame) {
  var condition;
  if (typeof frame === 'number' || frame instanceof webdriver.WebElement) {
    condition = driver => attemptToSwitchFrames(driver, frame);
  } else {
    condition = function(driver) {
      let locator = /** @type {!(By|Function)} */(frame);
      return driver.findElements(locator).then(function(els) {
        if (els.length) {
          return attemptToSwitchFrames(driver, els[0]);
        }
      });
    };
  }

  return new Condition('to be able to switch to frame', condition);

  function attemptToSwitchFrames(driver, frame) {
    return driver.switchTo().frame(frame).then(
        function() { return true; },
        function(e) {
          if (!(e instanceof error.NoSuchFrameError)) {
            throw e;
          }
        });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.alertIsPresent"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>alertIsPresent ()](#apidoc.element.selenium-webdriver.until.alertIsPresent)
- description and source-code
```javascript
function alertIsPresent() {
  return new Condition('for alert to be present', function(driver) {
    return driver.switchTo().alert().catch(function(e) {
      if (!(e instanceof error.NoSuchAlertError
        // XXX: Workaround for GeckoDriver error 'TypeError: can't convert null
        // to object'. For more details, see
        // https://github.com/SeleniumHQ/selenium/pull/2137
        || (e instanceof error.WebDriverError
          && e.message === 'can't convert null to object')
        )) {
        throw e;
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementIsDisabled"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsDisabled (element)](#apidoc.element.selenium-webdriver.until.elementIsDisabled)
- description and source-code
```javascript
function elementIsDisabled(element) {
  return new WebElementCondition('until element is disabled', function() {
    return element.isEnabled().then(v => v ? null : element);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementIsEnabled"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsEnabled (element)](#apidoc.element.selenium-webdriver.until.elementIsEnabled)
- description and source-code
```javascript
function elementIsEnabled(element) {
  return new WebElementCondition('until element is enabled', function() {
    return element.isEnabled().then(v => v ? element : null);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementIsNotSelected"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsNotSelected (element)](#apidoc.element.selenium-webdriver.until.elementIsNotSelected)
- description and source-code
```javascript
function elementIsNotSelected(element) {
  return new WebElementCondition('until element is not selected', function() {
    return element.isSelected().then(v => v ? null : element);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementIsNotVisible"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsNotVisible (element)](#apidoc.element.selenium-webdriver.until.elementIsNotVisible)
- description and source-code
```javascript
function elementIsNotVisible(element) {
  return new WebElementCondition('until element is not visible', function() {
    return element.isDisplayed().then(v => v ? null : element);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementIsSelected"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsSelected (element)](#apidoc.element.selenium-webdriver.until.elementIsSelected)
- description and source-code
```javascript
function elementIsSelected(element) {
  return new WebElementCondition('until element is selected', function() {
    return element.isSelected().then(v => v ? element : null);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementIsVisible"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementIsVisible (element)](#apidoc.element.selenium-webdriver.until.elementIsVisible)
- description and source-code
```javascript
function elementIsVisible(element) {
  return new WebElementCondition('until element is visible', function() {
    return element.isDisplayed().then(v => v ? element : null);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementLocated"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementLocated (locator)](#apidoc.element.selenium-webdriver.until.elementLocated)
- description and source-code
```javascript
function elementLocated(locator) {
  locator = by.checkedLocator(locator);
  let locatorStr =
      typeof locator === 'function' ? 'by function()' : locator + '';
  return new WebElementCondition('for element to be located ' + locatorStr,
      function(driver) {
        return driver.findElements(locator).then(function(elements) {
          return elements[0];
        });
      });
}
```
- example usage
```shell
...
* Note, if the provided condition is a {@link WebElementCondition}, then
* the wait will return a {@link WebElementPromise} that will resolve to the
* element that satisfied the condition.
*
* _Example:_ waiting up to 10 seconds for an element to be present on the
* page.
*
*     var button = driver.wait(until.elementLocated(By.id('foo')), 10000);
*     button.click();
*
* This function may also be used to block the command flow on the resolution
* of any thenable promise object. When given a promise, the command will
* simply wait for its resolution before completing. A timeout may be provided
* to fail the command if the promise does not resolve before the timeout
* expires.
...
```

#### <a name="apidoc.element.selenium-webdriver.until.elementTextContains"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementTextContains (element, substr)](#apidoc.element.selenium-webdriver.until.elementTextContains)
- description and source-code
```javascript
function elementTextContains(element, substr) {
  return new WebElementCondition('until element text contains', function() {
    return element.getText()
        .then(t => t.indexOf(substr) != -1 ? element : null);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementTextIs"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementTextIs (element, text)](#apidoc.element.selenium-webdriver.until.elementTextIs)
- description and source-code
```javascript
function elementTextIs(element, text) {
  return new WebElementCondition('until element text is', function() {
    return element.getText().then(t => t === text ? element : null);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementTextMatches"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementTextMatches (element, regex)](#apidoc.element.selenium-webdriver.until.elementTextMatches)
- description and source-code
```javascript
function elementTextMatches(element, regex) {
  return new WebElementCondition('until element text matches', function() {
    return element.getText().then(t => regex.test(t) ? element : null);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.elementsLocated"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>elementsLocated (locator)](#apidoc.element.selenium-webdriver.until.elementsLocated)
- description and source-code
```javascript
function elementsLocated(locator) {
  locator = by.checkedLocator(locator);
  let locatorStr =
      typeof locator === 'function' ? 'by function()' : locator + '';
  return new Condition(
      'for at least one element to be located ' + locatorStr,
      function(driver) {
        return driver.findElements(locator).then(function(elements) {
          return elements.length > 0 ? elements : null;
        });
      });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.stalenessOf"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>stalenessOf (element)](#apidoc.element.selenium-webdriver.until.stalenessOf)
- description and source-code
```javascript
function stalenessOf(element) {
  return new Condition('element to become stale', function() {
    return element.getTagName().then(
        function() { return false; },
        function(e) {
          if (e instanceof error.StaleElementReferenceError) {
            return true;
          }
          throw e;
        });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.titleContains"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>titleContains (substr)](#apidoc.element.selenium-webdriver.until.titleContains)
- description and source-code
```javascript
function titleContains(substr) {
  return new Condition(
      'for title to contain ' + JSON.stringify(substr),
      function(driver) {
        return driver.getTitle().then(function(title) {
          return title.indexOf(substr) !== -1;
        });
      });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.titleIs"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>titleIs (title)](#apidoc.element.selenium-webdriver.until.titleIs)
- description and source-code
```javascript
function titleIs(title) {
  return new Condition(
      'for title to be ' + JSON.stringify(title),
      function(driver) {
        return driver.getTitle().then(function(t) {
          return t === title;
        });
      });
}
```
- example usage
```shell
...
    var driver = new webdriver.Builder()
        .forBrowser('firefox')
        .build();

    driver.get('http://www.google.com/ncr');
    driver.findElement(By.name('q')).sendKeys('webdriver');
    driver.findElement(By.name('btnG')).click();
    driver.wait(until.titleIs('webdriver - Google Search'), 1000);
    driver.quit();

### Using the Builder API

The 'Builder' class is your one-stop shop for configuring new WebDriver
instances. Rather than clutter your code with branches for the various browsers,
the builder lets you set all options in one flow. When you call
...
```

#### <a name="apidoc.element.selenium-webdriver.until.titleMatches"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>titleMatches (regex)](#apidoc.element.selenium-webdriver.until.titleMatches)
- description and source-code
```javascript
function titleMatches(regex) {
  return new Condition('for title to match ' + regex, function(driver) {
    return driver.getTitle().then(function(title) {
      return regex.test(title);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.urlContains"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>urlContains (substrUrl)](#apidoc.element.selenium-webdriver.until.urlContains)
- description and source-code
```javascript
function urlContains(substrUrl) {
  return new Condition(
      'for URL to contain ' + JSON.stringify(substrUrl),
      function(driver) {
        return driver.getCurrentUrl().then(function(url) {
          return url.indexOf(substrUrl) !== -1;
        });
      });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.urlIs"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>urlIs (url)](#apidoc.element.selenium-webdriver.until.urlIs)
- description and source-code
```javascript
function urlIs(url) {
  return new Condition(
      'for URL to be ' + JSON.stringify(url),
      function(driver) {
        return driver.getCurrentUrl().then(function(u) {
          return u === url;
        });
      });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.until.urlMatches"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.until.</span>urlMatches (regex)](#apidoc.element.selenium-webdriver.until.urlMatches)
- description and source-code
```javascript
function urlMatches(regex) {
  return new Condition('for URL to match ' + regex, function(driver) {
    return driver.getCurrentUrl().then(function(url) {
      return regex.test(url);
    });
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.util"></a>[module selenium-webdriver.util](#apidoc.module.selenium-webdriver.util)

#### <a name="apidoc.element.selenium-webdriver.util.getStatus"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.util.</span>getStatus (url)](#apidoc.element.selenium-webdriver.util.getStatus)
- description and source-code
```javascript
function getStatus(url) {
  var client = new HttpClient(url);
  var executor = new Executor(client);
  var command = new Command(CommandName.GET_SERVER_STATUS);
  return executor.execute(command);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.util.waitForServer"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.util.</span>waitForServer (url, timeout, opt_cancelToken)](#apidoc.element.selenium-webdriver.util.waitForServer)
- description and source-code
```javascript
waitForServer = function (url, timeout, opt_cancelToken) {
  return new Promise((onResolve, onReject) => {
    let start = Date.now();

    let done = false;
    let resolve = (status) => {
      done = true;
      onResolve(status);
    };
    let reject = (err) => {
      done = true;
      onReject(err);
    };

    if (opt_cancelToken) {
      opt_cancelToken.then(_ => reject(new promise.CancellationError));
    }

    checkServerStatus();
    function checkServerStatus() {
      return getStatus(url).then(status => resolve(status), onError);
    }

    function onError(e) {
      // Some servers don't support the status command. If they are able to
      // response with an error, then can consider the server ready.
      if (e instanceof error.UnsupportedOperationError) {
        resolve({});
        return;
      }

      if (Date.now() - start > timeout) {
        reject(Error('Timed out waiting for the WebDriver server at ' + url));
      } else {
        setTimeout(function() {
          if (!done) {
            checkServerStatus();
          }
        }, 50);
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.util.waitForUrl"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.util.</span>waitForUrl (url, timeout, opt_cancelToken)](#apidoc.element.selenium-webdriver.util.waitForUrl)
- description and source-code
```javascript
waitForUrl = function (url, timeout, opt_cancelToken) {
  return new Promise((onResolve, onReject) => {
    let client = new HttpClient(url);
    let request = new HttpRequest('GET', '');
    let start = Date.now();

    let done = false;
    let resolve = () => {
      done = true;
      onResolve();
    };
    let reject = (err) => {
      done = true;
      onReject(err);
    };

    if (opt_cancelToken) {
      opt_cancelToken.then(_ => reject(new promise.CancellationError));
    }

    testUrl();

    function testUrl() {
      client.send(request).then(onResponse, onError);
    }

    function onError() {
      if (Date.now() - start > timeout) {
        reject(Error('Timed out waiting for the URL to return 2xx: ' + url));
      } else {
        setTimeout(function() {
          if (!done) {
            testUrl();
          }
        }, 50);
      }
    }

    function onResponse(response) {
      if (done) {
        return;
      }
      if (response.status > 199 && response.status < 300) {
        resolve();
        return;
      }
      onError();
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.selenium-webdriver.webdriver"></a>[module selenium-webdriver.webdriver](#apidoc.module.selenium-webdriver.webdriver)

#### <a name="apidoc.element.selenium-webdriver.webdriver.Alert"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Alert (driver, text)](#apidoc.element.selenium-webdriver.webdriver.Alert)
- description and source-code
```javascript
class Alert {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The driver controlling the browser this alert
   *     is attached to.
   * @param {string} text The message text displayed with this alert.
   */
</span>  constructor(driver, text) {
    /** @private {!WebDriver} */
    this.driver_ = driver;

    /** @private {!promise.Thenable<string>} */
    this.text_ = driver.controlFlow().promise(resolve => resolve(text));
  }

  /**
   * Retrieves the message text displayed with this alert. For instance, if the
   * alert were opened with alert("hello"), then this would return "hello".
   *
   * @return {!promise.Thenable<string>} A promise that will be
   *     resolved to the text displayed with this alert.
   */
  getText() {
    return this.text_;
  }

  /**
   * Sets the username and password in an alert prompting for credentials (such
   * as a Basic HTTP Auth prompt). This method will implicitly
   * {@linkplain #accept() submit} the dialog.
   *
   * @param {string} username The username to send.
   * @param {string} password The password to send.
   * @return {!promise.Thenable<void>} A promise that will be resolved when this
   *     command has completed.
   */
  authenticateAs(username, password) {
    return this.driver_.schedule(
        new command.Command(command.Name.SET_ALERT_CREDENTIALS),
        'WebDriver.switchTo().alert()'
            + '.authenticateAs("${username}", "${password}")');
  }

  /**
   * Accepts this alert.
   *
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when this command has completed.
   */
  accept() {
    return this.driver_.schedule(
        new command.Command(command.Name.ACCEPT_ALERT),
        'WebDriver.switchTo().alert().accept()');
  }

  /**
   * Dismisses this alert.
   *
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when this command has completed.
   */
  dismiss() {
    return this.driver_.schedule(
        new command.Command(command.Name.DISMISS_ALERT),
        'WebDriver.switchTo().alert().dismiss()');
  }

  /**
   * Sets the response text on this alert. This command will return an error if
   * the underlying alert does not support response text (e.g. window.alert and
   * window.confirm).
   *
   * @param {string} text The text to set.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when this command has completed.
   */
  sendKeys(text) {
    return this.driver_.schedule(
        new command.Command(command.Name.SET_ALERT_TEXT).
            setParameter('text', text),
        'WebDriver.switchTo().alert().sendKeys(' + text + ')');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.AlertPromise"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>AlertPromise (driver, alert)](#apidoc.element.selenium-webdriver.webdriver.AlertPromise)
- description and source-code
```javascript
class AlertPromise extends Alert {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The driver controlling the browser this
   *     alert is attached to.
   * @param {!promise.Thenable<!Alert>} alert A thenable
   *     that will be fulfilled with the promised alert.
   */
</span>  constructor(driver, alert) {
    super(driver, 'unused');

    /**
     * Cancel operation is only supported if the wrapped thenable is also
     * cancellable.
     * @param {(string|Error)=} opt_reason
     * @override
     */
    this.cancel = function(opt_reason) {
      if (promise.CancellableThenable.isImplementation(alert)) {
        /** @type {!promise.CancellableThenable} */(alert).cancel(opt_reason);
      }
    };

    /** @override */
    this.then = alert.then.bind(alert);

    /** @override */
    this.catch = alert.catch.bind(alert);

    /**
     * Defer returning text until the promised alert has been resolved.
     * @override
     */
    this.getText = function() {
      return alert.then(function(alert) {
        return alert.getText();
      });
    };

    /**
     * Defers action until the alert has been located.
     * @override
     */
    this.authenticateAs = function(username, password) {
      return alert.then(function(alert) {
        return alert.authenticateAs(username, password);
      });
    };

    /**
     * Defers action until the alert has been located.
     * @override
     */
    this.accept = function() {
      return alert.then(function(alert) {
        return alert.accept();
      });
    };

    /**
     * Defers action until the alert has been located.
     * @override
     */
    this.dismiss = function() {
      return alert.then(function(alert) {
        return alert.dismiss();
      });
    };

    /**
     * Defers action until the alert has been located.
     * @override
     */
    this.sendKeys = function(text) {
      return alert.then(function(alert) {
        return alert.sendKeys(text);
      });
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.Condition"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Condition (!WebDriver)](#apidoc.element.selenium-webdriver.webdriver.Condition)
- description and source-code
```javascript
class Condition {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} message A descriptive error message. Should complete the
   *     sentence "Waiting [...]"
   * @param {function(!WebDriver): OUT} fn The condition function to
   *     evaluate on each iteration of the wait loop.
   */
</span>  constructor(message, fn) {
    /** @private {string} */
    this.description_ = 'Waiting ' + message;

    /** @type {function(!WebDriver): OUT} */
    this.fn = fn;
  }

  /** @return {string} A description of this condition. */
  description() {
    return this.description_;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.IWebDriver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>IWebDriver ()](#apidoc.element.selenium-webdriver.webdriver.IWebDriver)
- description and source-code
```javascript
class IWebDriver {

<span class="apidocCodeCommentSpan">  /** @return {!promise.ControlFlow} The control flow used by this instance. */
</span>  controlFlow() {}

  /**
   * Schedules a {@link command.Command} to be executed by this driver's
   * {@link command.Executor}.
   *
   * @param {!command.Command} command The command to schedule.
   * @param {string} description A description of the command for debugging.
   * @return {!promise.Thenable<T>} A promise that will be resolved
   *     with the command result.
   * @template T
   */
  schedule(command, description) {}

  /**
   * Sets the {@linkplain input.FileDetector file detector} that should be
   * used with this instance.
   * @param {input.FileDetector} detector The detector to use or {@code null}.
   */
  setFileDetector(detector) {}

  /**
   * @return {!command.Executor} The command executor used by this instance.
   */
  getExecutor() {}

  /**
   * @return {!promise.Thenable<!Session>} A promise for this client's session.
   */
  getSession() {}

  /**
   * @return {!promise.Thenable<!Capabilities>} A promise that will resolve with
   *     the this instance's capabilities.
   */
  getCapabilities() {}

  /**
   * Terminates the browser session. After calling quit, this instance will be
   * invalidated and may no longer be used to issue commands against the
   * browser.
   *
   * @return {!promise.Thenable<void>} A promise that will be resolved when the
   *     command has completed.
   */
  quit() {}

  /**
   * Creates a new action sequence using this driver. The sequence will not be
   * scheduled for execution until {@link actions.ActionSequence#perform} is
   * called. Example:
   *
   *     driver.actions().
   *         mouseDown(element1).
   *         mouseMove(element2).
   *         mouseUp().
   *         perform();
   *
   * @return {!actions.ActionSequence} A new action sequence for this instance.
   */
  actions() {}

  /**
   * Creates a new touch sequence using this driver. The sequence will not be
   * scheduled for execution until {@link actions.TouchSequence#perform} is
   * called. Example:
   *
   *     driver.touchActions().
   *         tap(element1).
   *         doubleTap(element2).
   *         perform();
   *
   * @return {!actions.TouchSequence} A new touch sequence for this instance.
   */
  touchActions() {}

  /**
   * Schedules a command to execute JavaScript in the context of the currently
   * selected frame or window. The script fragment will be executed as the body
   * of an anonymous function. If the script is provided as a function object,
   * that function will be converted to a string for injection into the target
   * window.
   *
   * Any arguments provided in addition to the script will be included as script
   * arguments and may be referenced using the {@code arguments} object.
   * Arguments may be a boolean, number, string, or {@linkplain WebElement}.
   * Arrays and objects may also be used as script arguments as long as each item
   * adheres to the types previously mentioned.
   *
   * The script may refer to any variables accessible from the current window.
   * Furthermore, the script will execute in the window's context, thus
   * {@code document} may be used to refer to the current document. Any local
   * variables will not be available once the script has finished executing,
   * though global variables will persist.
   *
   * If the script has a return value (i.e. if the script contains a return
   * statement), then the following steps will be taken for resolving this
   * functions return value:
   *
   * - For a HTML element, the value will resolve to a {@linkplain WebElement}
   * - Null and undefined return values will resolve to null</li>
   * - Booleans, numbers, and strings will resolve as is</li>
   * - Functions will resolve to their string representation</li>
   * - For arrays and objects, each member item will be converted according to
   *     the rules above
   *
   * @param {!(string|Function)} script The script to execute.
   * @param {...*} var_args The arguments to pass to the script.
   * @return {!promise.Thenable< ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.Logs"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Logs (driver)](#apidoc.element.selenium-webdriver.webdriver.Logs)
- description and source-code
```javascript
class Logs {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The parent driver.
   * @private
   */
</span>  constructor(driver) {
    /** @private {!WebDriver} */
    this.driver_ = driver;
  }

  /**
   * Fetches available log entries for the given type.
   *
   * Note that log buffers are reset after each call, meaning that available
   * log entries correspond to those entries not yet returned for a given log
   * type. In practice, this means that this call will return the available log
   * entries since the last call, or from the start of the session.
   *
   * @param {!logging.Type} type The desired log type.
   * @return {!promise.Thenable<!Array.<!logging.Entry>>} A
   *   promise that will resolve to a list of log entries for the specified
   *   type.
   */
  get(type) {
    let cmd = new command.Command(command.Name.GET_LOG).
        setParameter('type', type);
    return this.driver_.schedule(
        cmd, 'WebDriver.manage().logs().get(' + type + ')').
        then(function(entries) {
          return entries.map(function(entry) {
            if (!(entry instanceof logging.Entry)) {
              return new logging.Entry(
                  entry['level'], entry['message'], entry['timestamp'],
                  entry['type']);
            }
            return entry;
          });
        });
  }

  /**
   * Retrieves the log types available to this driver.
   * @return {!promise.Thenable<!Array<!logging.Type>>} A
   *     promise that will resolve to a list of available log types.
   */
  getAvailableLogTypes() {
    return this.driver_.schedule(
        new command.Command(command.Name.GET_AVAILABLE_LOG_TYPES),
        'WebDriver.manage().logs().getAvailableLogTypes()');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.Navigation"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Navigation (driver)](#apidoc.element.selenium-webdriver.webdriver.Navigation)
- description and source-code
```javascript
class Navigation {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The parent driver.
   * @private
   */
</span>  constructor(driver) {
    /** @private {!WebDriver} */
    this.driver_ = driver;
  }

  /**
   * Schedules a command to navigate to a new URL.
   * @param {string} url The URL to navigate to.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the URL has been loaded.
   */
  to(url) {
    return this.driver_.schedule(
        new command.Command(command.Name.GET).
            setParameter('url', url),
        'WebDriver.navigate().to(' + url + ')');
  }

  /**
   * Schedules a command to move backwards in the browser history.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the navigation event has completed.
   */
  back() {
    return this.driver_.schedule(
        new command.Command(command.Name.GO_BACK),
        'WebDriver.navigate().back()');
  }

  /**
   * Schedules a command to move forwards in the browser history.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the navigation event has completed.
   */
  forward() {
    return this.driver_.schedule(
        new command.Command(command.Name.GO_FORWARD),
        'WebDriver.navigate().forward()');
  }

  /**
   * Schedules a command to refresh the current page.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the navigation event has completed.
   */
  refresh() {
    return this.driver_.schedule(
        new command.Command(command.Name.REFRESH),
        'WebDriver.navigate().refresh()');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.Options"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Options (driver)](#apidoc.element.selenium-webdriver.webdriver.Options)
- description and source-code
```javascript
class Options {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The parent driver.
   * @private
   */
</span>  constructor(driver) {
    /** @private {!WebDriver} */
    this.driver_ = driver;
  }

  /**
   * Schedules a command to add a cookie.
   *
   * __Sample Usage:__
   *
   *     // Set a basic cookie.
   *     driver.options().addCookie({name: 'foo', value: 'bar'});
   *
   *     // Set a cookie that expires in 10 minutes.
   *     let expiry = new Date(Date.now() + (10 * 60 * 1000));
   *     driver.options().addCookie({name: 'foo', value: 'bar', expiry});
   *
   *     // The cookie expiration may also be specified in seconds since epoch.
   *     driver.options().addCookie({
   *       name: 'foo',
   *       value: 'bar',
   *       expiry: Math.floor(Date.now() / 1000)
   *     });
   *
   * @param {!Options.Cookie} spec Defines the cookie to add.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the cookie has been added to the page.
   * @throws {error.InvalidArgumentError} if any of the cookie parameters are
   *     invalid.
   * @throws {TypeError} if 'spec' is not a cookie object.
   */
  addCookie(spec) {
    if (!spec || typeof spec !== 'object') {
      throw TypeError('addCookie called with non-cookie parameter');
    }

    // We do not allow '=' or ';' in the name.
    let name = spec.name;
    if (/[;=]/.test(name)) {
      throw new error.InvalidArgumentError(
          'Invalid cookie name "' + name + '"');
    }

    // We do not allow ';' in value.
    let value = spec.value;
    if (/;/.test(value)) {
      throw new error.InvalidArgumentError(
          'Invalid cookie value "' + value + '"');
    }

    let cookieString = name + '=' + value +
        (spec.domain ? ';domain=' + spec.domain : '') +
        (spec.path ? ';path=' + spec.path : '') +
        (spec.secure ? ';secure' : '');

    let expiry;
    if (typeof spec.expiry === 'number') {
      expiry = Math.floor(spec.expiry);
      cookieString += ';expires=' + new Date(spec.expiry * 1000).toUTCString();
    } else if (spec.expiry instanceof Date) {
      let date = /** @type {!Date} */(spec.expiry);
      expiry = Math.floor(date.getTime() / 1000);
      cookieString += ';expires=' + date.toUTCString();
    }

    return this.driver_.schedule(
        new command.Command(command.Name.ADD_COOKIE).
            setParameter('cookie', {
              'name': name,
              'value': value,
              'path': spec.path,
              'domain': spec.domain,
              'secure': !!spec.secure,
              'expiry': expiry
            }),
        'WebDriver.manage().addCookie(' + cookieString + ')');
  }

  /**
   * Schedules a command to delete all cookies visible to the current page.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when all cookies have been deleted.
   */
  deleteAllCookies() {
    return this.driver_.schedule(
        new command.Command(command.Name.DELETE_ALL_COOKIES),
        'WebDriver.manage().deleteAllCookies()');
  }

  /**
   * Schedules a command to delete the cookie with the given name. This command
   * is a no-op if there is no cookie with the given name visible to the current
   * page.
   * @param {string} name The name of the cookie to delete.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the cookie has been deleted.
   */
  deleteCookie(name) {
    return this.driver_.schedule(
        new command.Command(command.Name.DELETE_COOKIE).
            setParameter('name', name),
        'WebDriver.manage().deleteCookie(' + name + ')');
  }

  /**
   * Schedules a command to retrieve all cookies visible to the current page.
   * Each cookie will be returned as a JSON object as described by the WebDriver
   * wire protocol.
   * @return {!promise.Thenable<!Array<!Options.Cookie>>} A promise that will be
   *     resolved with the cookies visible to the current browsing context.
   */
  getCookies() {
    return this.driver_.schedule(
        new command.Command(command.Name.GET_ALL_COOKIES),
        'WebDriver ...
```
- example usage
```shell
...
*     let chrome = require('selenium-webdriver/chrome');
*
*     let service = new chrome.ServiceBuilder()
*         .loggingTo('/my/log/file.txt')
*         .enableVerboseLogging()
*         .build();
*
*     let options = new chrome.Options();
*     // configure browser options ...
*
*     let driver = chrome.Driver.createSession(options, service);
*
* Users should only instantiate the {@link Driver} class directly when they
* need a custom driver service configuration (as shown above). For normal
* operation, users should start Chrome using the
...
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.TargetLocator"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>TargetLocator (driver)](#apidoc.element.selenium-webdriver.webdriver.TargetLocator)
- description and source-code
```javascript
class TargetLocator {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The parent driver.
   * @private
   */
</span>  constructor(driver) {
    /** @private {!WebDriver} */
    this.driver_ = driver;
  }

  /**
   * Schedules a command retrieve the {@code document.activeElement} element on
   * the current document, or {@code document.body} if activeElement is not
   * available.
   * @return {!WebElementPromise} The active element.
   */
  activeElement() {
    var id = this.driver_.schedule(
        new command.Command(command.Name.GET_ACTIVE_ELEMENT),
        'WebDriver.switchTo().activeElement()');
    return new WebElementPromise(this.driver_, id);
  }

  /**
   * Schedules a command to switch focus of all future commands to the topmost
   * frame on the page.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the driver has changed focus to the default content.
   */
  defaultContent() {
    return this.driver_.schedule(
        new command.Command(command.Name.SWITCH_TO_FRAME).
            setParameter('id', null),
        'WebDriver.switchTo().defaultContent()');
  }

  /**
   * Schedules a command to switch the focus of all future commands to another
   * frame on the page. The target frame may be specified as one of the
   * following:
   *
   * - A number that specifies a (zero-based) index into [window.frames](
   *   https://developer.mozilla.org/en-US/docs/Web/API/Window.frames).
   * - A {@link WebElement} reference, which correspond to a 'frame' or 'iframe'
   *   DOM element.
   * - The 'null' value, to select the topmost frame on the page. Passing 'null'
   *   is the same as calling {@link #defaultContent defaultContent()}.
   *
   * If the specified frame can not be found, the returned promise will be
   * rejected with a {@linkplain error.NoSuchFrameError}.
   *
   * @param {(number|WebElement|null)} id The frame locator.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the driver has changed focus to the specified frame.
   */
  frame(id) {
    return this.driver_.schedule(
        new command.Command(command.Name.SWITCH_TO_FRAME).
            setParameter('id', id),
        'WebDriver.switchTo().frame(' + id + ')');
  }

  /**
   * Schedules a command to switch the focus of all future commands to another
   * window. Windows may be specified by their {@code window.name} attribute or
   * by its handle (as returned by {@link WebDriver#getWindowHandles}).
   *
   * If the specified window cannot be found, the returned promise will be
   * rejected with a {@linkplain error.NoSuchWindowError}.
   *
   * @param {string} nameOrHandle The name or window handle of the window to
   *     switch focus to.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the driver has changed focus to the specified window.
   */
  window(nameOrHandle) {
    return this.driver_.schedule(
        new command.Command(command.Name.SWITCH_TO_WINDOW).
            // "name" supports the legacy drivers. "handle" is the W3C
            // compliant parameter.
            setParameter('name', nameOrHandle).
            setParameter('handle', nameOrHandle),
        'WebDriver.switchTo().window(' + nameOrHandle + ')');
  }

  /**
   * Schedules a command to change focus to the active modal dialog, such as
   * those opened by 'window.alert()', 'window.confirm()', and
   * 'window.prompt()'. The returned promise will be rejected with a
   * {@linkplain error.NoSuchAlertError} if there are no open alerts.
   *
   * @return {!AlertPromise} The open alert.
   */
  alert() {
    var text = this.driver_.schedule(
        new command.Command(command.Name.GET_ALERT_TEXT),
        'WebDriver.switchTo().alert()');
    var driver = this.driver_;
    return new AlertPromise(driver, text.then(function(text) {
      return new Alert(driver, text);
    }));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.Timeouts"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Timeouts (driver)](#apidoc.element.selenium-webdriver.webdriver.Timeouts)
- description and source-code
```javascript
class Timeouts {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The parent driver.
   * @private
   */
</span>  constructor(driver) {
    /** @private {!WebDriver} */
    this.driver_ = driver;
  }

  /**
   * Specifies the amount of time the driver should wait when searching for an
   * element if it is not immediately present.
   *
   * When searching for a single element, the driver should poll the page
   * until the element has been found, or this timeout expires before failing
   * with a {@link bot.ErrorCode.NO_SUCH_ELEMENT} error. When searching
   * for multiple elements, the driver should poll the page until at least one
   * element has been found or this timeout has expired.
   *
   * Setting the wait timeout to 0 (its default value), disables implicit
   * waiting.
   *
   * Increasing the implicit wait timeout should be used judiciously as it
   * will have an adverse effect on test run time, especially when used with
   * slower location strategies like XPath.
   *
   * @param {number} ms The amount of time to wait, in milliseconds.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the implicit wait timeout has been set.
   */
  implicitlyWait(ms) {
    return this._scheduleCommand(ms, 'implicit', 'implicitlyWait');
  }

  /**
   * Sets the amount of time to wait, in milliseconds, for an asynchronous
   * script to finish execution before returning an error. If the timeout is
   * less than or equal to 0, the script will be allowed to run indefinitely.
   *
   * @param {number} ms The amount of time to wait, in milliseconds.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the script timeout has been set.
   */
  setScriptTimeout(ms) {
    return this._scheduleCommand(ms, 'script', 'setScriptTimeout');
  }

  /**
   * Sets the amount of time to wait for a page load to complete before
   * returning an error.  If the timeout is negative, page loads may be
   * indefinite.
   *
   * @param {number} ms The amount of time to wait, in milliseconds.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the timeout has been set.
   */
  pageLoadTimeout(ms) {
    return this._scheduleCommand(ms, 'page load', 'pageLoadTimeout');
  }

  _scheduleCommand(ms, timeoutIdentifier, timeoutName) {
    return this.driver_.schedule(
        new command.Command(command.Name.SET_TIMEOUT).
            setParameter('type', timeoutIdentifier).
            setParameter('ms', ms),
        'WebDriver.manage().timeouts().${timeoutName}(${ms})');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.WebDriver"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>WebDriver (Session|IThenable<!Session>)](#apidoc.element.selenium-webdriver.webdriver.WebDriver)
- description and source-code
```javascript
class WebDriver {
<span class="apidocCodeCommentSpan">  /**
   * @param {!(Session|IThenable<!Session>)} session Either a known session or a
   *     promise that will be resolved to a session.
   * @param {!command.Executor} executor The executor to use when sending
   *     commands to the browser.
   * @param {promise.ControlFlow=} opt_flow The flow to
   *     schedule commands through. Defaults to the active flow object.
   * @param {(function(this: void): ?)=} opt_onQuit A function to call, if any,
   *     when the session is terminated.
   */
</span>  constructor(session, executor, opt_flow, opt_onQuit) {
    /** @private {!promise.ControlFlow} */
    this.flow_ = opt_flow || promise.controlFlow();

    /** @private {!promise.Thenable<!Session>} */
    this.session_ = this.flow_.promise(resolve => resolve(session));

    /** @private {!command.Executor} */
    this.executor_ = executor;

    /** @private {input.FileDetector} */
    this.fileDetector_ = null;

    /** @private @const {(function(this: void): ?|undefined)} */
    this.onQuit_ = opt_onQuit;
  }

  /**
   * Creates a new WebDriver client for an existing session.
   * @param {!command.Executor} executor Command executor to use when querying
   *     for session details.
   * @param {string} sessionId ID of the session to attach to.
   * @param {promise.ControlFlow=} opt_flow The control flow all
   *     driver commands should execute under. Defaults to the
   *     {@link promise.controlFlow() currently active}  control flow.
   * @return {!WebDriver} A new client for the specified session.
   */
  static attachToSession(executor, sessionId, opt_flow) {
    let flow = opt_flow || promise.controlFlow();
    let cmd = new command.Command(command.Name.DESCRIBE_SESSION)
        .setParameter('sessionId', sessionId);
    let session = flow.execute(
        () => executeCommand(executor, cmd).catch(err => {
          // The DESCRIBE_SESSION command is not supported by the W3C spec, so
          // if we get back an unknown command, just return a session with
          // unknown capabilities.
          if (err instanceof error.UnknownCommandError) {
            return new Session(sessionId, new Capabilities);
          }
          throw err;
        }),
        'WebDriver.attachToSession()');
    return new WebDriver(session, executor, flow);
  }

  /**
   * Creates a new WebDriver session.
   *
   * By default, the requested session 'capabilities' are merely "desired" and
   * the remote end will still create a new session even if it cannot satisfy
   * all of the requested capabilities. You can query which capabilities a
   * session actually has using the
   * {@linkplain #getCapabilities() getCapabilities()} method on the returned
   * WebDriver instance.
   *
   * To define _required capabilities_, provide the 'capabilities' as an object
   * literal with 'required' and 'desired' keys. The 'desired' key may be
   * omitted if all capabilities are required, and vice versa. If the server
   * cannot create a session with all of the required capabilities, it will
   * return an {@linkplain error.SessionNotCreatedError}.
   *
   *     let required = new Capabilities().set('browserName', 'firefox');
   *     let desired = new Capabilities().set('version', '45');
   *     let driver = WebDriver.createSession(executor, {required, desired});
   *
   * This function will always return a WebDriver instance. If there is an error
   * creating the session, such as the aforementioned SessionNotCreatedError,
   * the driver will have a rejected {@linkplain #getSession session} promise.
   * It is recommended that this promise is left _unhandled_ so it will
   * propagate through the {@linkplain promise.ControlFlow control flow} and
   * cause subsequent commands to fail.
   *
   *     let required = Capabilities.firefox();
   *     let driver = WebDriver.createSession(executor, {required});
   *
   *     // If the createSession operation failed, then this command will also
   *     // also fail, propagating the creation failure.
   *     driver.get('http://www.google.com').catch(e => console.log(e));
   * ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.WebElement"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>WebElement (!IThenable<string>|string)](#apidoc.element.selenium-webdriver.webdriver.WebElement)
- description and source-code
```javascript
class WebElement {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver the parent WebDriver instance for this element.
   * @param {(!IThenable<string>|string)} id The server-assigned opaque ID for
   *     the underlying DOM element.
   */
</span>  constructor(driver, id) {
    /** @private {!WebDriver} */
    this.driver_ = driver;

    /** @private {!promise.Thenable<string>} */
    this.id_ = driver.controlFlow().promise(resolve => resolve(id));
  }

  /**
   * @param {string} id The raw ID.
   * @param {boolean=} opt_noLegacy Whether to exclude the legacy element key.
   * @return {!Object} The element ID for use with WebDriver's wire protocol.
   */
  static buildId(id, opt_noLegacy) {
    return opt_noLegacy
        ? {[ELEMENT_ID_KEY]: id}
        : {[ELEMENT_ID_KEY]: id, [LEGACY_ELEMENT_ID_KEY]: id};
  }

  /**
   * Extracts the encoded WebElement ID from the object.
   *
   * @param {?} obj The object to extract the ID from.
   * @return {string} the extracted ID.
   * @throws {TypeError} if the object is not a valid encoded ID.
   */
  static extractId(obj) {
    if (obj && typeof obj === 'object') {
      if (typeof obj[ELEMENT_ID_KEY] === 'string') {
        return obj[ELEMENT_ID_KEY];
      } else if (typeof obj[LEGACY_ELEMENT_ID_KEY] === 'string') {
        return obj[LEGACY_ELEMENT_ID_KEY];
      }
    }
    throw new TypeError('object is not a WebElement ID');
  }

  /**
   * @param {?} obj the object to test.
   * @return {boolean} whether the object is a valid encoded WebElement ID.
   */
  static isId(obj) {
    return obj && typeof obj === 'object'
        && (typeof obj[ELEMENT_ID_KEY] === 'string'
            || typeof obj[LEGACY_ELEMENT_ID_KEY] === 'string');
  }

  /**
   * Compares two WebElements for equality.
   *
   * @param {!WebElement} a A WebElement.
   * @param {!WebElement} b A WebElement.
   * @return {!promise.Thenable<boolean>} A promise that will be
   *     resolved to whether the two WebElements are equal.
   */
  static equals(a, b) {
    if (a === b) {
      return a.driver_.controlFlow().promise(resolve => resolve(true));
    }
    let ids = [a.getId(), b.getId()];
    return promise.all(ids).then(function(ids) {
      // If the two element's have the same ID, they should be considered
      // equal. Otherwise, they may still be equivalent, but we'll need to
      // ask the server to check for us.
      if (ids[0] === ids[1]) {
        return true;
      }

      let cmd = new command.Command(command.Name.ELEMENT_EQUALS);
      cmd.setParameter('id', ids[0]);
      cmd.setParameter('other', ids[1]);
      return a.driver_.schedule(cmd, 'WebElement.equals()');
    });
  }

  /** @return {!WebDriver} The parent driver for this instance. */
  getDriver() {
    return this.driver_;
  }

  /**
   * @return {!promise.Thenable<string>} A promise that resolves to
   *     the server-assigned opaque ID assigned to this element.
   */
  getId() {
    return this.id_;
  }

  /**
   * @return {!Object} Returns the serialized representation of this WebElement.
   */
  [Symbols.serialize]() {
    return this.getId().then(WebElement.buildId);
  }

  /**
   * Schedules a command that targets this element with the parent WebDriver
   * instance. Will ensure this element's ID is included in the command
   * parameters under the "id" key.
   *
   * @param {!command.Command} command The command to schedule.
   * @param {string} description A description of the command for debugging.
   * @return {!promise.Thenable<T>} A promise that will be resolved
   *     with the command result.
   * @template T
   * @see WebDriver#schedule
   * @private
   */
  schedule_(command, description) {
    command.setParameter('id', this);
    return this.driver_.schedule(command, description);
  }

  /**
   * Schedule a command to find a descendant of this element. If the element
   * cannot be found, the returned promise will be rejected with a
   * {@linkplain error.NoSuchElementError NoSuchElementError}.
   *
   * The search criteria for an element may be defined using one of the static
   * factories on the {@link by.By} class, or ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.WebElementCondition"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>WebElementCondition (!WebDriver)](#apidoc.element.selenium-webdriver.webdriver.WebElementCondition)
- description and source-code
```javascript
class WebElementCondition extends Condition {
<span class="apidocCodeCommentSpan">  /**
   * @param {string} message A descriptive error message. Should complete the
   *     sentence "Waiting [...]"
   * @param {function(!WebDriver): !(WebElement|IThenable<!WebElement>)}
   *     fn The condition function to evaluate on each iteration of the wait
   *     loop.
   */
</span>  constructor(message, fn) {
    super(message, fn);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.WebElementPromise"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>WebElementPromise (driver, el)](#apidoc.element.selenium-webdriver.webdriver.WebElementPromise)
- description and source-code
```javascript
class WebElementPromise extends WebElement {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The parent WebDriver instance for this
   *     element.
   * @param {!promise.Thenable<!WebElement>} el A promise
   *     that will resolve to the promised element.
   */
</span>  constructor(driver, el) {
    super(driver, 'unused');

    /**
     * Cancel operation is only supported if the wrapped thenable is also
     * cancellable.
     * @param {(string|Error)=} opt_reason
     * @override
     */
    this.cancel = function(opt_reason) {
      if (promise.CancellableThenable.isImplementation(el)) {
        /** @type {!promise.CancellableThenable} */(el).cancel(opt_reason);
      }
    };

    /** @override */
    this.then = el.then.bind(el);

    /** @override */
    this.catch = el.catch.bind(el);

    /**
     * Defers returning the element ID until the wrapped WebElement has been
     * resolved.
     * @override
     */
    this.getId = function() {
      return el.then(function(el) {
        return el.getId();
      });
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.selenium-webdriver.webdriver.Window"></a>[function <span class="apidocSignatureSpan">selenium-webdriver.webdriver.</span>Window (driver)](#apidoc.element.selenium-webdriver.webdriver.Window)
- description and source-code
```javascript
class Window {
<span class="apidocCodeCommentSpan">  /**
   * @param {!WebDriver} driver The parent driver.
   * @private
   */
</span>  constructor(driver) {
    /** @private {!WebDriver} */
    this.driver_ = driver;
  }

  /**
   * Retrieves the window's current position, relative to the top left corner of
   * the screen.
   * @return {!promise.Thenable<{x: number, y: number}>} A promise
   *     that will be resolved with the window's position in the form of a
   *     {x:number, y:number} object literal.
   */
  getPosition() {
    return this.driver_.schedule(
        new command.Command(command.Name.GET_WINDOW_POSITION).
            setParameter('windowHandle', 'current'),
        'WebDriver.manage().window().getPosition()');
  }

  /**
   * Repositions the current window.
   * @param {number} x The desired horizontal position, relative to the left
   *     side of the screen.
   * @param {number} y The desired vertical position, relative to the top of the
   *     of the screen.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the command has completed.
   */
  setPosition(x, y) {
    return this.driver_.schedule(
        new command.Command(command.Name.SET_WINDOW_POSITION).
            setParameter('windowHandle', 'current').
            setParameter('x', x).
            setParameter('y', y),
        'WebDriver.manage().window().setPosition(' + x + ', ' + y + ')');
  }

  /**
   * Retrieves the window's current size.
   * @return {!promise.Thenable<{width: number, height: number}>} A
   *     promise that will be resolved with the window's size in the form of a
   *     {width:number, height:number} object literal.
   */
  getSize() {
    return this.driver_.schedule(
        new command.Command(command.Name.GET_WINDOW_SIZE).
            setParameter('windowHandle', 'current'),
        'WebDriver.manage().window().getSize()');
  }

  /**
   * Resizes the current window.
   * @param {number} width The desired window width.
   * @param {number} height The desired window height.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the command has completed.
   */
  setSize(width, height) {
    return this.driver_.schedule(
        new command.Command(command.Name.SET_WINDOW_SIZE).
            setParameter('windowHandle', 'current').
            setParameter('width', width).
            setParameter('height', height),
        'WebDriver.manage().window().setSize(' + width + ', ' + height + ')');
  }

  /**
   * Maximizes the current window.
   * @return {!promise.Thenable<void>} A promise that will be resolved
   *     when the command has completed.
   */
  maximize() {
    return this.driver_.schedule(
        new command.Command(command.Name.MAXIMIZE_WINDOW).
            setParameter('windowHandle', 'current'),
        'WebDriver.manage().window().maximize()');
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
