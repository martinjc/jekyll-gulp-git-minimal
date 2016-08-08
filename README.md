# jekyll-gulp-git-minimal

A very basic Jekyll + Gulp + github setup.

Gulp tasks:

* Sass is compiled to CSS, auto-prefixed, cleaned and minimised
* JS is concatenated, uglified and minified
* Images are minified
* HTML is minified


## pushing built site to to gh-pages

`git subtree push --prefix _site origin gh-pages`
