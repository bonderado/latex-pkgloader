latex-pkgloader
===============

LaTeX Package : latex-pkgloader 0.5.0

Last Modified : 2014-11-30

Author        : Michiel Helvensteijn  (www.mhelvens.net)

CTAN page     : https://www.ctan.org/pkg/pkgloader


Summary
-------

A LaTeX package for managing the options and loading order of other packages


Prerequisites
-------------

To use this package you need, apart from packages installed by default,
the following package:

*  `lt3graph`

To generate the documentation some additional packages are needed.


Installation
-------------

`pkgloader.sty` is provided directly in the package archive. Put
it in a place where your LaTeX distribution can find it.
(`pkgloader.sty` is not generated, but manually maintained; you
 may use docstrip to remove the documentation, but you don't
 have to; it will just work the way it is)


Documentation
-------------

`pkgloader.pdf` is provided directly in the package archive or [via CTAN](http://mirrors.ctan.org/macros/latex/contrib/pkgloader/pkgloader.pdf).
To generate the documentation yourself, run LaTeX on pkgloader.tex.
(`pkgloader.tex` does not contain the package code itself; it inputs
 `pkgloader.sty` directly to document the implementation)

License
-------

This material is subject to the LaTeX Project Public License. See
http://www.ctan.org/tex-archive/help/Catalogue/licenses.lppl.html 
for the details of that license.
