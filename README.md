# Component Template

Quick and dirty starter template for building ES6 and Sass.

Build JavaScript (using Babel, Browserify) and Sass (using node-sass) for development or production.
Currently `envify`, `minifyify` and `babelify` are run during Browserify step. Sourcemaps are turned off.

1. `npm install`
1. `npm run dev` starts a watcher for JS/Sass
1. Edit files in `src/*`
1. `npm run dist` for "production" version

## TODO

1. Add autoprefixer to style building process.
