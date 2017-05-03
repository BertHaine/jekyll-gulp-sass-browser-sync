Jekyll Boilerplate
=============================

A starter project including full setup for Jekyll, GulpJS, SASS, AutoPrefixer &amp; BrowserSync

#### Install Node.js
1.  Install [HomeBrew](http://brew.sh/)
1. `brew install nvm`
1. `nvm install v6.9.4`

#### Setting up the Project
1. Install Jekyll `$ gem install jekyll`
1. Install gulp: `$ npm install -g gulp`
1. Install dependencies: `$ npm install`
1. Build for prod: `$ gulp

## Deploy with Gulp

You can easily deploy your site build to a gh-pages branch. First, follow the instructions at [gulp-gh-pages](https://github.com/rowoot/gulp-gh-pages) to get your branch prepared for the deployment and to install the module. Then, in `gulpfile.js` you'll want to include something like the code below. `gulp.src()` needs to be the path to your final site folder, which by default will be `_site`. If you change the `destination` in your `_config.yml` file, be sure to reflect that in your gulpfile.



```javascript
var deploy = require("gulp-gh-pages");

gulp.task("deploy", ["jekyll-build"], function () {
    return gulp.src("./_site/**/*")
        .pipe(deploy());
});
```

## Acknowledgments

Hat tip to

* [Shane Osbourne](https://github.com/shakyShane) for his jekyll boilerplate I built off of for this template.
* [Urban Influence](http://urbaninfluence.com/2016/08/a-flexy-little-grid-system/) for their Flex Grid Mixin used here.