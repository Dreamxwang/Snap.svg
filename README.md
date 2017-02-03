[Snap.svg](http://snapsvg.io)
======

A JavaScript SVG library for the modern web. Learn more at [snapsvg.io](http://snapsvg.io).

[Follow us on Twitter.](https://twitter.com/snapsvg)

### Install
* [Bower](http://bower.io/) - `bower install snap.svg`
* Manual Minified - https://github.com/adobe-webplatform/Snap.svg/raw/master/dist/snap.svg-min.js
* Manual Unminified - https://raw.githubusercontent.com/adobe-webplatform/Snap.svg/master/dist/snap.svg.js


### Learn

* [About Snap.svg](http://snapsvg.io/about/)
* [Getting Started](http://snapsvg.io/start/)
* [API Reference](http://snapsvg.io/docs/)

### Use

In your HTML file, load simply by:
```html
<script src="snap.svg-min.js"></script>
```
No other scripts are needed. Both the minified and uncompressed (for development) versions are in the `/dist` folder.

To load with webpack use following command:
```js
const Snap = require(`imports-loader?this=>window,fix=>module.exports=0!snapsvg/dist/snap.svg.js`);
```

### Build
[![Build Status](https://travis-ci.org/adobe-webplatform/Snap.svg.svg?branch=dev)](https://travis-ci.org/adobe-webplatform/Snap.svg)

Snap.svg uses [Grunt](http://gruntjs.com/) to build.

* Open the terminal from the Snap.svg directory:
```sh
cd Snap.svg
```
* Install its command line interface (CLI) globally:
```sh
npm install -g grunt-cli
```
_*You might need to use `sudo npm`, depending on your configuration._

* Install dependencies with npm:
```sh
npm install
```
_*Snap.svg uses Grunt 0.4.0. You might want to [read](http://gruntjs.com/getting-started) more on their website if you haven’t upgraded since a lot has changed._

* Type `grunt` in the command line to build the files.
* The results will be built into the release folder.
* Alternatively type `grunt watch` to have the build run automatically when you make changes to source files.

### Contribute

* [Fill out the CLA](http://snapsvg.io/contributions/).
* [Fork](https://help.github.com/articles/fork-a-repo) the repo.
* Create a branch:
```sh
git checkout -b my_branch
```
* Add your changes.
* Commit your changes:
```sh
git commit -am "Added some awesome stuff"
```
* Push your branch:
```sh
git push origin my_branch
```
* Make a [pull request](https://help.github.com/articles/using-pull-requests) to `dev`(!) branch.

*Note:* Pull requests to other branches than `dev` or without filled CLA wouldn’t be accepted.
