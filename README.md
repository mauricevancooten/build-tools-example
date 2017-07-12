# Compiling Tools Example

Example of compile tools using NPM scripts.

## Dependencies

Node.js

## Instructions

### Install dependencies

run: `npm install`

### Run one of the following compile scripts.

* Compile CSS

run: `npm run compile:css`

Compile Sass to CSS and watches the 'src/sass' directory for changes.

* Lint and Browserify JavaScript

run: `npm run compile:js`

Lint and Browserify JavaScript and watch the 'src/js' directory for changes.

* Compile CSS, Lint and Browserify JavaScript

run: `npm run compile:watch`

Compile Sass to CSS, Lint and Browserify JavaScript and watch the 'src' directory for changes.

* Browser-sync

While watch tasks are running open a new Terminal window to run Browsersync.

run: `npm run browser-sync`

Sync browser when all HTML files and all files in the 'public' directory change.

* Compile CSS, Lint, Browserify JavaScript and Browser-sync

run: `npm run compile:sync`

Compile Sass to CSS, Lint and Browserify JavaScript, watch the 'src' directory for changes and sync browser.

## Licence

Licensed under the MIT Licence
