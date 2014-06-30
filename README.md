# eshell-z.el

by [travisjeffery](http://twitter.com/travisjeffery)

A way to quickly jump between directories. This is an emacs lisp lib to use in emacs's eshell.

## Installing

``` elisp
(eval-after-load 'eshell
    '(require 'eshell-z nil t))
```

## Using

Instead of using `cd` in eshell, just use `z`.

## Jump by giving a whole directory path

`$ z ~/dev/timecop`

## Jump by giving a pattern

`$ z timecop`
