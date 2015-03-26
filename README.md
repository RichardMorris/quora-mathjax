Quora with MathJax (Chrome extesion)
========================================

Extension replaces Quora bitmap equations with HTML-CSS ones by re-rendering them with the open source [MathJax](http://mathjax.org/) library. 

Forked from on [Wikipedia with MathJax](https://chrome.google.com/webstore/detail/wikipedia-with-mathjax/fhomhkjcommffnlajeemenejemmegcmi) [git-hub page](https://github.com/bgromov/wiki-mathjax) by Boris Gromov.

Very minor change to make it work with Quora and not wikipedia. 

Left-Click on equation to instantly zoom it to 200% (can be changed via MathJax menu).

Right-Click on equation to show MathJax's context menu with additional options, e.g. "Scale All Math..." to instantly scale all equations on a page, "TeX commands" to see the source TeX equation etc.

Extension is now published under [New BSD License](https://github.com/bgromov/wiki-mathjax/blob/master/LICENSE.md) with the source code available [here](https://github.com/bgromov/wiki-mathjax).

For bug reports and feature requests, please use [Issue tracker](https://github.com/bgromov/wiki-mathjax/issues).

### INSTALLATION:

Official release available at [Chrome Web Store](https://chrome.google.com/webstore/detail/wikipedia-with-mathjax/fhomhkjcommffnlajeemenejemmegcmi).


### KNOWN ISSUES:

 - Symbols which are not a part of display equation, i.e. not typed in between <math>...</math>, but right after it, will be displayed from the next line. This is along with LaTeX markup rules and won't be fixed.
 
