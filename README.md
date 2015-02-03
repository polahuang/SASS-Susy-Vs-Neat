SASS Susy Vs. Bourbon.io Neat (compile time test)
=================================================

Since my last project with [Susy](http://susy.oddbird.net/) i think, my SASS files needs to much time to compile into CSS. Because before i switched to
Susy, i used the [Bourbon.io Neat](https://github.com/thoughtbot/neat) framework and never had this "long time to compile" feeling.

Test
----

Using the `@for $i from 1 through 50` loop in SASS to build CSS for each `<span>` tag in HTML.

Result
------

* Building with Susy: 13.08s
* Building with Neat:  1.61s 

Environment
-----------

Two simple and identic HTML files with 50 `<span>` elements. Each file includes the specific compiled CSS file.
One build with Susy and one with Neat.

Compiled with [CodeKit 2](https://incident57.com/codekit/) and

* SASS Version: 3.4.10
* Susy Version: 2.2.1
* Neat Version: 1.7.1

License
-------
The class is free and unencumbered public domain software. For more information, see [unlicense.org](http://unlicense.org).