## startt
Simple wrapper around starting a process in new window for Node.js.

##### Install:

> `npm install startt`

##### Usage:

```js
'use strict';

const startt = require('startt');
startt('echo foo');
```

Uses `start %process%` command on win32 and `xterm -e %process%` on *nix.

Install xterm first if necessary. E.g. on Ubuntu:
 > `sudo apt-get install xterm`
