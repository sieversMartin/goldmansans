# goldmansans

## Support for Goldman Sans font for lualatex and xelatex

This LaTeX package set-ups the font `Goldman Sans` to use it with `lualatex` and `xelatex`.

It supports the following 11 font variants:
* Thin (Ultra Light)
* Light
* Regular 
* Regular Italic
* Medium (Semi Bold)
* Medium Italic
* Bold
* Bold Italic
* Black (Ultra Bold)
* Condensed
* Condensed Bold

There are options for switching between `bold` and `semibold` as well as between `proportional` and `tabular` figures. Moreover the package supports an easy access to the OpenType features `sups`/`subs` and `frac`.

## Installation

Until there is no CTAN release (or in case you want to use a development version), just copy `goldmansans.sty` to a place TeX can find it, e.g. one of your TEXMF trees or your working directory.

Please note, that the fonts themselfes are _not_ included. They have to be downloaded separatly from https://design.gs.com/d/design-system/foundation/typography/ and have to be installed either in one of your system's font directories or one of the TeX trees or in your working directory.

## Contributions

Feel free to raise an [GitHub issue](https://github.com/sieversMartin/goldmansans/issues). [Pull requests](https://github.com/sieversMartin/goldmansans/pulls) are also welcome.

## Licensing

This file is distributed under the terms of the LaTeX Project Public License from CTAN archives in directory macros/latex/base/lppl.txt. Either version 1.3 or, at your option, any later version.

See [LICENSE](LICENSE) for more details.

## Acknowledgements

Thanks to @hvoss49 for his `libertinus-otf` package, which inspired me.
