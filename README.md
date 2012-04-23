# Lo-Dash <sup>v0.1.0</sup>

A drop-in replacement for [Underscore.js](https://github.com/documentcloud/underscore/) that delivers **up to 8x performance improvements**, bug fixes, and additional features.

## BestieJS

Lo-Dash is part of the BestieJS *"Best in Class"* module collection. This means we promote solid browser/environment support, ES5 precedents, unit testing, and plenty of documentation.

## Documentation

The documentation for Lo-Dash can be viewed here: [/doc/README.md](https://github.com/bestiejs/lodash/blob/master/doc/README.md#readme)
Underscore's [documentation](http://documentcloud.github.com/underscore/) may also be used.

For a list of upcoming features, check out our [roadmap](https://github.com/bestiejs/lodash/wiki/Roadmap).

## Installation and usage

In a browser:

~~~ html
<script src="lodash.js"></script>
~~~

Via [npm](http://npmjs.org/):

~~~ bash
npm install lodash
~~~

In [Node.js](http://nodejs.org/) and [RingoJS v0.8.0+](http://ringojs.org/):

~~~ js
var _ = require('lodash');
~~~

In [Narwhal](http://narwhaljs.org/) and [RingoJS v0.7.0-](http://ringojs.org/):

~~~ js
var _ = require('lodash')._;
~~~

In [Rhino](http://www.mozilla.org/rhino/):

~~~ js
load('lodash.js');
~~~

In an AMD loader like [RequireJS](http://requirejs.org/):

~~~ js
// opt-in
define.amd.lodash = true;

require({
  'paths': {
    'lodash': 'path/to/lodash'
  }
},
['lodash'], function(_) {
  console.log(_.VERSION);
});
~~~

## Cloning this repo

To clone this repository including all submodules, using Git 1.6.5 or later:

~~~ bash
git clone --recursive https://github.com/bestiejs/lodash.git
cd lodash.js
~~~

For older Git versions, just use:

~~~ bash
git clone https://github.com/bestiejs/lodash.git
cd lodash
git submodule update --init
~~~

Feel free to fork and send pull requests if you see improvements!

## Author

* [John-David Dalton](http://allyoucanleet.com/)
  [![twitter/jdalton](http://gravatar.com/avatar/299a3d891ff1920b69c364d061007043?s=70)](https://twitter.com/jdalton "Follow @jdalton on Twitter")