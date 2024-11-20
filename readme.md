# Readme
## Install
* Download LaTeX (9Gb size cca, full install recommended)  
https://www.tug.org/texlive/

## Learn
https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes

## Editor
### Visual Studio Code
Install plugin LaTeX Workshop by James Yu  
https://github.com/James-Yu/LaTeX-Workshop

## Commandline
Assumes installed TeXLive available on path.  
Input LaTeX file is sample.tex.  

To get help:
```
latex --help
```
Output PDF
```
pdflatex sample.tex
```
Output DVI:
```
latex sample.tex
```
Output image (when we have DVI):
```
dvipng sample.dvi
```
## Conversions
### LaTeX to DVI  
https://tex.stackexchange.com/questions/162964/how-can-i-get-the-dvi-file-from-latex-in-addition-to-or-instead-of-a-pdf  

### LaTeX to PNG 
Via DVI (both links)   
https://tex.stackexchange.com/questions/11866/compile-a-latex-document-into-a-png-image-thats-as-short-as-possible

https://tex.stackexchange.com/questions/48245/how-can-i-get-tex-file-compiled-into-image?noredirect=1&lq=1
