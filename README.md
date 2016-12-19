# CV

The source code of my academic CV, based on Jason
Blevins's [CV template][template].

You'll need XeTeX since I'm using [fontspec][fontspec] for typesetting the
beautiful [EB Garamond][ebgaramond] font by Georg Duffner.

Use `xelatex cv.tex` to generate the PDF. Or alternatively,
use `latexmk -pvc -xelatex cv.tex` to preview and automatically re-compile when
saving changes.

[template]: http://jblevins.org/projects/cv-template/
[fontspec]: https://www.ctan.org/pkg/fontspec?lang=en
[ebgaramond]: http://www.georgduffner.at/ebgaramond/
