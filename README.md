# Font Builder
The script tool for building files for [vazir-font](https://github.com/rastikerdar/vazir-font) and similar repositories.

## Requirements
- fontforge
- python3
- python3-fontforge
- ttfautohint
- sfnt2woff
- ttf2eot
- woff2_compress
- zip

## How it works
``` 
git clone https://github.com/rastikerdar/fontbuilder.git
chmod +x fontbuilder/makefont
git clone https://github.com/rastikerdar/shabnam-font.git
cd shabnam-font/
../fontbuilder/makefont
or 
bash ../fontbuilder/makefont
```

Thanks [github.com/alif-type/amiri](https://github.com/alif-type/amiri) for his great tools.

The common or standard way (Make file) is what you could see in [https://github.com/bateni/qalam-tarash](https://github.com/bateni/qalam-tarash). Maybe we should switch to that repo.

License: MIT
