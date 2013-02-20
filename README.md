GForth libraries documentation

This documentations are memo about standard libraries of gforth version 0.7.0 .

* author

ytnobody <ytnobody atmark gmail dot com>

* memo for general stuff

** library path

Basis library-path is following.

    $GFORTH_DIR/lib/gforth/site-forth
    $GFORTH_DIR/lib/gforth/$GFORTH_VERSION
    $GFORTH_DIR/share/gforth/site-forth
    $GFORTH_DIR/share/gforth/$GFORTH_VERSION

We can load library that is under these directories with "include" word into our program.

    \ loading string.fs library
    include string.fs

