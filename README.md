Productions made during my L3 internship at LISN (2023)
=======================================================

Because compiling large files on Overleaf is far from ergonomic, 
this repo provides the source codes of the report and the oral presentation 
(for validation of my course unit) of my L3 internship in LISN 
(january-july 2023). 
All used figures can be found in the **figs** sub-dirs.

Compilation
-----------

For the report, you must have _python-pygments_ installed. pdflatex must be executed with the 
`--shell-escape` option. No compilation file is shared in this repo. 
Output pdfs being especially huge, by default they are ignored by git.
In case of a modification of the .tex files, you shall `--force add`
a <ins>compressed</ins> pdf. The compression can be done using 
Ghostscript and the following command:

>  gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/printer -dNOPAUSE -dQUIET -dBATCH -sOutputFile=compressed.pdf original.pdf