# bar-cursor

## Introduction

bar-cursor is an Emacs Lisp package that changes the Emacs cursor from a block into a bar. In overwrite-mode, the cursor will change into a block.

I forked bar-cursor from the file by Joseph L. Casadonte Jr. found on [his webpage](http://www.northbound-train.com/emacs.html#MyPackages).

## Installation

1. Place `bar-cursor.el` somewhere on your Emacs load path.
2. Add `(require 'bar-cursor)` to your .emacs
3. Add `(bar-cursor-mode 1)` to your .emacs

`bar-cursor.el` is also available in Melpa. See the [setup instructions](https://github.com/melpa/melpa#usage) for information on using Melpa. Then you can run `M-x package-install bar-cursor` to install it.
