# fgdc-geoage-font

Web-ready representations of the [FGDC GeoAge font](http://ngmdb.usgs.gov/fgdc_gds/geolsymstd/fgdc-geolsym-sec32.pdf). This lets you use the font on the internet without having to worry about whether or not your end-users have the font installed on their computers.

Suggested Usage:

```css
@font-face{ 
    font-family: 'FGDCGeoAge';
    src: url('//azgs-geomapmaker.github.io/fgdc-geoage-font/fgdcgeoage.eot');
    src: url('//azgs-geomapmaker.github.io/fgdc-geoage-font/fgdcgeoage.eot?#iefix') format('embedded-opentype'),
         url('//azgs-geomapmaker.github.io/fgdc-geoage-font/fgdcgeoage.woff') format('woff'),
         url('//azgs-geomapmaker.github.io/fgdc-geoage-font/fgdcgeoage.ttf') format('truetype'),
         url('//azgs-geomapmaker.github.io/fgdc-geoage-font/fgdcgeoage.svg#FGDCGeoAge') format('svg');
}
```

*Note*: As of Dec. 8, 2013, the suggested usage will work in all browsers except Firefox. To make sure that the site works in Firefox you must download the font files and host them on the same domain as your website. 

If you would like to download the font files themselves, They are available in the following formats:

- **Embedded OpenType**: [*download*](http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.eot)
- **Web Open Font Format**: [*download*](http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.woff)
- **TrueType Font**: [*download*](http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.ttf)
- **Scalable Vector Graphics**: [*download*](http://ncgmp09.github.io/fgdc-geoage-font/fgdcgeoage.svg)

Thanks to Font Squirrel's [Webfont Generator](http://www.fontsquirrel.com/tools/webfont-generator) for doing all the lifting.
