This repo includes files for producing an example LaTeX document. I designed it for use in my department, but others who want to learn the rudiments of LaTeX may find it useful.

The document works in two ways. The output, `LatexExample.pdf`, is a nicely formatted document that shows how LaTeX works through examples. The production file, however, is also heavily commented. These comments of course don't show up in the finished document, but they do add useful information about some of the quirks of LaTeX. Use both to get a better idea of how LaTeX works.

## Required files

To properly compile the following files need to be on your local machine in the same directory (folder):

* `LatexExample.tex`: the main document file
* `LatexExampleExternalTable.tex`: an external table file
* `LatexExample.bib`: a bibliography file
* `calvingetsit.jpg`: an image

The file `LatexExample.pdf` is an example of the document produced by compiling `LatexExample.tex`. If you don't want it to be overwritten as you attempt to compile the `.tex` file, move it to another location on your computer.

## Install TeX on your computer

If you haven't already, you'll need a TeX engine your computer in order to compile `.tex` files into `.pdf` documents. I recommend one of the prepackaged distributions.

##### Windows: [MikTeX](http://miktex.org/)  
##### Mac: [MacTex](http://www.tug.org/mactex/)  
##### Linux: [Tex Live](http://www.tug.org/texlive/)

## To run

1. Download all files in this repo to your local machine. Make sure they are in the same directory.
2. Open `LatexExample.tex` in a TeX editor such as TexWorks and compile the document. It should look like the included `LatexExample.pdf` document.

## Other resources

Have this one figured out? Want to know more? Here are some other (read: even better) resources:

[The Not So Short Introduction to LaTeX](http://tobi.oetiker.ch/lshort/lshort.pdf)  

[LaTeX wiki](http://en.wikibooks.org/wiki/LaTeX)  

[Don't know what the symbol you want is called, but you can draw it? Then draw it with  Detexify!](http://detexify.kirelabs.org/classify.html)

