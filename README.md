Title of the document
=====================

This file was last updated on DAY MONTH YEAR.

Downloading
-----------

This paper can be found at https://github.com/jfinkels/SHORTNAME.

To download the paper using [Git][1], run

    git clone git@github.com:jfinkels/SHORTNAME.git

A somewhat recent version of this work should be available at
https://cs-people.bu.edu/jeffreyf#SHORTNAME, but I can't guarantee that it will
always be up to date, since I compile and upload it manually.

[1]: http://git-scm.com

Compilation dependencies
------------------------

This document requires `pdflatex` to compile and `biber` for bibliography
management. The complete list of LaTeX packages required to compile this
document can be found at the head of the file `SHORTNAME.tex`.

To install the necessary packages on Ubuntu, run

    sudo apt-get install texlive-base texlive-latex-base texlive-latex-extra \
      texlive-science biber

Compiling
---------

To compile the document, run

    pdflatex SHORTNAME
    biber SHORTNAME
    pdflatex SHORTNAME

The output is `SHORTNAME.pdf`, and can be viewed with any PDF reader.

Copyright
---------

Copyright YEAR Jeffrey Finkelstein.

Both the LaTeX markup and the compiled document are made available under the
terms of the Creative Commons Attribution-ShareAlike 4.0 International License,
https://creativecommons.org/licenses/by-sa/4.0/.

Contact
-------

Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>
