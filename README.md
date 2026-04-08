# assets
This repo contains miscellanous public assets for Athelas.
Contents:
- ``/logo``: Latex for generating the logo.

## png
To convert a pdf logo to png we can use [ImageMagic](https://github.com/ImageMagick/ImageMagick):

```sh
magick -density 600 logo.pdf logo.png 
```
