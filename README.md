# Maxiplot

Maxiplot er en LaTeX-pakke som giver mulighed for at benytte Maxima and Gnuplot i dine LaTeX-dokumenter.

Dette er en baseret på den original maxiplot-pakke.

## Installation og brug

- Installer [Maxima](https://maxima.sourceforge.io/download.html) og [Gnuplot](http://www.gnuplot.info/download.html)
- Tilføj deres mapper til %PATH miljøvariablen.

### Hvis du bruger TeXWorks
- Tilføj -enable-write18 til pdflatex parametererne i TexWorks preferences-menuen.
- Sæt eventuelt pdflatex som default typesætter i TeXworks hvis du benytter den editor

### Hvis du benytter latexmk
- Opret filen C:\latexmk\LatexMk (Eller $HOME/.latexmkrc på MacOS og *nix-platforme)
- indsæt linierne:
$latex = 'latex -interaction=nonstopmode -shell-escape';
$pdflatex = 'pdflatex -interaction=nonstopmode -shell-escape';

Kopiere filen maxiplot.sty til mappen hvor du skriver dit LaTeX-dokument og typeset dokumentet med pdflatex (to gange).

## Maxima dokumentation

Maxima linker til en stor mængde dokumentation på:
http://maxima.sourceforge.net/documentation.html

## Gnuplot dokumantation

Du kan finde Gnuplot dokumentationen på:
http://www.gnuplot.info/documentation.html

## Maxima LaTeX-output

Hvis du vil de det LaTeX-output som Maxima generere kan du kikke i den *.mxp fil som vil blive genereret i forbindelse med 
Typesetting-processen.
