## FontSpector report

fontspector version: 1.5.1






## Check results




<details><summary>[4] </summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** BetaniaPatmos-Regular.ttf missing required codepoints:

* 0x00AA: FEMININE ORDINAL INDICATOR
* 0x00BA: MASCULINE ORDINAL INDICATOR
* 0x00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX
* 0x00E5: LATIN SMALL LETTER A WITH RING ABOVE
* 0x00EA: LATIN SMALL LETTER E WITH CIRCUMFLEX
* 0x00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX
* 0x00F4: LATIN SMALL LETTER O WITH CIRCUMFLEX
* 0x00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX
* 0x00FD: LATIN SMALL LETTER Y WITH ACUTE
... and 92 others [code: missing-codepoints]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** BetaniaPatmos-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
* U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, todhri, canadian-aboriginal, duployan, old-permic, hebrew, syriac, coptic, malayalam, math
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0327 COMBINING CEDILLA: try adding math
... and 63 others

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin [code: unreachable-subsetting]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file (googlefonts/description/has_article)</summary>
    <div>








- ℹ️ **INFO** This font doesn't have an ARTICLE.en_us.html file. [code: missing-article]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. (googlefonts/STAT/axis_order)</summary>
    <div>








- ℹ️ **INFO** All of the fonts lack a STAT table. [code: summary]
  
  

  

</div>
</details>


</div>
</details>


<details><summary>[12] BetaniaPatmos-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. (case_mapping)</summary>
    <div>








- 🔥 **FAIL** The following glyphs are missing case-swapping counterparts:

| Glyph present in the font                      | Missing case-swapping counterpart            |
|------------------------------------------------|----------------------------------------------|
| U+00C2: LATIN CAPITAL LETTER A WITH CIRCUMFLEX | U+00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX |
| U+1E84: LATIN CAPITAL LETTER W WITH DIAERESIS  | U+1E85: LATIN SMALL LETTER W WITH DIAERESIS  |
| U+0174: LATIN CAPITAL LETTER W WITH CIRCUMFLEX | U+0175: LATIN SMALL LETTER W WITH CIRCUMFLEX |
| U+00CA: LATIN CAPITAL LETTER E WITH CIRCUMFLEX | U+00EA: LATIN SMALL LETTER E WITH CIRCUMFLEX |
| U+00C5: LATIN CAPITAL LETTER A WITH RING ABOVE | U+00E5: LATIN SMALL LETTER A WITH RING ABOVE |
| U+1EF2: LATIN CAPITAL LETTER Y WITH GRAVE      | U+1EF3: LATIN SMALL LETTER Y WITH GRAVE      |
| U+00CE: LATIN CAPITAL LETTER I WITH CIRCUMFLEX | U+00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX |
| U+00DD: LATIN CAPITAL LETTER Y WITH ACUTE      | U+00FD: LATIN SMALL LETTER Y WITH ACUTE      |
| U+1E80: LATIN CAPITAL LETTER W WITH GRAVE      | U+1E81: LATIN SMALL LETTER W WITH GRAVE      |
| U+0176: LATIN CAPITAL LETTER Y WITH CIRCUMFLEX | U+0177: LATIN SMALL LETTER Y WITH CIRCUMFLEX |
| U+00D4: LATIN CAPITAL LETTER O WITH CIRCUMFLEX | U+00F4: LATIN SMALL LETTER O WITH CIRCUMFLEX |
| U+0100: LATIN CAPITAL LETTER A WITH MACRON     | U+0101: LATIN SMALL LETTER A WITH MACRON     |
| U+0102: LATIN CAPITAL LETTER A WITH BREVE      | U+0103: LATIN SMALL LETTER A WITH BREVE      |
| U+0178: LATIN CAPITAL LETTER Y WITH DIAERESIS  | U+00FF: LATIN SMALL LETTER Y WITH DIAERESIS  |
| U+1E82: LATIN CAPITAL LETTER W WITH ACUTE      | U+1E83: LATIN SMALL LETTER W WITH ACUTE      |
| U+00DB: LATIN CAPITAL LETTER U WITH CIRCUMFLEX | U+00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX |
| U+0132: LATIN CAPITAL LIGATURE IJ              | U+0133: LATIN SMALL LIGATURE IJ              | [code: missing-case-counterparts]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

* uni0308
* uni0307
* gravecomb
* acutecomb
* uni0302
* uni030C
* uni0306
* uni030A
* tildecomb
... and 4 others [code: unattached-dotted-circle-marks]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 710 among a set of 16  math glyphs.
The following math glyphs have a different width, though:
width=638: divide, uni2238
width=501: multiply
width=646: approxequal
width=636: uni2237
width=618: notequal
width=621: less, greater
width=722: uni2239
width=653: lessequal
width=687: logicalnot
width=688: plus [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* b.init
* eth.init
* e.init
* eacute.init
* edieresis.init
* egrave.init
* uni1EBD.init
* f.init
* h.init
... and 33 others [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:

* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* v (U+0076): Line(Line { p0: (515.0, 332.0), p1: (515.0, 332.0) }) has the same coordinates as a previous segment.
* v.fina: Line(Line { p0: (515.0, 332.0), p1: (515.0, 332.0) }) has the same coordinates as a previous segment.
* v.init: Line(Line { p0: (515.0, 332.0), p1: (515.0, 332.0) }) has the same coordinates as a previous segment.
* v.isol: Line(Line { p0: (515.0, 332.0), p1: (515.0, 332.0) }) has the same coordinates as a previous segment.
* v.from.bottom: Line(Line { p0: (539.0, 332.0), p1: (539.0, 332.0) }) has the same coordinates as a previous segment.
* v.from.middle: Line(Line { p0: (507.0, 332.0), p1: (507.0, 332.0) }) has the same coordinates as a previous segment.
* v.from.top: Line(Line { p0: (410.0, 332.0), p1: (410.0, 332.0) }) has the same coordinates as a previous segment.
* v.from.bottom.fina: Line(Line { p0: (539.0, 332.0), p1: (539.0, 332.0) }) has the same coordinates as a previous segment.
* v.from.middle.fina: Line(Line { p0: (507.0, 332.0), p1: (507.0, 332.0) }) has the same coordinates as a previous segment.
... and 3 others [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* AE (U+00C6): Line(Line { p0: (475.0, 0.0), p1: (476.0, 311.0) })
* AE (U+00C6): Line(Line { p0: (477.0, 374.0), p1: (478.0, 715.0) })
* T (U+0054): Line(Line { p0: (60.0, 776.0), p1: (568.0, 775.0) })
* A_N_D: Line(Line { p0: (117.0, 27.0), p1: (119.0, 745.0) })
* A_N_D: Line(Line { p0: (182.0, 243.0), p1: (181.0, 27.0) })
* A_N_D: Line(Line { p0: (183.0, 638.0), p1: (182.0, 303.0) })
* h (U+0068): Line(Line { p0: (151.0, 221.0), p1: (150.0, 637.0) })
* h (U+0068): Line(Line { p0: (215.0, 202.0), p1: (216.0, 27.0) })
* h (U+0068): Line(Line { p0: (214.0, 637.0), p1: (215.0, 335.0) })
... and 69 others [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | BetaniaPatmos-Regular.ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 144904 |
 | Hinted Size   | 193600   |
 | Increase      | 48696      |
 | Change        | 33.6 %  | [code: size-impact]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? (required_tables)</summary>
    <div>








- ℹ️ **INFO** This font contains the following optional tables:

    cvt 
    fpgm
    loca
    prep
    GPOS
    GSUB
    gasp [code: optional-tables]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table
set to optimize rendering? (googlefonts/gasp)</summary>
    <div>








- ℹ️ **INFO** These are the ppm ranges declared on the gasp table:

| PPM <= 65535 | - Use grid-fitting                                    |
|              | 	- Use grayscale rendering                            |
|              | 	- Use gridfitting with ClearType symmetric smoothing |
|              | 	- Use smoothing along multiple axes with ClearType®  |
|--------------|-------------------------------------------------------|
 [code: ranges]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? (googlefonts/old_ttfautohint)</summary>
    <div>








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 11.001; ttfautohint (v1.8.4.16-eb64) [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 3 | 7 | 6 | 99 | 71 | 
| 2% | 4% | 3% | 54% | 38% | 



