# phantomjs-polyfill-every

Array.prototype.every polyfill for phantom.js based on https://github.com/ndelangen/phantomjs-polyfill

This is a polyfill for Array.prototype.every which is missing from PhantomJS.


## Installation

```
npm install --save-dev phantomjs-polyfill-every
```


## Usage

```
require('phantomjs-polyfill')
```


## Usage with Karma

Include the polyfill directly in the files list of your karma.conf

```
...
files: [
  './node_modules/phantomjs-polyfill-every/every-polyfill.js',
  ...
]
...
```
