WhitestormJS + Physics (AmmoNext) Webpack4 Boilerplate
======================================================

> Webpack 4 Boilerplate with Babel, WhitestormJS and Physics module

## Setup
You'll need to install a few things before you have a working copy of the project.

### 1. Clone this repo:
Navigate into your workspace directory.

Run:
```sh
$ git clone https://github.com/Septaris/whitestorm-physics-app-boilerplate.git
```
### 2. Install node.js and [yarn](https://yarnpkg.com/):
https://nodejs.org/en/

### 3. Install dependencies:
Navigate to the cloned repo's directory.

Run:
```sh
$ yarn
```

## Development
Run the local webpack-dev-server with livereload and autocompile on [http://localhost:3000/](http://localhost:3000/)
```sh
$ yarn dev
```
## Deployment
Build the current application
```sh
$ yarn build
```

## [webpack](https://webpack.js.org/)
If you're not familiar with webpack, the [webpack-dev-server](https://webpack.js.org/configuration/dev-server/) will serve the static files in your build folder and watch your source files for changes.
When changes are made the bundle will be recompiled. This modified bundle is served from memory at the relative path specified in publicPath.

## Demo

https://septaris.github.io/whitestorm-physics-app-boilerplate/

## References and acknowledgments

- Inspired by https://github.com/rafaeldelboni/phaser3-es6-webpack4
- Deploying a subfolder to GitHub Pages: https://gist.github.com/cobyism/4730490
