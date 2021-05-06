# react-pdf-in-react-native
@react-pdf/renderer doesn't work in react-native, as the following error occures:

```
Failed building JavaScript bundle.
Unable to resolve module stream from /Users/frederik/tmp/my-app/node_modules/blob-stream/index.js: stream could not be found within the project.

If you are sure the module exists, try these steps:
 1. Clear watchman watches: watchman watch-del-all
 2. Delete node_modules and run yarn install
 3. Reset Metro's cache: yarn start --reset-cache
 4. Remove the cache: rm -rf /tmp/metro-*
> 1 | var WritableStream = require('stream').Writable;
    |                               ^
  2 | var util = require('util');
  3 | var Blob = require('blob');
  4 | var URL = global.URL || global.webkitURL || global.mozURL;
```
