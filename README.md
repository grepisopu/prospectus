Dissertation prospectus
=======================

This file was last updated on January 4, 2016.


Downloading
-----------

This document can be found at https://github.com/jfinkels/prospectus.

To download the source markup of the paper, run

    git clone git@github.com:jfinkels/prospectus.git

A somewhat recent version of this work should be available at
https://cs-people.bu.edu/jeffreyf#prospectus, but I can't guarantee that it
will always be up to date, since I compile and upload it manually.


Compilation dependencies
------------------------

This document requires `pdflatex` to compile and `biber` for bibliography
management. The complete list of LaTeX packages required to compile this
document can be found at the head of the file `prospectus.tex`.

To install the necessary packages on Ubuntu, run

    sudo apt-get install texlive-base texlive-latex-base texlive-latex-extra \
      texlive-science biber


Compiling
---------

To compile the document, run

    pdflatex prospectus
    biber prospectus
    pdflatex prospectus

The output is `prospectus.pdf`, and can be viewed with any PDF reader.


Copyright
---------

Copyright 2016 Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>.

Both the LaTeX markup and the compiled document are made available under the
terms of the Creative Commons Attribution-ShareAlike 4.0 International License,
https://creativecommons.org/licenses/by-sa/4.0/.


Contact
-------

Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>
