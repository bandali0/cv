# CV

The source code of my academic CV, based on Jason
Blevins's [CV template][template].

You'll need XeTeX since I'm using [fontspec][fontspec] for typesetting Matthew
Butterick's [Equity][equity] and [Triplicate][triplicate]. Note that these are
not free fonts. So if you don't have them or don't want to purchase them,
replace them with any font you like, such as [EB Garamond][ebgaramond]
and [Ubuntu Mono][ubuntumono].

Use `xelatex cv.tex` to generate the PDF. Or alternatively,
use `latexmk -pvc -xelatex cv.tex` to preview and automatically re-compile when
saving changes.

[template]: http://jblevins.org/projects/cv-template/
[fontspec]: https://www.ctan.org/pkg/fontspec?lang=en
[ebgaramond]: http://www.georgduffner.at/ebgaramond/
[ubuntumono]: http://font.ubuntu.com/
[equity]: http://practicaltypography.com/equity.html
[triplicate]: http://practicaltypography.com/triplicate.html

## License

The source code is licensed under the LaTeX Project Public License, either
version 1.3 of this license or (at your option) any later version.
See [LICENSE](LICENSE).
