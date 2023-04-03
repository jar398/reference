
To generate latex and then a PDF: visit the .org file in emacs and do 
^C ^E l p

To generate and immediately view a PDF: ^C ^E l o

TBD: I need to make a little script to tweak the LaTeX file to remove 
the ugly red boxes.  Need:

    \documentclass[hidelinks,12pt]{article}

or whatever.

https://emacs.stackexchange.com/questions/29640/how-do-i-get-rid-of-the-red-boxes-around-the-links-in-the-toc 
advises something like

    #+latex_header: \hypersetup{colorlinks=true,linkcolor=blue}
