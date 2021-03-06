# TeX stuff

## LaTeX environment

[This VS Code package makes writing LaTex great.](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)


It provides: 

- Compilation on save.
- Good autocompletion.
- A command to clean build files.
- A PDF viewer in VS Code that updates on save.
- The ability to preview equations by hovering over them, before compilation.
![hover-example.jpg](hover-example.png)


[Install this code spell checker package](https://open-vsx.org/extension/streetsidesoftware/code-spell-checker)
to correct spelling mistakes within LaTeX documents.

To install LaTeX on an Arch based system run -

`sudo pacman -S texlive-most`

and that handles almost anything LaTeX related.

If you use an Arch based system and want to beautify LaTeX files, install `texlive-latexindent-meta` from the AUR.

`yay -S texlive-latexindent-meta`

Then add this alias. 

`alias texfix="latexindent -w $1 -s"`

$1 is the .tex file.

This automatically fixes formatting, so you don't go mad tabbing.

