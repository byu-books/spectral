Compile as:
`quarto render spectral.qmd`

`spectral.qmd` is the main file. It includes `fourier.qmd` and `cheby.qmd`. Each of these can be run on their own though: `quarto render fourier.qmd` or `quarto render cheby.qmd`. You can replace "render" with "preview" to both render and open the file. Note the table of contents has different (better) behavior with preview than render. Seems to be a bug in quarto.

