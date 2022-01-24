# Business Card

## Prerequisites

- XeLaTeX
- [Font Awesome](https://github.com/xdanaux/fontawesome-latex)
- [Fira Sans Font](https://github.com/mozilla/Fira)

Heavily influenced by,
- 
- https://github.com/mikedecr/latex-business-card

## Preview

![Card Front](./images/card-front.png)

![Card Back](./images/card-back.png)

Preview generated via ImageMagick

```sh
magick convert -density 300 card-front.pdf -quality 90 -alpha remove images/card-front.png

magick convert -density 300 card-back.pdf -quality 90 -alpha remove images/card-back.png
```
