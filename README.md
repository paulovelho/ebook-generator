# Paulo Velho e-book generator

## Requirements
### write your book!
JUST FUCKING WRITE IT!
- create a prologue (optional)
- create a cover image (mandatory)
  - recommended size: `1563 x 2500 pixels`
  - recommended format: `jpeg` or `tiff`

### Kindlegen
download kindlegen:
[https://www.amazon.com/gp/feature.html?docId=1000765211](https://www.amazon.com/gp/feature.html?docId=1000765211)

### UUID Generator
To generate your UUID:
[https://www.uuidgenerator.net/](https://www.uuidgenerator.net/)

### mobi to epub
To convert your generated `.mobi` book to a `.epub` (better and more used format), you can:
#### do it online:
[http://www.zamzar.com/convert/mobi-to-epub/](http://www.zamzar.com/convert/mobi-to-epub/)
#### use **calibre**
[https://calibre-ebook.com/](https://calibre-ebook.com/)
_(I tottally recommend you to use **Calibre**...)_

---

## creating the book

- save HTML in `cap_.html`
  - one HTML per chapter
  - you can add as much chapters as you want - 1 per html... =)
  - images are added in `images` folder and referenced internally as `<img src="images/____.png"...` or whatever
- change book title in files: `content.opf`, `head.html`, `toc.html`, `toc.ncx` (toc.ncx in 2 places)
- create prologue (in `prologo.html`)
- add `agradecimentos.html`
- save cover image in root folder with name `cover.jpg`
- generate your UUID
  - change the UUID in `content.opf` and `toc.ncx`
- run the command line to build the book


### command line:
```
./kindlegen ebook/content.opf -verbose -o myEbook.mobi
```
`-o`: name of generated file
`-verbose`: print information
`-locale pt`: messages in portuguese, por favor

### generate epub
using Calibre, preferably


## to publish on Amazon:
[https://kdp.amazon.com/](https://kdp.amazon.com/)

---
## express your love <3

if you're creating a book or some other text following this tutorial, send me the epub/mobi!
I'm in favor of donate-ware format, where things are free but accepts donation.
I'll donate the value of your book directly to you! =)

[![Pay me a coffee](https://az743702.vo.msecnd.net/cdn/kofi2.png?v=0)](https://ko-fi.com/A4243CFI)

