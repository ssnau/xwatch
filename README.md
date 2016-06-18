xwatch
-----

a tiny watcher with no external dependencies.


install
-----

```
npm install xwatch
```


usage
-----

```
var xwatch = require('xwatch');

xwatch({
  path: 'dir-you-wanna-to-watch',
  pattern: RegExp | Function  // indicate file pattern to want to watch
  watcherName: 'name-of-the-watcher',
  callback: function (fileName) { ... }  // a callback with a single parameter
});
```

with `xwatch`, you wont know if a file is `renamed` or `added` or `removed`. Please do it by yourself.
