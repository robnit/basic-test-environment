# Simple ES6 test environment with functioning VSC breakpoints


Googling "vsc breakpoints es6 jest" will yield a wide variety of conflicting and outdated information. I am making this very simple example so that I will always have a basic test running environment when I need one. Hope it helps at least one other person.

### To use
Run `npm i` or `yarn`

In `package.json`, click `Debug` right above the `scripts` property. Select the only option. Now any future test runs will stop on breakpoints set in VSC!

If the `Debug` option is not showing, verify the following VSC setting exists `debug.javascript.codelens.npmScripts`

### Verified working on:
VSC Version: 1.62.3

Node.js: 14.16.0
