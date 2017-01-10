# Jekyll Simple Demo

Jekyll can be a simple solution for making static sites. This simplicity
can be lost when looking at kitchen sink demostrations. I put this
together as an example of an unitimidating Jekyll setup.

## Jekyll assumptions

* There must exist an index file at the root of the project. This can
  have either an html or md extension, but should probably have an html
  extension because of a limitation of the pagination gem
* The main CSS or Sass file needs to live in a css folder at the root of
  the project. This file needs frontmatter bars to trigger something in
  the jekyll build process. All other sass files do not need and should
  not have these bars. I've added configuration to the `_config.yml` file
  so partials can live in a sub directory of css instead of a root level
  `_sass` directory. The official documentation discusses creating a
  `_sass` directory, I do not care for this default as having css and
  `_sass` as siblings in the root seems messy and confusingto new
  developers to the project.
