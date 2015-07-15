# hnsr-angular-ui-tree
Thin wrapper around angular-ui-tree so that it can be used with npm+browserify.

## Usage 

Using it is as simple as installing it with npm and `requiring()` it from your code:

```bash
$ npm install --save hnsr/hnsr-angular-ui-tree
```

Then from your code:

```javascript
  var angular = require('angular');
  angular.module('myApp', [  require('hnsr-angular-ui-tree') ]);
```

Browserify will then include angular-ui-tree in its bundle output. See http://blog.npmjs.org/post/114584444410/using-angulars-new-improved-browserify-support on how (and why) this works.

## Docs

For documentation on using angular-ui-tree itself, see https://github.com/angular-ui-tree/angular-ui-tree
