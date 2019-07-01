# EconomicsBSTformatfiles
Useful BST format files for submission to economics journals

Most of these were created using the custom-bib package by Patrick Daly
Download and create your own here: https://ctan.org/tex-archive/biblio/bibtex/contrib/custom-bib?lang=en <br>
A useful overview of how to use this package is here: https://www.medicalnerds.com/latex-bibliography-management-and-styles/ <br>
Also see: https://www.andy-roberts.net/res/writing/latex/merlin.pdf

Since most economics journals use Author-year citation styles, they work best with natbib package, which you need to add to your preamble

```

\usepackage[authoryear]{natbib}
\bibliographystyle{JBEE_format}
```
...and later call...

```

\bibliography{***}  
```
... where *** is the name of your bib file.

Note also that you have to compile the Bibtex and then the full file (sometimes twice) to get everything to appear correctly.

