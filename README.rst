****************
Springer_csv2bib
****************

Python script to convert SpringerLink .csv to .bib 

SpringerLink doest not export .bib. Instead, it gives us .csv files, which are
kind of useless when writing with Latex.

Right now, this script considers everything '@articles' entries in .bib file.

Usage:
------

From your terminal, type::

    $ python3 springer_csv2bib <filepath.csv>

This will create (append) bib entries into a file named filepath.bib.
