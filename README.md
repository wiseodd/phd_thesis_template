# Agustinus' PhD Thesis Template

**Disclaimer:** This template is based on the [mimosis](https://github.com/Pseudomanifold/latex-mimosis) theme. License: MIT.

## How-to

1. Write your chapter in `sources/`, e.g. `sources/01_intro.tex`.
2. Include it in `main.tex` by adding `\include{sources/01_intro}`
3. Don't forget to also add it into the `\includeonly` block at the very top of the `main.tex` file
4. To compile, simply run `make` in your terminal
5. If you have tikz figures:
    1. After running `make`, it will generate the `main.makefile` file
    2. Run `make -j 8 -f main.makefile` to generate compile the figures (in an externalized manner)
