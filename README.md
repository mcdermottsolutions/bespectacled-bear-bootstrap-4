## Bespectacled Bear Bootstrap 4

This is an empty Grunt starter project with Bootstrap 4 (in alpha), preloaded with goodies like Babel, Sass, etc.  If you already have Grunt, there's very little setup.  It's just an empty web project, ready to go.

![alt text](https://raw.githubusercontent.com/mcdermottsolutions/bespectacled-bear/master/dist/img/bespectacled-bear.png "Bespectacled Bear Logo")



## Motivation

Just looking to play with Bootstrap 4

## Installation

If you don't have have Node, NPM & Grunt installed, install those first.
See https://docs.npmjs.com/getting-started/installing-node & http://gruntjs.com/getting-started

---

Once you have Node, NPM & Grunt installed, do the following to install Bespectacled Bear:

```shell
git clone https://github.com/mcdermottsolutions/bespectacled-bear-bootstrap-4.git
cd bespectacled-bear
npm install
```
That last line there, npm install, just installs the required node modules specified in package.json.


The src folder is for working on the index.html.  For scss, work in the scss/_main.scss.

---

If you make any changes, you'll want to run
```shell
grunt
````
to recompile the sass, retranspile the js and copy everything from src to dev.

---

If you just want to watch for changes as you work, run
```shell
grunt server
````
and everytime you save, it will recompile the sass, retranspile the js, minimize the sass & js and copy everything from src to dev.

---

Todo:
- get livereload working
- include a local version of jquery for local offline work

---

Let me know if you have any questions or anything.
