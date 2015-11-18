First time compilation:

```
$ pdflatex template
$ biber template
$ pdflatex template
$ pdflatex template
```

Note: you must use `lualatex` instead of `pdflatex` if using `fontspec` package.

See sample book and sample handout for possible commands and environments
provided by the tufte-latex package. `tufte-handout-local` implements
modifications to comply with UCLIC requirements and configures APA referencing.
