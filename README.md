Seed project for Ruby-flavoured front-end packages.

Requires:
---------
* Ruby with [RubyGems](http://rubygems.org/pages/download) and [Bundler](http://bundler.io/);
* [Node](http://nodejs.org/) with [NPM](https://www.npmjs.org/);

Supports:
---------
* [CoffeeScript](http://coffeescript.org/) (as well as plain JavaScript)
* [Slim](http://slim-lang.com/) (as well as plain HTML)
* [Stylus](http://learnboost.github.io/stylus/) (as well as plain CSS)
* [Bower](http://bower.io/)
* [Browserify](http://browserify.org/)
* [Gulp](http://gulpjs.com/)

Usage:
------
1. Fork this project
2. Overwrite `package.json` with your package's name, version, description, dev dependencies, etc.;
3. Overwrite `bower.json` with your package's name, version, description, dependencies, etc.;
4. Overwrite this `README.md` with your package's notes;
5. Compose your own `sources\index.coffee` or `sources\index.js` for code (if any);
6. Compose your own `sources\index.styl` or `sources\index.css` for styles (if any);
7. Compose your own `sources\*.slim` or `sources\*.html` for templates (if any);
8. Compose your test cases or demo pages in `tests` (if any);
9. Append to `gulpfile.js` your own tasks (if any);
10. Build everything up, and start the dev server with live reload on [http://localhost:8082](http://localhost:8082):
    ```PowerShell
    # Ruby dependencies
    bundle install

    # JavaScript dev dependencies
    npm install

    # Build and run
    gulp
    ```




