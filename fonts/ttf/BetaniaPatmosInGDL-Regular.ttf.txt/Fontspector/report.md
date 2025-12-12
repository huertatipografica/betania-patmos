## FontSpector report

fontspector version: 1.5.1






## Check results




<details><summary>[17] BetaniaPatmosInGDL-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. (case_mapping)</summary>
    <div>








- 🔥 **FAIL** The following glyphs are missing case-swapping counterparts:

| Glyph present in the font                      | Missing case-swapping counterpart            |
|------------------------------------------------|----------------------------------------------|
| U+1E80: LATIN CAPITAL LETTER W WITH GRAVE      | U+1E81: LATIN SMALL LETTER W WITH GRAVE      |
| U+00D4: LATIN CAPITAL LETTER O WITH CIRCUMFLEX | U+00F4: LATIN SMALL LETTER O WITH CIRCUMFLEX |
| U+1E84: LATIN CAPITAL LETTER W WITH DIAERESIS  | U+1E85: LATIN SMALL LETTER W WITH DIAERESIS  |
| U+00C2: LATIN CAPITAL LETTER A WITH CIRCUMFLEX | U+00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX |
| U+00DD: LATIN CAPITAL LETTER Y WITH ACUTE      | U+00FD: LATIN SMALL LETTER Y WITH ACUTE      |
| U+0176: LATIN CAPITAL LETTER Y WITH CIRCUMFLEX | U+0177: LATIN SMALL LETTER Y WITH CIRCUMFLEX |
| U+00C5: LATIN CAPITAL LETTER A WITH RING ABOVE | U+00E5: LATIN SMALL LETTER A WITH RING ABOVE |
| U+00DB: LATIN CAPITAL LETTER U WITH CIRCUMFLEX | U+00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX |
| U+0100: LATIN CAPITAL LETTER A WITH MACRON     | U+0101: LATIN SMALL LETTER A WITH MACRON     |
| U+00CA: LATIN CAPITAL LETTER E WITH CIRCUMFLEX | U+00EA: LATIN SMALL LETTER E WITH CIRCUMFLEX |
| U+00CE: LATIN CAPITAL LETTER I WITH CIRCUMFLEX | U+00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX |
| U+0102: LATIN CAPITAL LETTER A WITH BREVE      | U+0103: LATIN SMALL LETTER A WITH BREVE      |
| U+1EF2: LATIN CAPITAL LETTER Y WITH GRAVE      | U+1EF3: LATIN SMALL LETTER Y WITH GRAVE      |
| U+0174: LATIN CAPITAL LETTER W WITH CIRCUMFLEX | U+0175: LATIN SMALL LETTER W WITH CIRCUMFLEX |
| U+0178: LATIN CAPITAL LETTER Y WITH DIAERESIS  | U+00FF: LATIN SMALL LETTER Y WITH DIAERESIS  |
| U+1E82: LATIN CAPITAL LETTER W WITH ACUTE      | U+1E83: LATIN SMALL LETTER W WITH ACUTE      |
| U+0132: LATIN CAPITAL LIGATURE IJ              | U+0133: LATIN SMALL LIGATURE IJ              | [code: missing-case-counterparts]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Whitespace glyphs have ink? (whitespace_ink)</summary>
    <div>








- 🔥 **FAIL** The following glyphs have ink; they should be replaced by an empty glyph:

* space [code: has-ink]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check family name for GF Guide compliance. (googlefonts/name/family_name_compliance)</summary>
    <div>








- 🔥 **FAIL** "Betania Patmos In GDL" contains an abbreviation. [code: abbreviation]
  
  

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
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* U (U+0055): found 4, expected one of: {5, 2, 1}
* Uacute (U+00DA): found 5, expected one of: {3, 2, 6}
* Ugrave (U+00D9): found 5, expected one of: {6, 2, 3}
* Utilde (U+0168): found 5, expected one of: {6, 2, 3}
* V (U+0056): found 4, expected one of: {1, 2, 5}
* uniA78B (U+A78B): found 4, expected one of: {1}
* c (U+0063): found 4, expected one of: {1, 5, 3}
* ccedilla (U+00E7): found 5, expected one of: {2, 1, 6}
* dotlessi (U+0131): found 4, expected one of: {2, 1}
... and 114 others [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 710 among a set of 16  math glyphs.
The following math glyphs have a different width, though:
width=653: lessequal
width=671: uni2239
width=618: notequal
width=501: multiply
width=687: logicalnot
width=646: approxequal
width=600: uni2237, uni2238
width=621: greater, less [code: width-outliers]
  
  

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
... and 34 others [code: unreachable-glyphs]
  
  

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
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* B (U+0042): Line(Line { p0: (630.0, 773.0), p1: (369.0, 773.0) })/Quad(QuadBez { p0: (369.0, 773.0), p1: (399.0, 770.0), p2: (432.0, 756.0) }) = 5.710593137499633
* B (U+0042): Quad(QuadBez { p0: (421.0, 52.0), p1: (371.0, 23.0), p2: (310.0, 11.0) })/Line(Line { p0: (310.0, 11.0), p1: (630.0, 11.0) }) = 11.129189289611167
* C (U+0043): Quad(QuadBez { p0: (134.5, 664.5), p1: (188.0, 752.0), p2: (296.0, 773.0) })/Line(Line { p0: (296.0, 773.0), p1: (0.0, 773.0) }) = 11.003540851749507
* C (U+0043): Line(Line { p0: (635.0, 773.0), p1: (458.0, 773.0) })/Quad(QuadBez { p0: (458.0, 773.0), p1: (478.0, 770.0), p2: (499.0, 766.0) }) = 8.530765609948139
* Ccedilla (U+00C7): Quad(QuadBez { p0: (134.5, 664.5), p1: (188.0, 752.0), p2: (296.0, 773.0) })/Line(Line { p0: (296.0, 773.0), p1: (0.0, 773.0) }) = 11.003540851749507
* Ccedilla (U+00C7): Line(Line { p0: (635.0, 773.0), p1: (458.0, 773.0) })/Quad(QuadBez { p0: (458.0, 773.0), p1: (478.0, 770.0), p2: (499.0, 766.0) }) = 8.530765609948139
* D (U+0044): Line(Line { p0: (760.0, 773.0), p1: (374.0, 773.0) })/Quad(QuadBez { p0: (374.0, 773.0), p1: (472.0, 764.0), p2: (535.0, 721.0) }) = 5.247138901616463
* D (U+0044): Quad(QuadBez { p0: (471.0, 88.0), p1: (392.0, 32.0), p2: (285.0, 11.0) })/Line(Line { p0: (285.0, 11.0), p1: (760.0, 11.0) }) = 11.103833436636105
* Eth (U+00D0): Line(Line { p0: (760.0, 773.0), p1: (374.0, 773.0) })/Quad(QuadBez { p0: (374.0, 773.0), p1: (472.0, 764.0), p2: (535.0, 721.0) }) = 5.247138901616463
... and 419 others [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* v (U+0076): Line(Line { p0: (515.0, 332.0), p1: (515.0, 332.0) }) has the same coordinates as a previous segment.
* t.fina: Line(Line { p0: (418.0, 780.0), p1: (418.0, 773.0) }) has the same coordinates as a previous segment.
* t.fina: Line(Line { p0: (418.0, 419.0), p1: (418.0, 417.0) }) has the same coordinates as a previous segment.
* t.fina: Line(Line { p0: (418.0, -5.0), p1: (418.0, -7.0) }) has the same coordinates as a previous segment.
* t.fina: Line(Line { p0: (418.0, -363.0), p1: (418.0, -370.0) }) has the same coordinates as a previous segment.
* v.fina: Line(Line { p0: (515.0, 332.0), p1: (515.0, 332.0) }) has the same coordinates as a previous segment.
* v.init: Line(Line { p0: (515.0, 332.0), p1: (515.0, 332.0) }) has the same coordinates as a previous segment.
* t.isol: Line(Line { p0: (418.0, 780.0), p1: (418.0, 773.0) }) has the same coordinates as a previous segment.
* t.isol: Line(Line { p0: (418.0, 419.0), p1: (418.0, 417.0) }) has the same coordinates as a previous segment.
... and 28 others [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* AE (U+00C6): Line(Line { p0: (477.0, 424.0), p1: (478.0, 715.0) })
* AE (U+00C6): Line(Line { p0: (475.0, 11.0), p1: (476.0, 311.0) })
* A_N_D: Line(Line { p0: (117.0, 27.0), p1: (118.0, 417.0) })
* A_N_D: Line(Line { p0: (118.0, 424.0), p1: (119.0, 745.0) })
* A_N_D: Line(Line { p0: (183.0, 638.0), p1: (182.0, 424.0) })
* A_N_D: Line(Line { p0: (182.0, 243.0), p1: (181.0, 27.0) })
* h (U+0068): Line(Line { p0: (151.0, 424.0), p1: (150.0, 637.0) })
* h (U+0068): Line(Line { p0: (214.0, 637.0), p1: (215.0, 424.0) })
* h (U+0068): Line(Line { p0: (215.0, 202.0), p1: (216.0, 27.0) })
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
    <summary>ℹ️ <b>INFO</b> Checking OS/2 fsSelection value. (opentype/xavgcharwidth)</summary>
    <div>








- ℹ️ **INFO** OS/2 xAvgCharWidth is 570 but it should be 569 which corresponds to the average of the widths of all glyphs in the font. These are similar values, which may be a symptom of the slightly different calculation of the xAvgCharWidth value in font editors. There's further discussion on this at https://github.com/fonttools/fontbakery/issues/1622 [code: xAvgCharWidth-close]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | BetaniaPatmosInGDL-Regular.ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 177692 |
 | Hinted Size   | 302156   |
 | Increase      | 124464      |
 | Change        | 70.0 %  | [code: size-impact]
  
  

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


<details><summary>[4] </summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** BetaniaPatmosInGDL-Regular.ttf missing required codepoints:

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








- ⚠️ **WARN** BetaniaPatmosInGDL-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, tai-le, duployan, syriac, tifinagh, hebrew, old-permic, todhri, math, malayalam, coptic
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






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 5 | 9 | 7 | 94 | 71 | 
| 3% | 5% | 4% | 51% | 38% | 



