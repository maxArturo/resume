This is my resume in LaTeX. While I originally found this resume
independently and maintained it, the templates come from Scott Clark.

I have also included Scott's (and the others) original templates.

Feel free to fork and edit.

In linux run

``` bash
$ pdflatex resumeName.tex
```

This should result in the creation of `resumeName.pdf`

Ubuntu requirements:

``` bash
$ sudo apt-get install texlive texlive-latex-extra
```

If you wish to use Docker for your latex needs instead, use in
conjunction with <https://github.com/blang/latex-docker>:

``` bash
$PATH_TO_LATEX_DOCKER_REPO/latexdockercmd.sh pdflatex dev_resume.tex

# or if you are using a custom typeface, use `xelatex`
$PATH_TO_LATEX_DOCKER_REPO/latexdockercmd.sh xelatex dev_resume.tex
```
