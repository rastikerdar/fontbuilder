# Font Builder
The script tool for building files for [vazir-font](https://github.com/rastikerdar/vazir-font) and similar repositories.

## Requirements
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

License: MIT
