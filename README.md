# Logger
Package who exposes methods to log with some colors to play with semver. Require it, use it, color ur terminal.

```bash
npm i npmToying -S
```

```js
Logger = require('npmToying')
Logger.errMsg()
Logger.saySomething()
```

```js
/**
 * errMsg
 * Display a customisable error msg
 * @param {object} msg 
 * @returns 
 */
Logger.errMsg();
Logger.errMsg('OOPS SORRY BUDDY');

/**
 * saySomething
 * Say something to your user
 * @param {string} msg 
 * @returns 
 */
Logger.saySomething(msg);
```