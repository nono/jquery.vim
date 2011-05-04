Vim syntax for jQuery
=====================

It currently detects syntax and keywords for jQuery 1.6.

About
-----

jQuery is a fast and concise JavaScript Library that simplifies HTML document
traversing, event handling, animating, and Ajax interactions for rapid web
development. jQuery is designed to change the way that you write JavaScript.
See http://jquery.com/ for more details.

The syntax file for Vim add some colorations for jQuery keywords (empty clone
hasClass hide show animate ...) and for CSS selectors (:empty :hidden :selected
:first ...).


Install
-------

Copy the `syntax/jquery.vim` file to `$HOME/.vim/syntax/`
and add the following line to your vimrc:

    au BufRead,BufNewFile jquery.*.js set ft=javascript syntax=jquery


Credits
-------

Copyright (c) 2011 Bruno Michel <bmichel@menfin.info>, released under the MIT license
