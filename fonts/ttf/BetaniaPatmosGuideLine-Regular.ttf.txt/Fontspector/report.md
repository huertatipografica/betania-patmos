## FontSpector report

fontspector version: 1.5.1






## Check results




<details><summary>[4] </summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** BetaniaPatmosGuideLine-Regular.ttf missing required codepoints:

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








- ⚠️ **WARN** BetaniaPatmosGuideLine-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, coptic, duployan, syriac, hebrew, math, tai-le, todhri, malayalam, canadian-aboriginal
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


<details><summary>[17] BetaniaPatmosGuideLine-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. (case_mapping)</summary>
    <div>








- 🔥 **FAIL** The following glyphs are missing case-swapping counterparts:

| Glyph present in the font                      | Missing case-swapping counterpart            |
|------------------------------------------------|----------------------------------------------|
| U+00DD: LATIN CAPITAL LETTER Y WITH ACUTE      | U+00FD: LATIN SMALL LETTER Y WITH ACUTE      |
| U+0102: LATIN CAPITAL LETTER A WITH BREVE      | U+0103: LATIN SMALL LETTER A WITH BREVE      |
| U+00DB: LATIN CAPITAL LETTER U WITH CIRCUMFLEX | U+00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX |
| U+0178: LATIN CAPITAL LETTER Y WITH DIAERESIS  | U+00FF: LATIN SMALL LETTER Y WITH DIAERESIS  |
| U+00C5: LATIN CAPITAL LETTER A WITH RING ABOVE | U+00E5: LATIN SMALL LETTER A WITH RING ABOVE |
| U+1E80: LATIN CAPITAL LETTER W WITH GRAVE      | U+1E81: LATIN SMALL LETTER W WITH GRAVE      |
| U+1E84: LATIN CAPITAL LETTER W WITH DIAERESIS  | U+1E85: LATIN SMALL LETTER W WITH DIAERESIS  |
| U+0132: LATIN CAPITAL LIGATURE IJ              | U+0133: LATIN SMALL LIGATURE IJ              |
| U+0174: LATIN CAPITAL LETTER W WITH CIRCUMFLEX | U+0175: LATIN SMALL LETTER W WITH CIRCUMFLEX |
| U+0100: LATIN CAPITAL LETTER A WITH MACRON     | U+0101: LATIN SMALL LETTER A WITH MACRON     |
| U+1E82: LATIN CAPITAL LETTER W WITH ACUTE      | U+1E83: LATIN SMALL LETTER W WITH ACUTE      |
| U+0176: LATIN CAPITAL LETTER Y WITH CIRCUMFLEX | U+0177: LATIN SMALL LETTER Y WITH CIRCUMFLEX |
| U+00D4: LATIN CAPITAL LETTER O WITH CIRCUMFLEX | U+00F4: LATIN SMALL LETTER O WITH CIRCUMFLEX |
| U+00CE: LATIN CAPITAL LETTER I WITH CIRCUMFLEX | U+00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX |
| U+1EF2: LATIN CAPITAL LETTER Y WITH GRAVE      | U+1EF3: LATIN SMALL LETTER Y WITH GRAVE      |
| U+00C2: LATIN CAPITAL LETTER A WITH CIRCUMFLEX | U+00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX |
| U+00CA: LATIN CAPITAL LETTER E WITH CIRCUMFLEX | U+00EA: LATIN SMALL LETTER E WITH CIRCUMFLEX | [code: missing-case-counterparts]
  
  

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








- 🔥 **FAIL** "Betania Patmos GuideLine" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
  
  

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
* C (U+0043): found 4, expected one of: {5, 2, 1}
* I (U+0049): found 4, expected one of: {1, 3, 2}
* Itilde (U+0128): found 4, expected one of: {6, 3, 2}
* J (U+004A): found 4, expected one of: {1, 2, 3}
* S (U+0053): found 4, expected one of: {1, 2, 5}
* U (U+0055): found 4, expected one of: {2, 5, 1}
* Uacute (U+00DA): found 4, expected one of: {3, 6, 2}
* Ugrave (U+00D9): found 4, expected one of: {3, 2, 6}
* Utilde (U+0168): found 4, expected one of: {2, 3, 6}
... and 141 others [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 710 among a set of 16  math glyphs.
The following math glyphs have a different width, though:
width=687: logicalnot
width=501: multiply
width=646: approxequal
width=618: notequal
width=636: uni2237
width=653: lessequal
width=621: greater, less
width=638: uni2238
width=671: uni2239 [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. (name/family_and_style_max_length)</summary>
    <div>








- ⚠️ **WARN** Name ID 6 'PostScript Name' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms. [code: nameid6-too-long]
  
  

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
... and 35 others [code: unreachable-glyphs]
  
  

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
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* one.dnom: Line { p0: (206.0, 367.0), p1: (207.0, 367.0) } -> Line { p0: (207.0, 367.0), p1: (208.0, 367.0) }
* three.dnom: Line { p0: (101.0, 170.0), p1: (101.0, 171.0) } -> Line { p0: (101.0, 171.0), p1: (101.0, 172.0) }
* seven.dnom: Line { p0: (343.0, 338.0), p1: (343.0, 336.0) } -> Line { p0: (343.0, 336.0), p1: (343.0, 335.0) }
* one.numr: Line { p0: (206.0, 767.0), p1: (207.0, 767.0) } -> Line { p0: (207.0, 767.0), p1: (208.0, 767.0) }
* three.numr: Line { p0: (101.0, 570.0), p1: (101.0, 571.0) } -> Line { p0: (101.0, 571.0), p1: (101.0, 572.0) }
* seven.numr: Line { p0: (343.0, 738.0), p1: (343.0, 736.0) } -> Line { p0: (343.0, 736.0), p1: (343.0, 735.0) }
* uni2081 (U+2081): Line { p0: (143.0, 367.0), p1: (144.0, 367.0) } -> Line { p0: (144.0, 367.0), p1: (145.0, 367.0) }
* uni2083 (U+2083): Line { p0: (37.0, 170.0), p1: (37.0, 171.0) } -> Line { p0: (37.0, 171.0), p1: (37.0, 172.0) }
* uni2087 (U+2087): Line { p0: (278.0, 338.0), p1: (278.0, 336.0) } -> Line { p0: (278.0, 336.0), p1: (278.0, 335.0) }
... and 3 others [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* oslash.fina: Line(Line { p0: (0.0, 773.0), p1: (0.0, 780.0) }) has the same coordinates as a previous segment.
* oslash.fina: Line(Line { p0: (0.0, 417.0), p1: (0.0, 424.0) }) has the same coordinates as a previous segment.
* oslash.fina: Line(Line { p0: (0.0, -7.0), p1: (0.0, 11.0) }) has the same coordinates as a previous segment.
* oslash.fina: Line(Line { p0: (0.0, -370.0), p1: (0.0, -363.0) }) has the same coordinates as a previous segment.
* t.fina: Line(Line { p0: (418.0, 780.0), p1: (418.0, 773.0) }) has the same coordinates as a previous segment.
* t.fina: Line(Line { p0: (418.0, 424.0), p1: (418.0, 417.0) }) has the same coordinates as a previous segment.
* t.fina: Line(Line { p0: (418.0, 11.0), p1: (418.0, -7.0) }) has the same coordinates as a previous segment.
* t.fina: Line(Line { p0: (418.0, -363.0), p1: (418.0, -370.0) }) has the same coordinates as a previous segment.
* t.isol: Line(Line { p0: (418.0, 780.0), p1: (418.0, 773.0) }) has the same coordinates as a previous segment.
... and 19 others [code: overlapping-path-segments]
  
  

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








- ℹ️ **INFO** OS/2 xAvgCharWidth is 564 but it should be 563 which corresponds to the average of the widths of all glyphs in the font. These are similar values, which may be a symptom of the slightly different calculation of the xAvgCharWidth value in font editors. There's further discussion on this at https://github.com/fonttools/fontbakery/issues/1622 [code: xAvgCharWidth-close]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | BetaniaPatmosGuideLine-Regular.ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 83156 |
 | Hinted Size   | 118780   |
 | Increase      | 35624      |
 | Change        | 42.8 %  | [code: size-impact]
  
  

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
| 5 | 9 | 7 | 93 | 72 | 
| 3% | 5% | 4% | 50% | 39% | 



