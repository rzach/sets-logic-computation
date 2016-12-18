# phil379
# Sets, Logic, Computation

Textbook for Calgary's Logic II course based on the Open Logic Project.

This repository/directory only contains the LaTeX files and
illustrations needed to typeset the textbook _Sets, Logic,
Computation_, which in turn requires the _[Open Logic
Text](http://github.com/OpenLogicProject/OpenLogic/)_.

You can download the PDF of the [screen version](http://people.ucalgary.ca/~rzach/static/open-logic/courses/phil379/phil379-screen.pdf) or the [print version](http://people.ucalgary.ca/~rzach/static/open-logic/courses/phil379/phil379-print.pdf).

To install and compile:

- Download/install the _Open Logic Text_
- Navigate to the subdirectory `courses/`
- Put the content of this repository into a subdirectory of it, say
  `courses/phil379`.

If you use `git`:

- `# git clone https://github.com/OpenLogicProject/OpenLogic.git`
- `# cd courses`
- `# git clone https://github.com/rzach/phil379.git`

Inside `courses/phil379`, you can now compile:

- `# cd phil379`
- `# pdflatex phil379-screen` or just `# make`

The file `phil379-screen.tex` produces a color version of the text
with smaller margins for screen reading. `phil379-print` produces a
black-and-white version designed for printing on Crown Quarto stock
(without cover). It can be used together with `cover-lulu-quarto.pdf`
on the print-on-demand website `lulu.com`. You can order a printed
copy [there](http://www.lulu.com/spotlight/openlogicproject).

Both versions load `phil379.tex`, which contains the actual
material. It in turn includes other files, most of them from the
`OpenLogic` repository. So you won't get a complete book unless you
download this into the right subdirectory of that and compile from
there.

[![Creative Commons License](http://mirrors.creativecommons.org/presskit/buttons/88x31/png/by.png)](http://creativecommons.org/licenses/by/4.0/) 

_[Sets, Logic, Computation](https://github.com/rzach/phil379/)_ by [Richard
Zach](http://richardzach.org/) is licensed under a [Creative
Commons Attribution 4.0 International
License](http://creativecommons.org/licenses/by/4.0/).
