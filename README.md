Fragmention Drupal module
==================

The [Fragmention concept](http://indiewebcamp.com/fragmention) is a cross between URL "hash" fragment identifiers and in-browser full-text search, which was created by [Kevin Marks](http://kevinmarks.com) on the [Indie Web Camp](http://indiewebcamp.com/) discussion forum.

>Fragmentions find the first matching word or phrase in a document and focuses its closest surrounding element. The match is determined by the case-sensitive string following the ## double-hash. The closest surrounding element may be a span, paragraph, heading, button, input, or any other container.

The Fragmention module implements a JavaScript polyfill for the fragmention concept, which is loaded on every page. It is a simple implementation of [Jonathan Neal's](http://www.jonathantneal.com/) [Fragmentions JavaScript](https://github.com/chapmanu/fragmentions). The script is approximately 1200 bytes when minified, and approximately 500 bytes when minifed and gzipped.

Currently this is a Drupal sandbox module located at [https://drupal.org/sandbox/ocean/2247743](https://drupal.org/sandbox/ocean/2247743).

Installation
------------

1. Copy the fragmention directory to your sites/SITENAME/modules directory.

2. Enable the module at Administer >> Site building >> Modules.


Credits
-------
* [Kevin Marks](http://kevinmarks.com)
* [Jonathan Neal](http://www.jonathantneal.com)
