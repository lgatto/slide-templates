# My slide template

## xaringan

This template uses Yihui Xie's `xaringan` package, that uses R
markdown and `remark.js` to generate fantastic presentations. My
template is available
[here](https://raw.githack.com/lgatto/slide-templates/master/my_template.html).


#### Cheat sheet

- The `xaringan` [wiki](https://github.com/yihui/xaringan/wiki)
- The `xaringan` [slides](https://slides.yihui.name/xaringan/)
- The `xaringan` [incremental slides](https://slides.yihui.name/xaringan/incremental.html)
- See also the default `xaringan` template (in RStudio: `File -> New
  File -> R Markdown -> From Template -> Ninja Presentation`)
- The `remark.js` [slides](https://remarkjs.com/)
- The `remark.js` [wiki](https://github.com/gnab/remark/wiki)

To use it, copy `my_template.Rmd`, `my.css` and the `img` directory.

To compile, run `Rscript -e "rmarkdown::render('my_template.Rmd')"`.

#### Issues

- Doesn't support [references](https://github.com/yihui/xaringan/issues/26)

## Beamer

See `LaTeX` directory, based on a template provided by SMCS.

TODO: include some macros from older slides ([examples](https://github.com/lgatto/2019_07_18_ISCB_KULeuven/blob/master/slides.tex)).
