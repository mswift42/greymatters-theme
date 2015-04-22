greymatters
===========

emacs 24 theme with a light background and warm colors.

Created with [Emacs Theme Creator](http://emacs-theme-creator.appspot.com).

Screenshots:
------------

Code samples of python and common lisp:

![Screenshot](https://github.com/mswift42/greymatters-theme/raw/master/greymattersclandpy.png)

Org-mode and JS sample:

![Screenshot](https://github.com/mswift42/greymatters-theme/raw/master/greymattersorgandjs.png)

Available on Melpa.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("melpa" . "http://melpa.milkbox.net/packages/")))
    (package-initialize)



This will add the gnu and melpa repos to your emacs setup.

To install the theme:

**M-x package-install** greymatters-theme


To use the greymatters theme when starting emacs, add this to your init.el:

    (load-theme 'greymatters)
