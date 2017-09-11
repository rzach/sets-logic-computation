# phil379
# Sets, Logic, Computation

![Book Cover](http://builds.openlogicproject.org/courses/phil379/phil379.png)\ 

Textbook for Calgary's Logic II course based on the Open Logic
Project.  Covers naive set theory, first-order logic, sequent calculus
and natural deduction, the completeness, compactness, and
Löwenheim-Skolem theorems, Turing machines, and the undecidability of
the halting problem and of first-order logic.

This repository/directory only contains the LaTeX files and
illustrations needed to typeset the textbook _Sets, Logic,
Computation_, which in turn requires the _[Open Logic
Text](http://github.com/OpenLogicProject/OpenLogic/)_.

You can [download the
PDF](http://builds.openlogicproject.org/courses/phil379/phil379-screen.pdf) of the most recent version
from the [Open Logic builds
site](http://builds.openlogicproject.org/), or order a hardcopy from [Amazon](https://www.amazon.com/dp/1975687132/) [[CA](https://www.amazon.ca/dp/1975687132/)] [[UK](https://www.amazon.co.uk/dp/1975687132/)] [[DE](https://www.amazon.de/dp/1975687132/)].

To install and compile:

- Download/install the _Open Logic Text_ from
  [GitHub](http://github.com/OpenLogicProject/OpenLogic/), including [photos](https://github.com/OpenLogicProject/photos) if you want those.
- Navigate to the subdirectory `courses/`
- Put the content of [this repository](https://github.com/rzach/phil379) into a subdirectory of it, say
  `courses/phil379`.

If you use `git`, this should do it:
```
# git clone https://github.com/OpenLogicProject/OpenLogic.git
# cd OpenLogic/courses
# git clone https://github.com/rzach/phil379.git
```
Inside `courses/phil379`, you can now compile:
```
# cd phil379
# pdflatex phil379-screen
```
or just `# make` if you have `latexmk` installed. (You'll also have to
do `makeglossaries phil379-screen` to get the glossary, and `bibtex
phil379-screen` for the bibliography.)

The file `phil379-screen.tex` produces a color version of the text
with smaller margins for screen reading. `phil379-print` produces a
black-and-white version designed for printing on Crown Quarto stock
(without cover).

Both versions load `phil379.tex`, which contains the actual
material. It in turn includes other files, most of them from the
`OpenLogic` repository. So you won't get a complete book unless you
download into the right subdirectory of and compile from there.

[![Creative Commons License](http://mirrors.creativecommons.org/presskit/buttons/88x31/png/by.png)](http://creativecommons.org/licenses/by/4.0/) 

_[Sets, Logic, Computation](https://github.com/rzach/phil379/)_ by [Richard
Zach](http://richardzach.org/) is licensed under a [Creative
Commons Attribution 4.0 International
License](http://creativecommons.org/licenses/by/4.0/).
