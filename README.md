# LaTeX CV

This repository contains the LaTeX source code of (an outdated version of) my CV.
I'm open sourcing it for anyone interested in making a similar document.
[LaTeX](https://www.latex-project.org/) is a type-setting system that is used extensively in academia.
It takes time and effort to get to know LaTeX, but the quality of the documents you can create with it is amazing.

To generate a PDF from the `.tex` file, install LaTeX and execute `pdflatex cv-luc-engelen-2015.tex`.
The [end result](https://github.com/ljpengelen/latex-cv/blob/master/cv-luc-engelen-2015.pdf) looks like this:

![Front](https://github.com/ljpengelen/latex-cv/raw/master/cv-luc-engelen-2015-front.png)

![Back](https://github.com/ljpengelen/latex-cv/raw/master/cv-luc-engelen-2015-back.png)

I used to have a copy of my CV with my real e-mail address online.
To hide my e-mail adres from non-human readers of my CV, I've replaced the periods and at signs with small PDF images of these symbols.
That's what the `\hiddendot` and `\hiddenat` are for.
