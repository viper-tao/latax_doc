How to build pdf file
$cd {target directory}
$docker run --rm -v "${PWD}:/texsrc" -w /texsrc k1z3/texlive latexmk ******.tex
