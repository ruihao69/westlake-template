Westlake University Thesis/Report Template
===

A LaTeX thesis template based on the LaTeX Memoir class.

This thesis template is heavily derived from [`oxford-thesis-template`](https://github.com/ferdinandvanwyk/oxford-thesis-template.git), which is licensed under the GNU General Public License v3.0. 
The repository is also licensed under GNU General Public License v3.0.


Authors:
* [Rui-Hao Bi](https://github.com/ruihao69)

Original Authors:
* [Ferdinand van Wyk](https://github.com/ferdinandvanwyk)
* Ian Abel
* [Edmund Highcock](https://github.com/edmundhighcock)

Quick-start guide
-----------------

1. Install [LaTeX](https://www.latex-project.org/get/)

2. Build the `main.tex` file. Using the command line, you can do this via the
   `makefile`:

   ```bash
   $ cd /path/to/thesis
   $ make clean; make
   ```

Customization
-------------

1. Fill your personal information in `metadata.tex`
2. Package importing and related setting are in `main.tex`
3. Layout settings are in `westlakethesis.sty`
4. Change university logo in `westlakethesis.sty` (search for `graphics/oxlogo`)
5. Place useful macros in `macros.tex`


