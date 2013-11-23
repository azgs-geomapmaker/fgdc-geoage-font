# fgdc-geoage-font

Web-ready representations of the [FGDC GeoAge font](http://ngmdb.usgs.gov/fgdc_gds/geolsymstd/fgdc-geolsym-sec32.pdf). This lets you use the font on the internet without having to worry about whether or not your end-users have the font installed on their computers.

Suggested Usage:

```css
@font-face{ 
    font-family: 'FGDCGeoAge';
    src: url('http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.eot');
    src: url('http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.eot?#iefix') format('embedded-opentype'),
         url('http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.woff') format('woff'),
         url('http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.ttf') format('truetype'),
         url('http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.svg#FGDCGeoAge') format('svg');
}
```

If you would like to download the font files themselves, They are available in the following formats:

- **Embedded OpenType**: [*download*](http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.eot) | [*description*](http://en.wikipedia.org/wiki/Embedded_OpenType)
- **Web Open Font Format**: [*download*](http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.woff) | [*description*](http://en.wikipedia.org/wiki/Woff)
- **TrueType Font**: [*download*](http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.ttf) | [*description*](http://en.wikipedia.org/wiki/TrueType)
- **Scalable Vector Graphics**: [*download*](http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.svg) | [*description*](http://en.wikipedia.org/wiki/Svg)

Thanks to Font Squirrel's [Webfont Generator](http://www.fontsquirrel.com/tools/webfont-generator) for doing all the lifting.