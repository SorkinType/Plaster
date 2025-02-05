## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure VFs have 'ital' STAT axis. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-STAT-ital-axis">opentype/STAT/ital_axis</a></summary>
    <div>







* 🔥 **FAIL** <p>Font fonts/ttf/Plaster-Regular.ttf has no STAT table</p>
 [code: no-stat]



* 🔥 **FAIL** <p>Font fonts/ttf/Plaster-Italic.ttf has no STAT table</p>
 [code: no-stat]



</div>
</details>
</div>
</details>

<details><summary>[15] Plaster-Italic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-license-OFL-copyright">googlefonts/license/OFL_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Plaster Regular: OS/2 sTypoAscender is 2054 when it should be 2000</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Plaster Regular: hhea Ascender is 2054 when it should be 2000</p>
 [code: bad-hhea-ascender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#alt-caron">alt_caron</a></summary>
    <div>









* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: two	Contours detected: 4	Expected: 1

- Glyph name: three	Contours detected: 3	Expected: 1

- Glyph name: five	Contours detected: 4	Expected: 1

- Glyph name: six	Contours detected: 3	Expected: 1 or 2

- Glyph name: seven	Contours detected: 2	Expected: 1

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: nine	Contours detected: 3	Expected: 1 or 2

- Glyph name: question	Contours detected: 3	Expected: 2

- Glyph name: A	Contours detected: 1	Expected: 2

- Glyph name: C	Contours detected: 3	Expected: 1

- Glyph name: E	Contours detected: 3	Expected: 1

- Glyph name: F	Contours detected: 2	Expected: 1

- Glyph name: G	Contours detected: 3	Expected: 1

- Glyph name: J	Contours detected: 2	Expected: 1

- Glyph name: K	Contours detected: 3	Expected: 1 or 2

- Glyph name: L	Contours detected: 2	Expected: 1

- Glyph name: M	Contours detected: 3	Expected: 1

- Glyph name: N	Contours detected: 2	Expected: 1

- Glyph name: Q	Contours detected: 3	Expected: 2

- Glyph name: S	Contours detected: 3	Expected: 1

- Glyph name: T	Contours detected: 3	Expected: 1

- Glyph name: U	Contours detected: 2	Expected: 1

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: W	Contours detected: 3	Expected: 1 or 2

- Glyph name: X	Contours detected: 2	Expected: 1

- Glyph name: Y	Contours detected: 2	Expected: 1

- Glyph name: Z	Contours detected: 3	Expected: 1

- Glyph name: c	Contours detected: 3	Expected: 1

- Glyph name: e	Contours detected: 3	Expected: 2

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: h	Contours detected: 2	Expected: 1

- Glyph name: k	Contours detected: 3	Expected: 1 or 2

- Glyph name: m	Contours detected: 3	Expected: 1

- Glyph name: n	Contours detected: 2	Expected: 1

- Glyph name: r	Contours detected: 2	Expected: 1

- Glyph name: s	Contours detected: 3	Expected: 1

- Glyph name: t	Contours detected: 2	Expected: 1

- Glyph name: u	Contours detected: 2	Expected: 1

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 3	Expected: 1

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: z	Contours detected: 3	Expected: 1

- Glyph name: cent	Contours detected: 5	Expected: 1 or 2

- Glyph name: sterling	Contours detected: 3	Expected: 1 or 2

- Glyph name: section	Contours detected: 3	Expected: 2

- Glyph name: copyright	Contours detected: 5	Expected: 3

- Glyph name: uni00B2	Contours detected: 4	Expected: 1

- Glyph name: uni00B3	Contours detected: 3	Expected: 1

- Glyph name: uni00B5	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 5	Expected: 3

- Glyph name: threequarters	Contours detected: 5	Expected: 3 or 4

- Glyph name: questiondown	Contours detected: 3	Expected: 2

- Glyph name: Agrave	Contours detected: 2	Expected: 3

- Glyph name: Aacute	Contours detected: 2	Expected: 3

- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

- Glyph name: Atilde	Contours detected: 2	Expected: 3

- Glyph name: Adieresis	Contours detected: 3	Expected: 4

- Glyph name: AE	Contours detected: 3	Expected: 2

- Glyph name: Ccedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: Egrave	Contours detected: 4	Expected: 2

- Glyph name: Eacute	Contours detected: 4	Expected: 2

- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

- Glyph name: Edieresis	Contours detected: 5	Expected: 3

- Glyph name: Ntilde	Contours detected: 3	Expected: 2

- Glyph name: Ugrave	Contours detected: 3	Expected: 2

- Glyph name: Uacute	Contours detected: 3	Expected: 2

- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

- Glyph name: Udieresis	Contours detected: 4	Expected: 3

- Glyph name: Yacute	Contours detected: 3	Expected: 2

- Glyph name: germandbls	Contours detected: 2	Expected: 1

- Glyph name: ae	Contours detected: 4	Expected: 3

- Glyph name: ccedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: egrave	Contours detected: 4	Expected: 3

- Glyph name: eacute	Contours detected: 4	Expected: 3

- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

- Glyph name: edieresis	Contours detected: 5	Expected: 4

- Glyph name: ntilde	Contours detected: 3	Expected: 2

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: ugrave	Contours detected: 3	Expected: 2

- Glyph name: uacute	Contours detected: 3	Expected: 2

- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

- Glyph name: udieresis	Contours detected: 4	Expected: 3

- Glyph name: yacute	Contours detected: 3	Expected: 2

- Glyph name: ydieresis	Contours detected: 4	Expected: 3

- Glyph name: Amacron	Contours detected: 2	Expected: 3

- Glyph name: Abreve	Contours detected: 2	Expected: 3

- Glyph name: Aogonek	Contours detected: 1	Expected: 2 or 3

- Glyph name: Cacute	Contours detected: 4	Expected: 2

- Glyph name: cacute	Contours detected: 4	Expected: 2

- Glyph name: Ccircumflex	Contours detected: 4	Expected: 2

- Glyph name: ccircumflex	Contours detected: 4	Expected: 2

- Glyph name: Cdotaccent	Contours detected: 4	Expected: 2

- Glyph name: cdotaccent	Contours detected: 4	Expected: 2

- Glyph name: Ccaron	Contours detected: 4	Expected: 2

- Glyph name: ccaron	Contours detected: 4	Expected: 2

- Glyph name: Emacron	Contours detected: 4	Expected: 2

- Glyph name: emacron	Contours detected: 4	Expected: 3

- Glyph name: Ebreve	Contours detected: 4	Expected: 2

- Glyph name: ebreve	Contours detected: 4	Expected: 3

- Glyph name: Edotaccent	Contours detected: 4	Expected: 2

- Glyph name: edotaccent	Contours detected: 4	Expected: 3

- Glyph name: Eogonek	Contours detected: 4	Expected: 1 or 2

- Glyph name: eogonek	Contours detected: 4	Expected: 2

- Glyph name: Ecaron	Contours detected: 4	Expected: 2

- Glyph name: ecaron	Contours detected: 4	Expected: 3

- Glyph name: Gcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Gbreve	Contours detected: 4	Expected: 2

- Glyph name: Gdotaccent	Contours detected: 4	Expected: 2

- Glyph name: uni0122	Contours detected: 4	Expected: 2

- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

- Glyph name: uni0137	Contours detected: 4	Expected: 2 or 3

- Glyph name: kgreenlandic	Contours detected: 3	Expected: 1 or 2

- Glyph name: Lacute	Contours detected: 3	Expected: 2

- Glyph name: uni013B	Contours detected: 3	Expected: 2

- Glyph name: uni013C	Contours detected: 1	Expected: 2

- Glyph name: Lcaron	Contours detected: 3	Expected: 2

- Glyph name: Ldot	Contours detected: 3	Expected: 2

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: Nacute	Contours detected: 3	Expected: 2

- Glyph name: nacute	Contours detected: 3	Expected: 2

- Glyph name: uni0145	Contours detected: 3	Expected: 2

- Glyph name: uni0146	Contours detected: 3	Expected: 2

- Glyph name: Ncaron	Contours detected: 3	Expected: 2

- Glyph name: ncaron	Contours detected: 3	Expected: 2

- Glyph name: Eng	Contours detected: 2	Expected: 1

- Glyph name: eng	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 4	Expected: 2

- Glyph name: oe	Contours detected: 4	Expected: 3

- Glyph name: racute	Contours detected: 3	Expected: 2

- Glyph name: uni0157	Contours detected: 3	Expected: 2

- Glyph name: rcaron	Contours detected: 3	Expected: 2

- Glyph name: Sacute	Contours detected: 4	Expected: 2

- Glyph name: sacute	Contours detected: 4	Expected: 2

- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

- Glyph name: scircumflex	Contours detected: 4	Expected: 2

- Glyph name: Scedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: scedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: Scaron	Contours detected: 4	Expected: 2

- Glyph name: scaron	Contours detected: 4	Expected: 2

- Glyph name: uni0162	Contours detected: 4	Expected: 1 or 2

- Glyph name: Tcaron	Contours detected: 4	Expected: 2

- Glyph name: tcaron	Contours detected: 3	Expected: 2

- Glyph name: Tbar	Contours detected: 3	Expected: 1

- Glyph name: tbar	Contours detected: 3	Expected: 1

- Glyph name: Utilde	Contours detected: 3	Expected: 2

- Glyph name: utilde	Contours detected: 3	Expected: 2

- Glyph name: Umacron	Contours detected: 3	Expected: 2

- Glyph name: umacron	Contours detected: 3	Expected: 2

- Glyph name: Ubreve	Contours detected: 3	Expected: 2

- Glyph name: ubreve	Contours detected: 3	Expected: 2

- Glyph name: Uring	Contours detected: 4	Expected: 3

- Glyph name: uring	Contours detected: 4	Expected: 3

- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: Uogonek	Contours detected: 3	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

- Glyph name: Zacute	Contours detected: 4	Expected: 2

- Glyph name: zacute	Contours detected: 4	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

- Glyph name: zdotaccent	Contours detected: 4	Expected: 2

- Glyph name: Zcaron	Contours detected: 4	Expected: 2

- Glyph name: zcaron	Contours detected: 4	Expected: 2

- Glyph name: uni0186	Contours detected: 3	Expected: 1

- Glyph name: uni018A	Contours detected: 3	Expected: 2

- Glyph name: uni018E	Contours detected: 3	Expected: 1

- Glyph name: uni018F	Contours detected: 3	Expected: 2

- Glyph name: uni0190	Contours detected: 3	Expected: 1

- Glyph name: florin	Contours detected: 3	Expected: 1

- Glyph name: uni0198	Contours detected: 3	Expected: 1

- Glyph name: uni0199	Contours detected: 4	Expected: 1

- Glyph name: uni019C	Contours detected: 3	Expected: 1

- Glyph name: uni019D	Contours detected: 2	Expected: 1

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: Uhorn	Contours detected: 3	Expected: 1

- Glyph name: uhorn	Contours detected: 3	Expected: 1

- Glyph name: uni01B3	Contours detected: 3	Expected: 1

- Glyph name: uni01B4	Contours detected: 3	Expected: 1

- Glyph name: uni01CD	Contours detected: 2	Expected: 3

- Glyph name: uni01D3	Contours detected: 3	Expected: 2

- Glyph name: uni01D4	Contours detected: 3	Expected: 2

- Glyph name: uni01D7	Contours detected: 5	Expected: 4

- Glyph name: uni01D8	Contours detected: 5	Expected: 4

- Glyph name: uni01DD	Contours detected: 3	Expected: 2

- Glyph name: uni01DE	Contours detected: 4	Expected: 5

- Glyph name: uni01E2	Contours detected: 4	Expected: 3

- Glyph name: uni01E3	Contours detected: 5	Expected: 4

- Glyph name: Gcaron	Contours detected: 4	Expected: 2

- Glyph name: uni01E8	Contours detected: 4	Expected: 2

- Glyph name: uni01E9	Contours detected: 4	Expected: 2

- Glyph name: uni01F8	Contours detected: 3	Expected: 2

- Glyph name: uni01F9	Contours detected: 3	Expected: 2

- Glyph name: AEacute	Contours detected: 4	Expected: 3

- Glyph name: aeacute	Contours detected: 5	Expected: 4

- Glyph name: uni0218	Contours detected: 4	Expected: 2

- Glyph name: uni0219	Contours detected: 4	Expected: 2

- Glyph name: uni021A	Contours detected: 4	Expected: 2

- Glyph name: uni0226	Contours detected: 2	Expected: 3

- Glyph name: uni0228	Contours detected: 4	Expected: 1

- Glyph name: uni0229	Contours detected: 4	Expected: 2

- Glyph name: uni0232	Contours detected: 3	Expected: 2

- Glyph name: uni0233	Contours detected: 3	Expected: 2

- Glyph name: uni0259	Contours detected: 3	Expected: 2

- Glyph name: uni0272	Contours detected: 2	Expected: 1

- Glyph name: uni0394	Contours detected: 1	Expected: 2

- Glyph name: uni03A9	Contours detected: 2	Expected: 1

- Glyph name: pi	Contours detected: 3	Expected: 1

- Glyph name: uni1E02	Contours detected: 3	Expected: 4

- Glyph name: uni1E14	Contours detected: 5	Expected: 3

- Glyph name: uni1E15	Contours detected: 5	Expected: 4

- Glyph name: uni1E1E	Contours detected: 3	Expected: 2

- Glyph name: uni1E1F	Contours detected: 3	Expected: 2

- Glyph name: uni1E20	Contours detected: 4	Expected: 2

- Glyph name: uni1E25	Contours detected: 3	Expected: 2

- Glyph name: uni1E36	Contours detected: 3	Expected: 2

- Glyph name: uni1E3E	Contours detected: 4	Expected: 2

- Glyph name: uni1E3F	Contours detected: 4	Expected: 2

- Glyph name: uni1E40	Contours detected: 4	Expected: 2

- Glyph name: uni1E41	Contours detected: 4	Expected: 2

- Glyph name: uni1E42	Contours detected: 4	Expected: 2

- Glyph name: uni1E43	Contours detected: 4	Expected: 2

- Glyph name: uni1E44	Contours detected: 3	Expected: 2

- Glyph name: uni1E45	Contours detected: 3	Expected: 2

- Glyph name: uni1E46	Contours detected: 3	Expected: 2

- Glyph name: uni1E47	Contours detected: 3	Expected: 2

- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

- Glyph name: uni1E60	Contours detected: 4	Expected: 2

- Glyph name: uni1E61	Contours detected: 4	Expected: 2

- Glyph name: uni1E62	Contours detected: 4	Expected: 2

- Glyph name: uni1E63	Contours detected: 4	Expected: 2

- Glyph name: uni1E6A	Contours detected: 4	Expected: 2

- Glyph name: uni1E6B	Contours detected: 3	Expected: 2

- Glyph name: uni1E6C	Contours detected: 4	Expected: 2

- Glyph name: uni1E6D	Contours detected: 3	Expected: 2

- Glyph name: Wgrave	Contours detected: 4	Expected: 2

- Glyph name: wgrave	Contours detected: 4	Expected: 2

- Glyph name: Wacute	Contours detected: 4	Expected: 2

- Glyph name: wacute	Contours detected: 4	Expected: 2

- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

- Glyph name: wdieresis	Contours detected: 5	Expected: 3

- Glyph name: uni1E92	Contours detected: 4	Expected: 2

- Glyph name: uni1E93	Contours detected: 4	Expected: 2

- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

- Glyph name: uni1EA0	Contours detected: 2	Expected: 3

- Glyph name: uni1EA2	Contours detected: 2	Expected: 3

- Glyph name: uni1EA4	Contours detected: 3	Expected: 4

- Glyph name: uni1EA6	Contours detected: 3	Expected: 4

- Glyph name: uni1EA8	Contours detected: 3	Expected: 4

- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

- Glyph name: uni1EAC	Contours detected: 3	Expected: 4

- Glyph name: uni1EAE	Contours detected: 3	Expected: 4

- Glyph name: uni1EB0	Contours detected: 3	Expected: 4

- Glyph name: uni1EB2	Contours detected: 3	Expected: 4

- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

- Glyph name: uni1EB6	Contours detected: 3	Expected: 4

- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

- Glyph name: uni1EBA	Contours detected: 4	Expected: 2

- Glyph name: uni1EBB	Contours detected: 4	Expected: 3

- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

- Glyph name: uni1EBE	Contours detected: 5	Expected: 3

- Glyph name: uni1EBF	Contours detected: 5	Expected: 4

- Glyph name: uni1EC0	Contours detected: 5	Expected: 3

- Glyph name: uni1EC1	Contours detected: 5	Expected: 4

- Glyph name: uni1EC2	Contours detected: 5	Expected: 3

- Glyph name: uni1EC3	Contours detected: 5	Expected: 4

- Glyph name: uni1EC4	Contours detected: 5	Expected: 3

- Glyph name: uni1EC5	Contours detected: 5	Expected: 4

- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

- Glyph name: uni1EC7	Contours detected: 5	Expected: 4

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

- Glyph name: uni1EE6	Contours detected: 3	Expected: 2

- Glyph name: uni1EE7	Contours detected: 3	Expected: 2

- Glyph name: uni1EE8	Contours detected: 4	Expected: 2

- Glyph name: uni1EE9	Contours detected: 4	Expected: 2

- Glyph name: uni1EEA	Contours detected: 4	Expected: 2

- Glyph name: uni1EEB	Contours detected: 4	Expected: 2

- Glyph name: uni1EEC	Contours detected: 4	Expected: 2

- Glyph name: uni1EED	Contours detected: 4	Expected: 2

- Glyph name: uni1EEE	Contours detected: 4	Expected: 2

- Glyph name: uni1EEF	Contours detected: 4	Expected: 2

- Glyph name: uni1EF0	Contours detected: 4	Expected: 2

- Glyph name: uni1EF1	Contours detected: 4	Expected: 2

- Glyph name: Ygrave	Contours detected: 3	Expected: 2

- Glyph name: ygrave	Contours detected: 3	Expected: 2

- Glyph name: uni1EF4	Contours detected: 3	Expected: 2

- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

- Glyph name: uni1EF6	Contours detected: 3	Expected: 2

- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

- Glyph name: trademark	Contours detected: 6	Expected: 2

- Glyph name: uni2206	Contours detected: 1	Expected: 2

- Glyph name: product	Contours detected: 3	Expected: 1

- Glyph name: summation	Contours detected: 3	Expected: 1

- Glyph name: integral	Contours detected: 3	Expected: 1

- Glyph name: fi	Contours detected: 4	Expected: 1, 2 or 3

- Glyph name: fl	Contours detected: 3	Expected: 1 or 2

- Glyph name: A	Contours detected: 1	Expected: 2

- Glyph name: AE	Contours detected: 3	Expected: 2

- Glyph name: AEacute	Contours detected: 4	Expected: 3

- Glyph name: Aacute	Contours detected: 2	Expected: 3

- Glyph name: Abreve	Contours detected: 2	Expected: 3

- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

- Glyph name: Adieresis	Contours detected: 3	Expected: 4

- Glyph name: Agrave	Contours detected: 2	Expected: 3

- Glyph name: Amacron	Contours detected: 2	Expected: 3

- Glyph name: Aogonek	Contours detected: 1	Expected: 2 or 3

- Glyph name: Atilde	Contours detected: 2	Expected: 3

- Glyph name: C	Contours detected: 3	Expected: 1

- Glyph name: Cacute	Contours detected: 4	Expected: 2

- Glyph name: Ccaron	Contours detected: 4	Expected: 2

- Glyph name: Ccedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: Ccircumflex	Contours detected: 4	Expected: 2

- Glyph name: Cdotaccent	Contours detected: 4	Expected: 2

- Glyph name: E	Contours detected: 3	Expected: 1

- Glyph name: Eacute	Contours detected: 4	Expected: 2

- Glyph name: Ebreve	Contours detected: 4	Expected: 2

- Glyph name: Ecaron	Contours detected: 4	Expected: 2

- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

- Glyph name: Edieresis	Contours detected: 5	Expected: 3

- Glyph name: Edotaccent	Contours detected: 4	Expected: 2

- Glyph name: Egrave	Contours detected: 4	Expected: 2

- Glyph name: Emacron	Contours detected: 4	Expected: 2

- Glyph name: Eng	Contours detected: 2	Expected: 1

- Glyph name: Eogonek	Contours detected: 4	Expected: 1 or 2

- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

- Glyph name: F	Contours detected: 2	Expected: 1

- Glyph name: G	Contours detected: 3	Expected: 1

- Glyph name: Gbreve	Contours detected: 4	Expected: 2

- Glyph name: Gcaron	Contours detected: 4	Expected: 2

- Glyph name: Gcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Gdotaccent	Contours detected: 4	Expected: 2

- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

- Glyph name: J	Contours detected: 2	Expected: 1

- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: K	Contours detected: 3	Expected: 1 or 2

- Glyph name: L	Contours detected: 2	Expected: 1

- Glyph name: Lacute	Contours detected: 3	Expected: 2

- Glyph name: Lcaron	Contours detected: 3	Expected: 2

- Glyph name: Ldot	Contours detected: 3	Expected: 2

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: M	Contours detected: 3	Expected: 1

- Glyph name: N	Contours detected: 2	Expected: 1

- Glyph name: Nacute	Contours detected: 3	Expected: 2

- Glyph name: Ncaron	Contours detected: 3	Expected: 2

- Glyph name: Ntilde	Contours detected: 3	Expected: 2

- Glyph name: OE	Contours detected: 4	Expected: 2

- Glyph name: Q	Contours detected: 3	Expected: 2

- Glyph name: S	Contours detected: 3	Expected: 1

- Glyph name: Sacute	Contours detected: 4	Expected: 2

- Glyph name: Scaron	Contours detected: 4	Expected: 2

- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

- Glyph name: T	Contours detected: 3	Expected: 1

- Glyph name: Tbar	Contours detected: 3	Expected: 1

- Glyph name: Tcaron	Contours detected: 4	Expected: 2

- Glyph name: U	Contours detected: 2	Expected: 1

- Glyph name: Uacute	Contours detected: 3	Expected: 2

- Glyph name: Ubreve	Contours detected: 3	Expected: 2

- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

- Glyph name: Udieresis	Contours detected: 4	Expected: 3

- Glyph name: Ugrave	Contours detected: 3	Expected: 2

- Glyph name: Uhorn	Contours detected: 3	Expected: 1

- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: Umacron	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 3	Expected: 1

- Glyph name: Uring	Contours detected: 4	Expected: 3

- Glyph name: Utilde	Contours detected: 3	Expected: 2

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: W	Contours detected: 3	Expected: 1 or 2

- Glyph name: Wacute	Contours detected: 4	Expected: 2

- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

- Glyph name: Wgrave	Contours detected: 4	Expected: 2

- Glyph name: X	Contours detected: 2	Expected: 1

- Glyph name: Y	Contours detected: 2	Expected: 1

- Glyph name: Yacute	Contours detected: 3	Expected: 2

- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

- Glyph name: Ygrave	Contours detected: 3	Expected: 2

- Glyph name: Z	Contours detected: 3	Expected: 1

- Glyph name: Zacute	Contours detected: 4	Expected: 2

- Glyph name: Zcaron	Contours detected: 4	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

- Glyph name: ae	Contours detected: 4	Expected: 3

- Glyph name: aeacute	Contours detected: 5	Expected: 4

- Glyph name: c	Contours detected: 3	Expected: 1

- Glyph name: cacute	Contours detected: 4	Expected: 2

- Glyph name: ccaron	Contours detected: 4	Expected: 2

- Glyph name: ccedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: ccircumflex	Contours detected: 4	Expected: 2

- Glyph name: cdotaccent	Contours detected: 4	Expected: 2

- Glyph name: cent	Contours detected: 5	Expected: 1 or 2

- Glyph name: copyright	Contours detected: 5	Expected: 3

- Glyph name: e	Contours detected: 3	Expected: 2

- Glyph name: eacute	Contours detected: 4	Expected: 3

- Glyph name: ebreve	Contours detected: 4	Expected: 3

- Glyph name: ecaron	Contours detected: 4	Expected: 3

- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

- Glyph name: edieresis	Contours detected: 5	Expected: 4

- Glyph name: edotaccent	Contours detected: 4	Expected: 3

- Glyph name: egrave	Contours detected: 4	Expected: 3

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: emacron	Contours detected: 4	Expected: 3

- Glyph name: eng	Contours detected: 2	Expected: 1

- Glyph name: eogonek	Contours detected: 4	Expected: 2

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: fi	Contours detected: 4	Expected: 3

- Glyph name: five	Contours detected: 4	Expected: 1

- Glyph name: fl	Contours detected: 3	Expected: 2

- Glyph name: germandbls	Contours detected: 2	Expected: 1

- Glyph name: h	Contours detected: 2	Expected: 1

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

- Glyph name: integral	Contours detected: 3	Expected: 1

- Glyph name: k	Contours detected: 3	Expected: 1 or 2

- Glyph name: kgreenlandic	Contours detected: 3	Expected: 1 or 2

- Glyph name: m	Contours detected: 3	Expected: 1

- Glyph name: n	Contours detected: 2	Expected: 1

- Glyph name: nacute	Contours detected: 3	Expected: 2

- Glyph name: ncaron	Contours detected: 3	Expected: 2

- Glyph name: nine	Contours detected: 3	Expected: 1 or 2

- Glyph name: ntilde	Contours detected: 3	Expected: 2

- Glyph name: oe	Contours detected: 4	Expected: 3

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: onehalf	Contours detected: 5	Expected: 3

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: pi	Contours detected: 3	Expected: 1

- Glyph name: product	Contours detected: 3	Expected: 1

- Glyph name: question	Contours detected: 3	Expected: 2

- Glyph name: questiondown	Contours detected: 3	Expected: 2

- Glyph name: r	Contours detected: 2	Expected: 1

- Glyph name: racute	Contours detected: 3	Expected: 2

- Glyph name: rcaron	Contours detected: 3	Expected: 2

- Glyph name: s	Contours detected: 3	Expected: 1

- Glyph name: sacute	Contours detected: 4	Expected: 2

- Glyph name: scaron	Contours detected: 4	Expected: 2

- Glyph name: scircumflex	Contours detected: 4	Expected: 2

- Glyph name: section	Contours detected: 3	Expected: 2

- Glyph name: seven	Contours detected: 2	Expected: 1

- Glyph name: six	Contours detected: 3	Expected: 1 or 2

- Glyph name: sterling	Contours detected: 3	Expected: 1 or 2

- Glyph name: summation	Contours detected: 3	Expected: 1

- Glyph name: t	Contours detected: 2	Expected: 1

- Glyph name: tbar	Contours detected: 3	Expected: 1

- Glyph name: tcaron	Contours detected: 3	Expected: 2

- Glyph name: three	Contours detected: 3	Expected: 1

- Glyph name: threequarters	Contours detected: 5	Expected: 3 or 4

- Glyph name: trademark	Contours detected: 6	Expected: 2

- Glyph name: two	Contours detected: 4	Expected: 1

- Glyph name: u	Contours detected: 2	Expected: 1

- Glyph name: uacute	Contours detected: 3	Expected: 2

- Glyph name: ubreve	Contours detected: 3	Expected: 2

- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

- Glyph name: udieresis	Contours detected: 4	Expected: 3

- Glyph name: ugrave	Contours detected: 3	Expected: 2

- Glyph name: uhorn	Contours detected: 3	Expected: 1

- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: umacron	Contours detected: 3	Expected: 2

- Glyph name: uni00B5	Contours detected: 2	Expected: 1

- Glyph name: uni0122	Contours detected: 4	Expected: 2

- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

- Glyph name: uni0137	Contours detected: 4	Expected: 2 or 3

- Glyph name: uni013B	Contours detected: 3	Expected: 2

- Glyph name: uni013C	Contours detected: 1	Expected: 2

- Glyph name: uni0145	Contours detected: 3	Expected: 2

- Glyph name: uni0146	Contours detected: 3	Expected: 2

- Glyph name: uni0157	Contours detected: 3	Expected: 2

- Glyph name: uni0162	Contours detected: 4	Expected: 1 or 2

- Glyph name: uni0186	Contours detected: 3	Expected: 1

- Glyph name: uni018A	Contours detected: 3	Expected: 2

- Glyph name: uni018E	Contours detected: 3	Expected: 1

- Glyph name: uni018F	Contours detected: 3	Expected: 2

- Glyph name: uni0190	Contours detected: 3	Expected: 1

- Glyph name: uni0198	Contours detected: 3	Expected: 1

- Glyph name: uni0199	Contours detected: 4	Expected: 1

- Glyph name: uni019C	Contours detected: 3	Expected: 1

- Glyph name: uni019D	Contours detected: 2	Expected: 1

- Glyph name: uni01B3	Contours detected: 3	Expected: 1

- Glyph name: uni01B4	Contours detected: 3	Expected: 1

- Glyph name: uni01CD	Contours detected: 2	Expected: 3

- Glyph name: uni01D3	Contours detected: 3	Expected: 2

- Glyph name: uni01D4	Contours detected: 3	Expected: 2

- Glyph name: uni01D7	Contours detected: 5	Expected: 4

- Glyph name: uni01D8	Contours detected: 5	Expected: 4

- Glyph name: uni01DD	Contours detected: 3	Expected: 2

- Glyph name: uni01DE	Contours detected: 4	Expected: 5

- Glyph name: uni01E2	Contours detected: 4	Expected: 3

- Glyph name: uni01E3	Contours detected: 5	Expected: 4

- Glyph name: uni01E8	Contours detected: 4	Expected: 2

- Glyph name: uni01E9	Contours detected: 4	Expected: 2

- Glyph name: uni01F8	Contours detected: 3	Expected: 2

- Glyph name: uni01F9	Contours detected: 3	Expected: 2

- Glyph name: uni0218	Contours detected: 4	Expected: 2

- Glyph name: uni0219	Contours detected: 4	Expected: 2

- Glyph name: uni021A	Contours detected: 4	Expected: 2

- Glyph name: uni0226	Contours detected: 2	Expected: 3

- Glyph name: uni0228	Contours detected: 4	Expected: 1

- Glyph name: uni0229	Contours detected: 4	Expected: 2

- Glyph name: uni0232	Contours detected: 3	Expected: 2

- Glyph name: uni0233	Contours detected: 3	Expected: 2

- Glyph name: uni0259	Contours detected: 3	Expected: 2

- Glyph name: uni0272	Contours detected: 2	Expected: 1

- Glyph name: uni0394	Contours detected: 1	Expected: 2

- Glyph name: uni03A9	Contours detected: 2	Expected: 1

- Glyph name: uni1E02	Contours detected: 3	Expected: 4

- Glyph name: uni1E14	Contours detected: 5	Expected: 3

- Glyph name: uni1E15	Contours detected: 5	Expected: 4

- Glyph name: uni1E1E	Contours detected: 3	Expected: 2

- Glyph name: uni1E20	Contours detected: 4	Expected: 2

- Glyph name: uni1E25	Contours detected: 3	Expected: 2

- Glyph name: uni1E36	Contours detected: 3	Expected: 2

- Glyph name: uni1E3E	Contours detected: 4	Expected: 2

- Glyph name: uni1E3F	Contours detected: 4	Expected: 2

- Glyph name: uni1E40	Contours detected: 4	Expected: 2

- Glyph name: uni1E41	Contours detected: 4	Expected: 2

- Glyph name: uni1E42	Contours detected: 4	Expected: 2

- Glyph name: uni1E43	Contours detected: 4	Expected: 2

- Glyph name: uni1E44	Contours detected: 3	Expected: 2

- Glyph name: uni1E45	Contours detected: 3	Expected: 2

- Glyph name: uni1E46	Contours detected: 3	Expected: 2

- Glyph name: uni1E47	Contours detected: 3	Expected: 2

- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

- Glyph name: uni1E60	Contours detected: 4	Expected: 2

- Glyph name: uni1E61	Contours detected: 4	Expected: 2

- Glyph name: uni1E62	Contours detected: 4	Expected: 2

- Glyph name: uni1E63	Contours detected: 4	Expected: 2

- Glyph name: uni1E6A	Contours detected: 4	Expected: 2

- Glyph name: uni1E6B	Contours detected: 3	Expected: 2

- Glyph name: uni1E6C	Contours detected: 4	Expected: 2

- Glyph name: uni1E6D	Contours detected: 3	Expected: 2

- Glyph name: uni1E92	Contours detected: 4	Expected: 2

- Glyph name: uni1E93	Contours detected: 4	Expected: 2

- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

- Glyph name: uni1EA0	Contours detected: 2	Expected: 3

- Glyph name: uni1EA2	Contours detected: 2	Expected: 3

- Glyph name: uni1EA4	Contours detected: 3	Expected: 4

- Glyph name: uni1EA6	Contours detected: 3	Expected: 4

- Glyph name: uni1EA8	Contours detected: 3	Expected: 4

- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

- Glyph name: uni1EAC	Contours detected: 3	Expected: 4

- Glyph name: uni1EAE	Contours detected: 3	Expected: 4

- Glyph name: uni1EB0	Contours detected: 3	Expected: 4

- Glyph name: uni1EB2	Contours detected: 3	Expected: 4

- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

- Glyph name: uni1EB6	Contours detected: 3	Expected: 4

- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

- Glyph name: uni1EBA	Contours detected: 4	Expected: 2

- Glyph name: uni1EBB	Contours detected: 4	Expected: 3

- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

- Glyph name: uni1EBE	Contours detected: 5	Expected: 3

- Glyph name: uni1EBF	Contours detected: 5	Expected: 4

- Glyph name: uni1EC0	Contours detected: 5	Expected: 3

- Glyph name: uni1EC1	Contours detected: 5	Expected: 4

- Glyph name: uni1EC2	Contours detected: 5	Expected: 3

- Glyph name: uni1EC3	Contours detected: 5	Expected: 4

- Glyph name: uni1EC4	Contours detected: 5	Expected: 3

- Glyph name: uni1EC5	Contours detected: 5	Expected: 4

- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

- Glyph name: uni1EC7	Contours detected: 5	Expected: 4

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

- Glyph name: uni1EE6	Contours detected: 3	Expected: 2

- Glyph name: uni1EE7	Contours detected: 3	Expected: 2

- Glyph name: uni1EE8	Contours detected: 4	Expected: 2

- Glyph name: uni1EE9	Contours detected: 4	Expected: 2

- Glyph name: uni1EEA	Contours detected: 4	Expected: 2

- Glyph name: uni1EEB	Contours detected: 4	Expected: 2

- Glyph name: uni1EEC	Contours detected: 4	Expected: 2

- Glyph name: uni1EED	Contours detected: 4	Expected: 2

- Glyph name: uni1EEE	Contours detected: 4	Expected: 2

- Glyph name: uni1EEF	Contours detected: 4	Expected: 2

- Glyph name: uni1EF0	Contours detected: 4	Expected: 2

- Glyph name: uni1EF1	Contours detected: 4	Expected: 2

- Glyph name: uni1EF4	Contours detected: 3	Expected: 2

- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

- Glyph name: uni1EF6	Contours detected: 3	Expected: 2

- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

- Glyph name: uni2206	Contours detected: 1	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uring	Contours detected: 4	Expected: 3

- Glyph name: utilde	Contours detected: 3	Expected: 2

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 3	Expected: 1

- Glyph name: wacute	Contours detected: 4	Expected: 2

- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

- Glyph name: wdieresis	Contours detected: 5	Expected: 3

- Glyph name: wgrave	Contours detected: 4	Expected: 2

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: yacute	Contours detected: 3	Expected: 2

- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: ydieresis	Contours detected: 4	Expected: 3

- Glyph name: ygrave	Contours detected: 3	Expected: 2

- Glyph name: z	Contours detected: 3	Expected: 1

- Glyph name: zacute	Contours detected: 4	Expected: 2

- Glyph name: zcaron	Contours detected: 4	Expected: 2

- Glyph name: zdotaccent	Contours detected: 4	Expected: 2
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1538 among a set of 8 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1358:
greater, less</p>
<p>Width = 1707:
logicalnot</p>
<p>Width = 1102:
approxequal</p>
<p>Width = 1018:
notequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni03020300

- uni03020301

- uni03020303

- uni03060300

- uni03060301

- uni03060303
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, canadian-aboriginal, tai-le, todhri, math, duployan, hebrew, old-permic, tifinagh, malayalam, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: math, greek, elbasan</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, greek, elbasan</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: phags-pa, yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to aogonek when shaping the text 'ą́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to aogonek when shaping the text 'ą̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uogonek when shaping the text 'ų́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uogonek when shaping the text 'ų̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɵ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɵ</td>
<td align="left">ig_Latn (Igbo)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: j̉ j̛̉ j̣̉ j̦̉ j̧̉ j̨̉ į̉ į̛̉ į̣̉ į̦̉ į̧̉ į̨̉ ị̉ ị̛̉ ị̣̉ ị̦̉ ị̧̉</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* Eng (U+014A): L&lt;&lt;831.0,-538.0&gt;--&lt;829.0,0.0&gt;&gt; -&gt; L&lt;&lt;829.0,0.0&gt;--&lt;829.0,1361.0&gt;&gt;

* Eng.loclNSM: L&lt;&lt;765.0,-538.0&gt;--&lt;829.0,0.0&gt;&gt; -&gt; L&lt;&lt;829.0,0.0&gt;--&lt;996.0,1361.0&gt;&gt;

* ampersand (U+0026): L&lt;&lt;872.0,401.0&gt;--&lt;905.0,680.0&gt;&gt; -&gt; L&lt;&lt;905.0,680.0&gt;--&lt;989.0,1361.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;1051.0,1598.0&gt;--&lt;1122.0,1598.0&gt;&gt; -&gt; L&lt;&lt;1122.0,1598.0&gt;--&lt;1178.0,1595.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;1122.0,1598.0&gt;--&lt;1178.0,1595.0&gt;&gt; -&gt; L&lt;&lt;1178.0,1595.0&gt;--&lt;1219.0,1593.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;981.0,-343.0&gt;--&lt;938.0,-345.0&gt;&gt; -&gt; L&lt;&lt;938.0,-345.0&gt;--&lt;891.0,-347.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;229.0,-348.0&gt;--&lt;172.0,-345.0&gt;&gt; -&gt; L&lt;&lt;172.0,-345.0&gt;--&lt;129.0,-343.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;301.0,-349.0&gt;--&lt;229.0,-348.0&gt;&gt; -&gt; L&lt;&lt;229.0,-348.0&gt;--&lt;172.0,-345.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;367.0,1593.0&gt;--&lt;454.0,1597.0&gt;&gt; -&gt; L&lt;&lt;454.0,1597.0&gt;--&lt;537.0,1598.0&gt;&gt;

* oe (U+0153): L&lt;&lt;1198.0,953.0&gt;--&lt;1212.0,960.0&gt;&gt; -&gt; L&lt;&lt;1212.0,960.0&gt;--&lt;1244.0,975.0&gt;&gt;

* s (U+0073): L&lt;&lt;227.0,636.0&gt;--&lt;225.0,662.0&gt;&gt; -&gt; L&lt;&lt;225.0,662.0&gt;--&lt;225.0,690.0&gt;&gt;

* sacute (U+015B): L&lt;&lt;227.0,636.0&gt;--&lt;225.0,662.0&gt;&gt; -&gt; L&lt;&lt;225.0,662.0&gt;--&lt;225.0,690.0&gt;&gt;

* scaron (U+0161): L&lt;&lt;227.0,636.0&gt;--&lt;225.0,662.0&gt;&gt; -&gt; L&lt;&lt;225.0,662.0&gt;--&lt;225.0,690.0&gt;&gt;

* scedilla (U+015F): L&lt;&lt;227.0,636.0&gt;--&lt;225.0,662.0&gt;&gt; -&gt; L&lt;&lt;225.0,662.0&gt;--&lt;225.0,690.0&gt;&gt;

* scircumflex (U+015D): L&lt;&lt;227.0,636.0&gt;--&lt;225.0,662.0&gt;&gt; -&gt; L&lt;&lt;225.0,662.0&gt;--&lt;225.0,690.0&gt;&gt;

* uni0219 (U+0219): L&lt;&lt;227.0,636.0&gt;--&lt;225.0,662.0&gt;&gt; -&gt; L&lt;&lt;225.0,662.0&gt;--&lt;225.0,690.0&gt;&gt;

* uni03020303: L&lt;&lt;1246.0,1961.0&gt;--&lt;1073.0,1766.0&gt;&gt; -&gt; L&lt;&lt;1073.0,1766.0&gt;--&lt;1057.0,1750.0&gt;&gt;

* uni03020303: L&lt;&lt;399.0,1798.0&gt;--&lt;573.0,1993.0&gt;&gt; -&gt; L&lt;&lt;573.0,1993.0&gt;--&lt;588.0,2009.0&gt;&gt;

* uni03060303: L&lt;&lt;1126.0,1961.0&gt;--&lt;953.0,1766.0&gt;&gt; -&gt; L&lt;&lt;953.0,1766.0&gt;--&lt;937.0,1750.0&gt;&gt;

* uni03060303: L&lt;&lt;279.0,1798.0&gt;--&lt;453.0,1993.0&gt;&gt; -&gt; L&lt;&lt;453.0,1993.0&gt;--&lt;468.0,2009.0&gt;&gt;

* uni1E61 (U+1E61): L&lt;&lt;227.0,636.0&gt;--&lt;225.0,662.0&gt;&gt; -&gt; L&lt;&lt;225.0,662.0&gt;--&lt;225.0,690.0&gt;&gt;

* uni1E63 (U+1E63): L&lt;&lt;227.0,636.0&gt;--&lt;225.0,662.0&gt;&gt; -&gt; L&lt;&lt;225.0,662.0&gt;--&lt;225.0,690.0&gt;&gt;

* uni1E93 (U+1E93): L&lt;&lt;125.0,0.0&gt;--&lt;139.0,100.0&gt;&gt; -&gt; L&lt;&lt;139.0,100.0&gt;--&lt;159.0,261.0&gt;&gt;

* uni1E93 (U+1E93): L&lt;&lt;1340.0,1020.0&gt;--&lt;1325.0,901.0&gt;&gt; -&gt; L&lt;&lt;1325.0,901.0&gt;--&lt;1308.0,765.0&gt;&gt;

* z (U+007A): L&lt;&lt;125.0,0.0&gt;--&lt;139.0,100.0&gt;&gt; -&gt; L&lt;&lt;139.0,100.0&gt;--&lt;159.0,261.0&gt;&gt;

* z (U+007A): L&lt;&lt;1340.0,1020.0&gt;--&lt;1325.0,901.0&gt;&gt; -&gt; L&lt;&lt;1325.0,901.0&gt;--&lt;1308.0,765.0&gt;&gt;

* zacute (U+017A): L&lt;&lt;125.0,0.0&gt;--&lt;139.0,100.0&gt;&gt; -&gt; L&lt;&lt;139.0,100.0&gt;--&lt;159.0,261.0&gt;&gt;

* zacute (U+017A): L&lt;&lt;1340.0,1020.0&gt;--&lt;1325.0,901.0&gt;&gt; -&gt; L&lt;&lt;1325.0,901.0&gt;--&lt;1308.0,765.0&gt;&gt;

* zcaron (U+017E): L&lt;&lt;125.0,0.0&gt;--&lt;139.0,100.0&gt;&gt; -&gt; L&lt;&lt;139.0,100.0&gt;--&lt;159.0,261.0&gt;&gt;

* zcaron (U+017E): L&lt;&lt;1340.0,1020.0&gt;--&lt;1325.0,901.0&gt;&gt; -&gt; L&lt;&lt;1325.0,901.0&gt;--&lt;1308.0,765.0&gt;&gt;

* zdotaccent (U+017C): L&lt;&lt;125.0,0.0&gt;--&lt;139.0,100.0&gt;&gt; -&gt; L&lt;&lt;139.0,100.0&gt;--&lt;159.0,261.0&gt;&gt;

* zdotaccent (U+017C): L&lt;&lt;1340.0,1020.0&gt;--&lt;1325.0,901.0&gt;&gt; -&gt; L&lt;&lt;1325.0,901.0&gt;--&lt;1308.0,765.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* aogonek (U+0105): B&lt;&lt;969.0,5.0&gt;-&lt;1008.0,32.0&gt;-&lt;1056.0,44.0&gt;&gt;/L&lt;&lt;1056.0,44.0&gt;--&lt;1052.0,44.0&gt;&gt; = 14.036243467926457

* eth (U+00F0): L&lt;&lt;1824.0,1486.0&gt;--&lt;1531.0,1412.0&gt;&gt;/L&lt;&lt;1531.0,1412.0&gt;--&lt;1548.0,1412.0&gt;&gt; = 14.17419451639709

* eth (U+00F0): L&lt;&lt;698.0,1395.0&gt;--&lt;1049.0,1484.0&gt;&gt;/L&lt;&lt;1049.0,1484.0&gt;--&lt;1030.0,1484.0&gt;&gt; = 14.228124128721467

* registered (U+00AE): B&lt;&lt;1610.5,582.0&gt;-&lt;1531.0,548.0&gt;-&lt;1431.0,536.0&gt;&gt;/B&lt;&lt;1431.0,536.0&gt;-&lt;1509.0,534.0&gt;-&lt;1575.0,517.0&gt;&gt; = 8.311574127016716

* section (U+00A7): B&lt;&lt;1438.0,378.0&gt;-&lt;1378.0,353.0&gt;-&lt;1302.0,344.0&gt;&gt;/L&lt;&lt;1302.0,344.0&gt;--&lt;1318.0,344.0&gt;&gt; = 6.753574035530968

* section (U+00A7): B&lt;&lt;600.0,982.0&gt;-&lt;660.0,1008.0&gt;-&lt;736.0,1017.0&gt;&gt;/L&lt;&lt;736.0,1017.0&gt;--&lt;720.0,1017.0&gt;&gt; = 6.753574035530968
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* A (U+0041) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Aacute (U+00C1) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Abreve (U+0102) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EAE (U+1EAE) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EB6 (U+1EB6) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EB0 (U+1EB0) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EB2 (U+1EB2) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EB4 (U+1EB4) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni01CD (U+01CD) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Acircumflex (U+00C2) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EA4 (U+1EA4) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EAC (U+1EAC) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EA6 (U+1EA6) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EA8 (U+1EA8) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EAA (U+1EAA) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Adieresis (U+00C4) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni01DE (U+01DE) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni0226 (U+0226) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EA0 (U+1EA0) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Agrave (U+00C0) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni1EA2 (U+1EA2) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Amacron (U+0100) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Aogonek (U+0104) contains a short segment L&lt;&lt;1124.0,0.0&gt;--&lt;1124.0,-28.0&gt;&gt;

* Aring (U+00C5) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Atilde (U+00C3) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* AE (U+00C6) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* AEacute (U+01FC) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* uni01E2 (U+01E2) contains a short segment L&lt;&lt;742.0,462.0&gt;--&lt;737.0,424.0&gt;&gt;

* Lslash (U+0141) contains a short segment L&lt;&lt;150.0,679.0&gt;--&lt;134.0,679.0&gt;&gt;

* Lslash (U+0141) contains a short segment L&lt;&lt;656.0,670.0&gt;--&lt;672.0,670.0&gt;&gt;

* Oslash (U+00D8) contains a short segment L&lt;&lt;1330.0,1187.0&gt;--&lt;1331.0,1187.0&gt;&gt;

* Oslash (U+00D8) contains a short segment L&lt;&lt;214.0,182.0&gt;--&lt;212.0,182.0&gt;&gt;

* S (U+0053) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* Sacute (U+015A) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* Scaron (U+0160) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* Scedilla (U+015E) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* Scircumflex (U+015C) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* uni0218 (U+0218) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* uni1E60 (U+1E60) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* uni1E62 (U+1E62) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* eth (U+00F0) contains a short segment L&lt;&lt;1531.0,1412.0&gt;--&lt;1548.0,1412.0&gt;&gt;

* eth (U+00F0) contains a short segment L&lt;&lt;1049.0,1484.0&gt;--&lt;1030.0,1484.0&gt;&gt;

* iogonek (U+012F) contains a short segment L&lt;&lt;449.0,0.0&gt;--&lt;449.0,-28.0&gt;&gt;

* lslash (U+0142) contains a short segment L&lt;&lt;250.0,704.0&gt;--&lt;240.0,704.0&gt;&gt;

* lslash (U+0142) contains a short segment L&lt;&lt;768.0,826.0&gt;--&lt;778.0,826.0&gt;&gt;

* oslash (U+00F8) contains a short segment L&lt;&lt;1431.0,830.0&gt;--&lt;1434.0,830.0&gt;&gt;

* oslash (U+00F8) contains a short segment L&lt;&lt;227.0,188.0&gt;--&lt;224.0,188.0&gt;&gt;

* oe (U+0153) contains a short segment L&lt;&lt;1198.0,953.0&gt;--&lt;1212.0,960.0&gt;&gt;

* s (U+0073) contains a short segment L&lt;&lt;234.0,636.0&gt;--&lt;227.0,636.0&gt;&gt;

* sacute (U+015B) contains a short segment L&lt;&lt;234.0,636.0&gt;--&lt;227.0,636.0&gt;&gt;

* scaron (U+0161) contains a short segment L&lt;&lt;234.0,636.0&gt;--&lt;227.0,636.0&gt;&gt;

* scedilla (U+015F) contains a short segment L&lt;&lt;234.0,636.0&gt;--&lt;227.0,636.0&gt;&gt;

* scircumflex (U+015D) contains a short segment L&lt;&lt;234.0,636.0&gt;--&lt;227.0,636.0&gt;&gt;

* uni0219 (U+0219) contains a short segment L&lt;&lt;234.0,636.0&gt;--&lt;227.0,636.0&gt;&gt;

* uni1E61 (U+1E61) contains a short segment L&lt;&lt;234.0,636.0&gt;--&lt;227.0,636.0&gt;&gt;

* uni1E63 (U+1E63) contains a short segment L&lt;&lt;234.0,636.0&gt;--&lt;227.0,636.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;1149.0,0.0&gt;--&lt;1149.0,-28.0&gt;&gt;

* x (U+0078) contains a short segment B&lt;&lt;1264.0,394.0&gt;-&lt;1268.0,386.0&gt;-&lt;1274.0,377.0&gt;&gt;

* x (U+0078) contains a short segment B&lt;&lt;1274.0,377.0&gt;-&lt;1280.0,368.0&gt;-&lt;1290.0,352.0&gt;&gt;

* uni1E8B (U+1E8B) contains a short segment B&lt;&lt;1264.0,394.0&gt;-&lt;1268.0,386.0&gt;-&lt;1274.0,377.0&gt;&gt;

* uni1E8B (U+1E8B) contains a short segment B&lt;&lt;1274.0,377.0&gt;-&lt;1280.0,368.0&gt;-&lt;1290.0,352.0&gt;&gt;

* uni0394 (U+0394) contains a short segment L&lt;&lt;1044.0,1529.0&gt;--&lt;1045.0,1530.0&gt;&gt;

* braceleft (U+007B) contains a short segment B&lt;&lt;530.0,1084.0&gt;-&lt;529.0,1104.0&gt;-&lt;529.0,1121.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;1033.0,157.0&gt;-&lt;1024.0,187.0&gt;-&lt;1023.0,221.5&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;1023.0,221.5&gt;-&lt;1022.0,256.0&gt;-&lt;1026.0,293.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;388.0,680.0&gt;--&lt;382.0,680.0&gt;&gt;

* dollar (U+0024) contains a short segment L&lt;&lt;393.0,959.0&gt;--&lt;387.0,959.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;422.0,584.0&gt;-&lt;421.0,599.0&gt;-&lt;421.0,614.0&gt;&gt;

* sterling (U+00A3) contains a short segment B&lt;&lt;186.0,0.0&gt;-&lt;160.0,0.0&gt;-&lt;165.5,10.5&gt;&gt;

* integral (U+222B) contains a short segment L&lt;&lt;852.0,142.0&gt;--&lt;855.0,150.0&gt;&gt;

* uni2206 (U+2206) contains a short segment L&lt;&lt;1044.0,1529.0&gt;--&lt;1045.0,1530.0&gt;&gt;

* radical (U+221A) contains a short segment L&lt;&lt;639.0,-337.0&gt;--&lt;639.0,-340.0&gt;&gt;

* radical (U+221A) contains a short segment L&lt;&lt;639.0,-340.0&gt;--&lt;638.0,-339.0&gt;&gt;

* radical (U+221A) contains a short segment L&lt;&lt;638.0,-339.0&gt;--&lt;638.0,-337.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;756.0,1527.0&gt;--&lt;757.0,1529.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;757.0,1529.0&gt;--&lt;758.0,1530.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;758.0,1530.0&gt;--&lt;759.0,1527.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;758.0,-337.0&gt;--&lt;758.0,-340.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;758.0,-340.0&gt;--&lt;757.0,-339.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>
</div>
</details>

<details><summary>[16] Plaster-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-license-OFL-copyright">googlefonts/license/OFL_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Plaster Regular: OS/2 sTypoAscender is 2054 when it should be 2000</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Plaster Regular: hhea Ascender is 2054 when it should be 2000</p>
 [code: bad-hhea-ascender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#alt-caron">alt_caron</a></summary>
    <div>









* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: two	Contours detected: 4	Expected: 1

- Glyph name: three	Contours detected: 3	Expected: 1

- Glyph name: five	Contours detected: 4	Expected: 1

- Glyph name: six	Contours detected: 3	Expected: 1 or 2

- Glyph name: seven	Contours detected: 2	Expected: 1

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: nine	Contours detected: 3	Expected: 1 or 2

- Glyph name: question	Contours detected: 3	Expected: 2

- Glyph name: A	Contours detected: 1	Expected: 2

- Glyph name: C	Contours detected: 3	Expected: 1

- Glyph name: E	Contours detected: 3	Expected: 1

- Glyph name: F	Contours detected: 2	Expected: 1

- Glyph name: G	Contours detected: 3	Expected: 1

- Glyph name: J	Contours detected: 2	Expected: 1

- Glyph name: K	Contours detected: 3	Expected: 1 or 2

- Glyph name: L	Contours detected: 2	Expected: 1

- Glyph name: M	Contours detected: 3	Expected: 1

- Glyph name: N	Contours detected: 2	Expected: 1

- Glyph name: Q	Contours detected: 3	Expected: 2

- Glyph name: S	Contours detected: 3	Expected: 1

- Glyph name: T	Contours detected: 3	Expected: 1

- Glyph name: U	Contours detected: 2	Expected: 1

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: W	Contours detected: 3	Expected: 1 or 2

- Glyph name: X	Contours detected: 2	Expected: 1

- Glyph name: Y	Contours detected: 2	Expected: 1

- Glyph name: Z	Contours detected: 3	Expected: 1

- Glyph name: c	Contours detected: 3	Expected: 1

- Glyph name: e	Contours detected: 3	Expected: 2

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: h	Contours detected: 2	Expected: 1

- Glyph name: k	Contours detected: 3	Expected: 1 or 2

- Glyph name: m	Contours detected: 3	Expected: 1

- Glyph name: n	Contours detected: 2	Expected: 1

- Glyph name: r	Contours detected: 2	Expected: 1

- Glyph name: s	Contours detected: 3	Expected: 1

- Glyph name: t	Contours detected: 2	Expected: 1

- Glyph name: u	Contours detected: 2	Expected: 1

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 3	Expected: 1

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: z	Contours detected: 3	Expected: 1

- Glyph name: cent	Contours detected: 5	Expected: 1 or 2

- Glyph name: sterling	Contours detected: 3	Expected: 1 or 2

- Glyph name: section	Contours detected: 3	Expected: 2

- Glyph name: copyright	Contours detected: 5	Expected: 3

- Glyph name: uni00B2	Contours detected: 4	Expected: 1

- Glyph name: uni00B3	Contours detected: 3	Expected: 1

- Glyph name: uni00B5	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 5	Expected: 3

- Glyph name: threequarters	Contours detected: 5	Expected: 3 or 4

- Glyph name: questiondown	Contours detected: 3	Expected: 2

- Glyph name: Agrave	Contours detected: 2	Expected: 3

- Glyph name: Aacute	Contours detected: 2	Expected: 3

- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

- Glyph name: Atilde	Contours detected: 2	Expected: 3

- Glyph name: Adieresis	Contours detected: 3	Expected: 4

- Glyph name: AE	Contours detected: 3	Expected: 2

- Glyph name: Ccedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: Egrave	Contours detected: 4	Expected: 2

- Glyph name: Eacute	Contours detected: 4	Expected: 2

- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

- Glyph name: Edieresis	Contours detected: 5	Expected: 3

- Glyph name: Ntilde	Contours detected: 3	Expected: 2

- Glyph name: Ugrave	Contours detected: 3	Expected: 2

- Glyph name: Uacute	Contours detected: 3	Expected: 2

- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

- Glyph name: Udieresis	Contours detected: 4	Expected: 3

- Glyph name: Yacute	Contours detected: 3	Expected: 2

- Glyph name: germandbls	Contours detected: 2	Expected: 1

- Glyph name: ae	Contours detected: 4	Expected: 3

- Glyph name: ccedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: egrave	Contours detected: 4	Expected: 3

- Glyph name: eacute	Contours detected: 4	Expected: 3

- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

- Glyph name: edieresis	Contours detected: 5	Expected: 4

- Glyph name: ntilde	Contours detected: 3	Expected: 2

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: ugrave	Contours detected: 3	Expected: 2

- Glyph name: uacute	Contours detected: 3	Expected: 2

- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

- Glyph name: udieresis	Contours detected: 4	Expected: 3

- Glyph name: yacute	Contours detected: 3	Expected: 2

- Glyph name: ydieresis	Contours detected: 4	Expected: 3

- Glyph name: Amacron	Contours detected: 2	Expected: 3

- Glyph name: Abreve	Contours detected: 2	Expected: 3

- Glyph name: Aogonek	Contours detected: 1	Expected: 2 or 3

- Glyph name: Cacute	Contours detected: 4	Expected: 2

- Glyph name: cacute	Contours detected: 4	Expected: 2

- Glyph name: Ccircumflex	Contours detected: 4	Expected: 2

- Glyph name: ccircumflex	Contours detected: 4	Expected: 2

- Glyph name: Cdotaccent	Contours detected: 4	Expected: 2

- Glyph name: cdotaccent	Contours detected: 4	Expected: 2

- Glyph name: Ccaron	Contours detected: 4	Expected: 2

- Glyph name: ccaron	Contours detected: 4	Expected: 2

- Glyph name: Emacron	Contours detected: 4	Expected: 2

- Glyph name: emacron	Contours detected: 4	Expected: 3

- Glyph name: Ebreve	Contours detected: 4	Expected: 2

- Glyph name: ebreve	Contours detected: 4	Expected: 3

- Glyph name: Edotaccent	Contours detected: 4	Expected: 2

- Glyph name: edotaccent	Contours detected: 4	Expected: 3

- Glyph name: Eogonek	Contours detected: 4	Expected: 1 or 2

- Glyph name: eogonek	Contours detected: 4	Expected: 2

- Glyph name: Ecaron	Contours detected: 4	Expected: 2

- Glyph name: ecaron	Contours detected: 4	Expected: 3

- Glyph name: Gcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Gbreve	Contours detected: 4	Expected: 2

- Glyph name: Gdotaccent	Contours detected: 4	Expected: 2

- Glyph name: uni0122	Contours detected: 4	Expected: 2

- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

- Glyph name: uni0137	Contours detected: 4	Expected: 2 or 3

- Glyph name: kgreenlandic	Contours detected: 3	Expected: 1 or 2

- Glyph name: Lacute	Contours detected: 3	Expected: 2

- Glyph name: uni013B	Contours detected: 3	Expected: 2

- Glyph name: uni013C	Contours detected: 1	Expected: 2

- Glyph name: Lcaron	Contours detected: 3	Expected: 2

- Glyph name: Ldot	Contours detected: 3	Expected: 2

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: Nacute	Contours detected: 3	Expected: 2

- Glyph name: nacute	Contours detected: 3	Expected: 2

- Glyph name: uni0145	Contours detected: 3	Expected: 2

- Glyph name: uni0146	Contours detected: 3	Expected: 2

- Glyph name: Ncaron	Contours detected: 3	Expected: 2

- Glyph name: ncaron	Contours detected: 3	Expected: 2

- Glyph name: Eng	Contours detected: 2	Expected: 1

- Glyph name: eng	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 4	Expected: 2

- Glyph name: oe	Contours detected: 4	Expected: 3

- Glyph name: racute	Contours detected: 3	Expected: 2

- Glyph name: uni0157	Contours detected: 3	Expected: 2

- Glyph name: rcaron	Contours detected: 3	Expected: 2

- Glyph name: Sacute	Contours detected: 4	Expected: 2

- Glyph name: sacute	Contours detected: 4	Expected: 2

- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

- Glyph name: scircumflex	Contours detected: 4	Expected: 2

- Glyph name: Scedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: scedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: Scaron	Contours detected: 4	Expected: 2

- Glyph name: scaron	Contours detected: 4	Expected: 2

- Glyph name: uni0162	Contours detected: 4	Expected: 1 or 2

- Glyph name: Tcaron	Contours detected: 4	Expected: 2

- Glyph name: tcaron	Contours detected: 3	Expected: 2

- Glyph name: Tbar	Contours detected: 3	Expected: 1

- Glyph name: tbar	Contours detected: 3	Expected: 1

- Glyph name: Utilde	Contours detected: 3	Expected: 2

- Glyph name: utilde	Contours detected: 3	Expected: 2

- Glyph name: Umacron	Contours detected: 3	Expected: 2

- Glyph name: umacron	Contours detected: 3	Expected: 2

- Glyph name: Ubreve	Contours detected: 3	Expected: 2

- Glyph name: ubreve	Contours detected: 3	Expected: 2

- Glyph name: Uring	Contours detected: 4	Expected: 3

- Glyph name: uring	Contours detected: 4	Expected: 3

- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: Uogonek	Contours detected: 3	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

- Glyph name: Zacute	Contours detected: 4	Expected: 2

- Glyph name: zacute	Contours detected: 4	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

- Glyph name: zdotaccent	Contours detected: 4	Expected: 2

- Glyph name: Zcaron	Contours detected: 4	Expected: 2

- Glyph name: zcaron	Contours detected: 4	Expected: 2

- Glyph name: uni0186	Contours detected: 3	Expected: 1

- Glyph name: uni018A	Contours detected: 3	Expected: 2

- Glyph name: uni018E	Contours detected: 3	Expected: 1

- Glyph name: uni018F	Contours detected: 3	Expected: 2

- Glyph name: uni0190	Contours detected: 3	Expected: 1

- Glyph name: florin	Contours detected: 3	Expected: 1

- Glyph name: uni0198	Contours detected: 3	Expected: 1

- Glyph name: uni0199	Contours detected: 4	Expected: 1

- Glyph name: uni019C	Contours detected: 3	Expected: 1

- Glyph name: uni019D	Contours detected: 2	Expected: 1

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: Uhorn	Contours detected: 3	Expected: 1

- Glyph name: uhorn	Contours detected: 3	Expected: 1

- Glyph name: uni01B3	Contours detected: 3	Expected: 1

- Glyph name: uni01B4	Contours detected: 3	Expected: 1

- Glyph name: uni01CD	Contours detected: 2	Expected: 3

- Glyph name: uni01D3	Contours detected: 3	Expected: 2

- Glyph name: uni01D4	Contours detected: 3	Expected: 2

- Glyph name: uni01D7	Contours detected: 5	Expected: 4

- Glyph name: uni01D8	Contours detected: 5	Expected: 4

- Glyph name: uni01DD	Contours detected: 3	Expected: 2

- Glyph name: uni01DE	Contours detected: 4	Expected: 5

- Glyph name: uni01E2	Contours detected: 4	Expected: 3

- Glyph name: uni01E3	Contours detected: 5	Expected: 4

- Glyph name: Gcaron	Contours detected: 4	Expected: 2

- Glyph name: uni01E8	Contours detected: 4	Expected: 2

- Glyph name: uni01E9	Contours detected: 4	Expected: 2

- Glyph name: uni01F8	Contours detected: 3	Expected: 2

- Glyph name: uni01F9	Contours detected: 3	Expected: 2

- Glyph name: AEacute	Contours detected: 4	Expected: 3

- Glyph name: aeacute	Contours detected: 5	Expected: 4

- Glyph name: uni0218	Contours detected: 4	Expected: 2

- Glyph name: uni0219	Contours detected: 4	Expected: 2

- Glyph name: uni021A	Contours detected: 4	Expected: 2

- Glyph name: uni0226	Contours detected: 2	Expected: 3

- Glyph name: uni0228	Contours detected: 4	Expected: 1

- Glyph name: uni0229	Contours detected: 4	Expected: 2

- Glyph name: uni0232	Contours detected: 3	Expected: 2

- Glyph name: uni0233	Contours detected: 3	Expected: 2

- Glyph name: uni0259	Contours detected: 3	Expected: 2

- Glyph name: uni0272	Contours detected: 2	Expected: 1

- Glyph name: uni0394	Contours detected: 1	Expected: 2

- Glyph name: uni03A9	Contours detected: 2	Expected: 1

- Glyph name: pi	Contours detected: 3	Expected: 1

- Glyph name: uni1E02	Contours detected: 3	Expected: 4

- Glyph name: uni1E14	Contours detected: 5	Expected: 3

- Glyph name: uni1E15	Contours detected: 5	Expected: 4

- Glyph name: uni1E1E	Contours detected: 3	Expected: 2

- Glyph name: uni1E1F	Contours detected: 3	Expected: 2

- Glyph name: uni1E20	Contours detected: 4	Expected: 2

- Glyph name: uni1E25	Contours detected: 3	Expected: 2

- Glyph name: uni1E36	Contours detected: 3	Expected: 2

- Glyph name: uni1E3E	Contours detected: 4	Expected: 2

- Glyph name: uni1E3F	Contours detected: 4	Expected: 2

- Glyph name: uni1E40	Contours detected: 4	Expected: 2

- Glyph name: uni1E41	Contours detected: 4	Expected: 2

- Glyph name: uni1E42	Contours detected: 4	Expected: 2

- Glyph name: uni1E43	Contours detected: 4	Expected: 2

- Glyph name: uni1E44	Contours detected: 3	Expected: 2

- Glyph name: uni1E45	Contours detected: 3	Expected: 2

- Glyph name: uni1E46	Contours detected: 3	Expected: 2

- Glyph name: uni1E47	Contours detected: 3	Expected: 2

- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

- Glyph name: uni1E60	Contours detected: 4	Expected: 2

- Glyph name: uni1E61	Contours detected: 4	Expected: 2

- Glyph name: uni1E62	Contours detected: 4	Expected: 2

- Glyph name: uni1E63	Contours detected: 4	Expected: 2

- Glyph name: uni1E6A	Contours detected: 4	Expected: 2

- Glyph name: uni1E6B	Contours detected: 3	Expected: 2

- Glyph name: uni1E6C	Contours detected: 4	Expected: 2

- Glyph name: uni1E6D	Contours detected: 3	Expected: 2

- Glyph name: Wgrave	Contours detected: 4	Expected: 2

- Glyph name: wgrave	Contours detected: 4	Expected: 2

- Glyph name: Wacute	Contours detected: 4	Expected: 2

- Glyph name: wacute	Contours detected: 4	Expected: 2

- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

- Glyph name: wdieresis	Contours detected: 5	Expected: 3

- Glyph name: uni1E92	Contours detected: 4	Expected: 2

- Glyph name: uni1E93	Contours detected: 4	Expected: 2

- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

- Glyph name: uni1EA0	Contours detected: 2	Expected: 3

- Glyph name: uni1EA2	Contours detected: 2	Expected: 3

- Glyph name: uni1EA4	Contours detected: 3	Expected: 4

- Glyph name: uni1EA6	Contours detected: 3	Expected: 4

- Glyph name: uni1EA8	Contours detected: 3	Expected: 4

- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

- Glyph name: uni1EAC	Contours detected: 3	Expected: 4

- Glyph name: uni1EAE	Contours detected: 3	Expected: 4

- Glyph name: uni1EB0	Contours detected: 3	Expected: 4

- Glyph name: uni1EB2	Contours detected: 3	Expected: 4

- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

- Glyph name: uni1EB6	Contours detected: 3	Expected: 4

- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

- Glyph name: uni1EBA	Contours detected: 4	Expected: 2

- Glyph name: uni1EBB	Contours detected: 4	Expected: 3

- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

- Glyph name: uni1EBE	Contours detected: 5	Expected: 3

- Glyph name: uni1EBF	Contours detected: 5	Expected: 4

- Glyph name: uni1EC0	Contours detected: 5	Expected: 3

- Glyph name: uni1EC1	Contours detected: 5	Expected: 4

- Glyph name: uni1EC2	Contours detected: 5	Expected: 3

- Glyph name: uni1EC3	Contours detected: 5	Expected: 4

- Glyph name: uni1EC4	Contours detected: 5	Expected: 3

- Glyph name: uni1EC5	Contours detected: 5	Expected: 4

- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

- Glyph name: uni1EC7	Contours detected: 5	Expected: 4

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

- Glyph name: uni1EE6	Contours detected: 3	Expected: 2

- Glyph name: uni1EE7	Contours detected: 3	Expected: 2

- Glyph name: uni1EE8	Contours detected: 4	Expected: 2

- Glyph name: uni1EE9	Contours detected: 4	Expected: 2

- Glyph name: uni1EEA	Contours detected: 4	Expected: 2

- Glyph name: uni1EEB	Contours detected: 4	Expected: 2

- Glyph name: uni1EEC	Contours detected: 4	Expected: 2

- Glyph name: uni1EED	Contours detected: 4	Expected: 2

- Glyph name: uni1EEE	Contours detected: 4	Expected: 2

- Glyph name: uni1EEF	Contours detected: 4	Expected: 2

- Glyph name: uni1EF0	Contours detected: 4	Expected: 2

- Glyph name: uni1EF1	Contours detected: 4	Expected: 2

- Glyph name: Ygrave	Contours detected: 3	Expected: 2

- Glyph name: ygrave	Contours detected: 3	Expected: 2

- Glyph name: uni1EF4	Contours detected: 3	Expected: 2

- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

- Glyph name: uni1EF6	Contours detected: 3	Expected: 2

- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

- Glyph name: trademark	Contours detected: 6	Expected: 2

- Glyph name: uni2206	Contours detected: 1	Expected: 2

- Glyph name: product	Contours detected: 3	Expected: 1

- Glyph name: summation	Contours detected: 3	Expected: 1

- Glyph name: integral	Contours detected: 3	Expected: 1

- Glyph name: fi	Contours detected: 4	Expected: 1, 2 or 3

- Glyph name: fl	Contours detected: 3	Expected: 1 or 2

- Glyph name: A	Contours detected: 1	Expected: 2

- Glyph name: AE	Contours detected: 3	Expected: 2

- Glyph name: AEacute	Contours detected: 4	Expected: 3

- Glyph name: Aacute	Contours detected: 2	Expected: 3

- Glyph name: Abreve	Contours detected: 2	Expected: 3

- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

- Glyph name: Adieresis	Contours detected: 3	Expected: 4

- Glyph name: Agrave	Contours detected: 2	Expected: 3

- Glyph name: Amacron	Contours detected: 2	Expected: 3

- Glyph name: Aogonek	Contours detected: 1	Expected: 2 or 3

- Glyph name: Atilde	Contours detected: 2	Expected: 3

- Glyph name: C	Contours detected: 3	Expected: 1

- Glyph name: Cacute	Contours detected: 4	Expected: 2

- Glyph name: Ccaron	Contours detected: 4	Expected: 2

- Glyph name: Ccedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: Ccircumflex	Contours detected: 4	Expected: 2

- Glyph name: Cdotaccent	Contours detected: 4	Expected: 2

- Glyph name: E	Contours detected: 3	Expected: 1

- Glyph name: Eacute	Contours detected: 4	Expected: 2

- Glyph name: Ebreve	Contours detected: 4	Expected: 2

- Glyph name: Ecaron	Contours detected: 4	Expected: 2

- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

- Glyph name: Edieresis	Contours detected: 5	Expected: 3

- Glyph name: Edotaccent	Contours detected: 4	Expected: 2

- Glyph name: Egrave	Contours detected: 4	Expected: 2

- Glyph name: Emacron	Contours detected: 4	Expected: 2

- Glyph name: Eng	Contours detected: 2	Expected: 1

- Glyph name: Eogonek	Contours detected: 4	Expected: 1 or 2

- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

- Glyph name: F	Contours detected: 2	Expected: 1

- Glyph name: G	Contours detected: 3	Expected: 1

- Glyph name: Gbreve	Contours detected: 4	Expected: 2

- Glyph name: Gcaron	Contours detected: 4	Expected: 2

- Glyph name: Gcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Gdotaccent	Contours detected: 4	Expected: 2

- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

- Glyph name: J	Contours detected: 2	Expected: 1

- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: K	Contours detected: 3	Expected: 1 or 2

- Glyph name: L	Contours detected: 2	Expected: 1

- Glyph name: Lacute	Contours detected: 3	Expected: 2

- Glyph name: Lcaron	Contours detected: 3	Expected: 2

- Glyph name: Ldot	Contours detected: 3	Expected: 2

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: M	Contours detected: 3	Expected: 1

- Glyph name: N	Contours detected: 2	Expected: 1

- Glyph name: Nacute	Contours detected: 3	Expected: 2

- Glyph name: Ncaron	Contours detected: 3	Expected: 2

- Glyph name: Ntilde	Contours detected: 3	Expected: 2

- Glyph name: OE	Contours detected: 4	Expected: 2

- Glyph name: Q	Contours detected: 3	Expected: 2

- Glyph name: S	Contours detected: 3	Expected: 1

- Glyph name: Sacute	Contours detected: 4	Expected: 2

- Glyph name: Scaron	Contours detected: 4	Expected: 2

- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

- Glyph name: T	Contours detected: 3	Expected: 1

- Glyph name: Tbar	Contours detected: 3	Expected: 1

- Glyph name: Tcaron	Contours detected: 4	Expected: 2

- Glyph name: U	Contours detected: 2	Expected: 1

- Glyph name: Uacute	Contours detected: 3	Expected: 2

- Glyph name: Ubreve	Contours detected: 3	Expected: 2

- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

- Glyph name: Udieresis	Contours detected: 4	Expected: 3

- Glyph name: Ugrave	Contours detected: 3	Expected: 2

- Glyph name: Uhorn	Contours detected: 3	Expected: 1

- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: Umacron	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 3	Expected: 1

- Glyph name: Uring	Contours detected: 4	Expected: 3

- Glyph name: Utilde	Contours detected: 3	Expected: 2

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: W	Contours detected: 3	Expected: 1 or 2

- Glyph name: Wacute	Contours detected: 4	Expected: 2

- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

- Glyph name: Wgrave	Contours detected: 4	Expected: 2

- Glyph name: X	Contours detected: 2	Expected: 1

- Glyph name: Y	Contours detected: 2	Expected: 1

- Glyph name: Yacute	Contours detected: 3	Expected: 2

- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

- Glyph name: Ygrave	Contours detected: 3	Expected: 2

- Glyph name: Z	Contours detected: 3	Expected: 1

- Glyph name: Zacute	Contours detected: 4	Expected: 2

- Glyph name: Zcaron	Contours detected: 4	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

- Glyph name: ae	Contours detected: 4	Expected: 3

- Glyph name: aeacute	Contours detected: 5	Expected: 4

- Glyph name: c	Contours detected: 3	Expected: 1

- Glyph name: cacute	Contours detected: 4	Expected: 2

- Glyph name: ccaron	Contours detected: 4	Expected: 2

- Glyph name: ccedilla	Contours detected: 4	Expected: 1 or 2

- Glyph name: ccircumflex	Contours detected: 4	Expected: 2

- Glyph name: cdotaccent	Contours detected: 4	Expected: 2

- Glyph name: cent	Contours detected: 5	Expected: 1 or 2

- Glyph name: copyright	Contours detected: 5	Expected: 3

- Glyph name: e	Contours detected: 3	Expected: 2

- Glyph name: eacute	Contours detected: 4	Expected: 3

- Glyph name: ebreve	Contours detected: 4	Expected: 3

- Glyph name: ecaron	Contours detected: 4	Expected: 3

- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

- Glyph name: edieresis	Contours detected: 5	Expected: 4

- Glyph name: edotaccent	Contours detected: 4	Expected: 3

- Glyph name: egrave	Contours detected: 4	Expected: 3

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: emacron	Contours detected: 4	Expected: 3

- Glyph name: eng	Contours detected: 2	Expected: 1

- Glyph name: eogonek	Contours detected: 4	Expected: 2

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: fi	Contours detected: 4	Expected: 3

- Glyph name: five	Contours detected: 4	Expected: 1

- Glyph name: fl	Contours detected: 3	Expected: 2

- Glyph name: germandbls	Contours detected: 2	Expected: 1

- Glyph name: h	Contours detected: 2	Expected: 1

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

- Glyph name: integral	Contours detected: 3	Expected: 1

- Glyph name: k	Contours detected: 3	Expected: 1 or 2

- Glyph name: kgreenlandic	Contours detected: 3	Expected: 1 or 2

- Glyph name: m	Contours detected: 3	Expected: 1

- Glyph name: n	Contours detected: 2	Expected: 1

- Glyph name: nacute	Contours detected: 3	Expected: 2

- Glyph name: ncaron	Contours detected: 3	Expected: 2

- Glyph name: nine	Contours detected: 3	Expected: 1 or 2

- Glyph name: ntilde	Contours detected: 3	Expected: 2

- Glyph name: oe	Contours detected: 4	Expected: 3

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: onehalf	Contours detected: 5	Expected: 3

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: pi	Contours detected: 3	Expected: 1

- Glyph name: product	Contours detected: 3	Expected: 1

- Glyph name: question	Contours detected: 3	Expected: 2

- Glyph name: questiondown	Contours detected: 3	Expected: 2

- Glyph name: r	Contours detected: 2	Expected: 1

- Glyph name: racute	Contours detected: 3	Expected: 2

- Glyph name: rcaron	Contours detected: 3	Expected: 2

- Glyph name: s	Contours detected: 3	Expected: 1

- Glyph name: sacute	Contours detected: 4	Expected: 2

- Glyph name: scaron	Contours detected: 4	Expected: 2

- Glyph name: scircumflex	Contours detected: 4	Expected: 2

- Glyph name: section	Contours detected: 3	Expected: 2

- Glyph name: seven	Contours detected: 2	Expected: 1

- Glyph name: six	Contours detected: 3	Expected: 1 or 2

- Glyph name: sterling	Contours detected: 3	Expected: 1 or 2

- Glyph name: summation	Contours detected: 3	Expected: 1

- Glyph name: t	Contours detected: 2	Expected: 1

- Glyph name: tbar	Contours detected: 3	Expected: 1

- Glyph name: tcaron	Contours detected: 3	Expected: 2

- Glyph name: three	Contours detected: 3	Expected: 1

- Glyph name: threequarters	Contours detected: 5	Expected: 3 or 4

- Glyph name: trademark	Contours detected: 6	Expected: 2

- Glyph name: two	Contours detected: 4	Expected: 1

- Glyph name: u	Contours detected: 2	Expected: 1

- Glyph name: uacute	Contours detected: 3	Expected: 2

- Glyph name: ubreve	Contours detected: 3	Expected: 2

- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

- Glyph name: udieresis	Contours detected: 4	Expected: 3

- Glyph name: ugrave	Contours detected: 3	Expected: 2

- Glyph name: uhorn	Contours detected: 3	Expected: 1

- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: umacron	Contours detected: 3	Expected: 2

- Glyph name: uni00B5	Contours detected: 2	Expected: 1

- Glyph name: uni0122	Contours detected: 4	Expected: 2

- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

- Glyph name: uni0137	Contours detected: 4	Expected: 2 or 3

- Glyph name: uni013B	Contours detected: 3	Expected: 2

- Glyph name: uni013C	Contours detected: 1	Expected: 2

- Glyph name: uni0145	Contours detected: 3	Expected: 2

- Glyph name: uni0146	Contours detected: 3	Expected: 2

- Glyph name: uni0157	Contours detected: 3	Expected: 2

- Glyph name: uni0162	Contours detected: 4	Expected: 1 or 2

- Glyph name: uni0186	Contours detected: 3	Expected: 1

- Glyph name: uni018A	Contours detected: 3	Expected: 2

- Glyph name: uni018E	Contours detected: 3	Expected: 1

- Glyph name: uni018F	Contours detected: 3	Expected: 2

- Glyph name: uni0190	Contours detected: 3	Expected: 1

- Glyph name: uni0198	Contours detected: 3	Expected: 1

- Glyph name: uni0199	Contours detected: 4	Expected: 1

- Glyph name: uni019C	Contours detected: 3	Expected: 1

- Glyph name: uni019D	Contours detected: 2	Expected: 1

- Glyph name: uni01B3	Contours detected: 3	Expected: 1

- Glyph name: uni01B4	Contours detected: 3	Expected: 1

- Glyph name: uni01CD	Contours detected: 2	Expected: 3

- Glyph name: uni01D3	Contours detected: 3	Expected: 2

- Glyph name: uni01D4	Contours detected: 3	Expected: 2

- Glyph name: uni01D7	Contours detected: 5	Expected: 4

- Glyph name: uni01D8	Contours detected: 5	Expected: 4

- Glyph name: uni01DD	Contours detected: 3	Expected: 2

- Glyph name: uni01DE	Contours detected: 4	Expected: 5

- Glyph name: uni01E2	Contours detected: 4	Expected: 3

- Glyph name: uni01E3	Contours detected: 5	Expected: 4

- Glyph name: uni01E8	Contours detected: 4	Expected: 2

- Glyph name: uni01E9	Contours detected: 4	Expected: 2

- Glyph name: uni01F8	Contours detected: 3	Expected: 2

- Glyph name: uni01F9	Contours detected: 3	Expected: 2

- Glyph name: uni0218	Contours detected: 4	Expected: 2

- Glyph name: uni0219	Contours detected: 4	Expected: 2

- Glyph name: uni021A	Contours detected: 4	Expected: 2

- Glyph name: uni0226	Contours detected: 2	Expected: 3

- Glyph name: uni0228	Contours detected: 4	Expected: 1

- Glyph name: uni0229	Contours detected: 4	Expected: 2

- Glyph name: uni0232	Contours detected: 3	Expected: 2

- Glyph name: uni0233	Contours detected: 3	Expected: 2

- Glyph name: uni0259	Contours detected: 3	Expected: 2

- Glyph name: uni0272	Contours detected: 2	Expected: 1

- Glyph name: uni0394	Contours detected: 1	Expected: 2

- Glyph name: uni03A9	Contours detected: 2	Expected: 1

- Glyph name: uni1E02	Contours detected: 3	Expected: 4

- Glyph name: uni1E14	Contours detected: 5	Expected: 3

- Glyph name: uni1E15	Contours detected: 5	Expected: 4

- Glyph name: uni1E1E	Contours detected: 3	Expected: 2

- Glyph name: uni1E20	Contours detected: 4	Expected: 2

- Glyph name: uni1E25	Contours detected: 3	Expected: 2

- Glyph name: uni1E36	Contours detected: 3	Expected: 2

- Glyph name: uni1E3E	Contours detected: 4	Expected: 2

- Glyph name: uni1E3F	Contours detected: 4	Expected: 2

- Glyph name: uni1E40	Contours detected: 4	Expected: 2

- Glyph name: uni1E41	Contours detected: 4	Expected: 2

- Glyph name: uni1E42	Contours detected: 4	Expected: 2

- Glyph name: uni1E43	Contours detected: 4	Expected: 2

- Glyph name: uni1E44	Contours detected: 3	Expected: 2

- Glyph name: uni1E45	Contours detected: 3	Expected: 2

- Glyph name: uni1E46	Contours detected: 3	Expected: 2

- Glyph name: uni1E47	Contours detected: 3	Expected: 2

- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

- Glyph name: uni1E60	Contours detected: 4	Expected: 2

- Glyph name: uni1E61	Contours detected: 4	Expected: 2

- Glyph name: uni1E62	Contours detected: 4	Expected: 2

- Glyph name: uni1E63	Contours detected: 4	Expected: 2

- Glyph name: uni1E6A	Contours detected: 4	Expected: 2

- Glyph name: uni1E6B	Contours detected: 3	Expected: 2

- Glyph name: uni1E6C	Contours detected: 4	Expected: 2

- Glyph name: uni1E6D	Contours detected: 3	Expected: 2

- Glyph name: uni1E92	Contours detected: 4	Expected: 2

- Glyph name: uni1E93	Contours detected: 4	Expected: 2

- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

- Glyph name: uni1EA0	Contours detected: 2	Expected: 3

- Glyph name: uni1EA2	Contours detected: 2	Expected: 3

- Glyph name: uni1EA4	Contours detected: 3	Expected: 4

- Glyph name: uni1EA6	Contours detected: 3	Expected: 4

- Glyph name: uni1EA8	Contours detected: 3	Expected: 4

- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

- Glyph name: uni1EAC	Contours detected: 3	Expected: 4

- Glyph name: uni1EAE	Contours detected: 3	Expected: 4

- Glyph name: uni1EB0	Contours detected: 3	Expected: 4

- Glyph name: uni1EB2	Contours detected: 3	Expected: 4

- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

- Glyph name: uni1EB6	Contours detected: 3	Expected: 4

- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

- Glyph name: uni1EBA	Contours detected: 4	Expected: 2

- Glyph name: uni1EBB	Contours detected: 4	Expected: 3

- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

- Glyph name: uni1EBE	Contours detected: 5	Expected: 3

- Glyph name: uni1EBF	Contours detected: 5	Expected: 4

- Glyph name: uni1EC0	Contours detected: 5	Expected: 3

- Glyph name: uni1EC1	Contours detected: 5	Expected: 4

- Glyph name: uni1EC2	Contours detected: 5	Expected: 3

- Glyph name: uni1EC3	Contours detected: 5	Expected: 4

- Glyph name: uni1EC4	Contours detected: 5	Expected: 3

- Glyph name: uni1EC5	Contours detected: 5	Expected: 4

- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

- Glyph name: uni1EC7	Contours detected: 5	Expected: 4

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

- Glyph name: uni1EE6	Contours detected: 3	Expected: 2

- Glyph name: uni1EE7	Contours detected: 3	Expected: 2

- Glyph name: uni1EE8	Contours detected: 4	Expected: 2

- Glyph name: uni1EE9	Contours detected: 4	Expected: 2

- Glyph name: uni1EEA	Contours detected: 4	Expected: 2

- Glyph name: uni1EEB	Contours detected: 4	Expected: 2

- Glyph name: uni1EEC	Contours detected: 4	Expected: 2

- Glyph name: uni1EED	Contours detected: 4	Expected: 2

- Glyph name: uni1EEE	Contours detected: 4	Expected: 2

- Glyph name: uni1EEF	Contours detected: 4	Expected: 2

- Glyph name: uni1EF0	Contours detected: 4	Expected: 2

- Glyph name: uni1EF1	Contours detected: 4	Expected: 2

- Glyph name: uni1EF4	Contours detected: 3	Expected: 2

- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

- Glyph name: uni1EF6	Contours detected: 3	Expected: 2

- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

- Glyph name: uni2206	Contours detected: 1	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uring	Contours detected: 4	Expected: 3

- Glyph name: utilde	Contours detected: 3	Expected: 2

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 3	Expected: 1

- Glyph name: wacute	Contours detected: 4	Expected: 2

- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

- Glyph name: wdieresis	Contours detected: 5	Expected: 3

- Glyph name: wgrave	Contours detected: 4	Expected: 2

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: yacute	Contours detected: 3	Expected: 2

- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: ydieresis	Contours detected: 4	Expected: 3

- Glyph name: ygrave	Contours detected: 3	Expected: 2

- Glyph name: z	Contours detected: 3	Expected: 1

- Glyph name: zacute	Contours detected: 4	Expected: 2

- Glyph name: zcaron	Contours detected: 4	Expected: 2

- Glyph name: zdotaccent	Contours detected: 4	Expected: 2
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1538 among a set of 8 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1358:
greater, less</p>
<p>Width = 1707:
logicalnot</p>
<p>Width = 1102:
approxequal</p>
<p>Width = 1018:
notequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni03020300

- uni03020301

- uni03020303

- uni03060300

- uni03060301

- uni03060303
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, canadian-aboriginal, tai-le, todhri, math, duployan, hebrew, old-permic, tifinagh, malayalam, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: math, greek, elbasan</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, greek, elbasan</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: phags-pa, yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to aogonek when shaping the text 'ą́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to aogonek when shaping the text 'ą̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uogonek when shaping the text 'ų́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uogonek when shaping the text 'ų̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɵ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɵ</td>
<td align="left">ig_Latn (Igbo)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: j̉ j̛̉ j̣̉ j̦̉ j̧̉ j̨̉ į̉ į̛̉ į̣̉ į̦̉ į̧̉ į̨̉ ị̉ ị̛̉ ị̣̉ ị̦̉ ị̧̉</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* Eng (U+014A): L&lt;&lt;831.0,-538.0&gt;--&lt;829.0,0.0&gt;&gt; -&gt; L&lt;&lt;829.0,0.0&gt;--&lt;829.0,1361.0&gt;&gt;

* Eng.loclNSM: L&lt;&lt;831.0,-538.0&gt;--&lt;829.0,0.0&gt;&gt; -&gt; L&lt;&lt;829.0,0.0&gt;--&lt;829.0,1361.0&gt;&gt;

* ampersand (U+0026): L&lt;&lt;823.0,398.0&gt;--&lt;822.0,680.0&gt;&gt; -&gt; L&lt;&lt;822.0,680.0&gt;--&lt;822.0,1361.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;1023.0,-343.0&gt;--&lt;980.0,-345.0&gt;&gt; -&gt; L&lt;&lt;980.0,-345.0&gt;--&lt;934.0,-347.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;854.0,1599.0&gt;--&lt;925.0,1598.0&gt;&gt; -&gt; L&lt;&lt;925.0,1598.0&gt;--&lt;982.0,1595.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;925.0,1598.0&gt;--&lt;982.0,1595.0&gt;&gt; -&gt; L&lt;&lt;982.0,1595.0&gt;--&lt;1023.0,1593.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;171.0,1593.0&gt;--&lt;258.0,1597.0&gt;&gt; -&gt; L&lt;&lt;258.0,1597.0&gt;--&lt;340.0,1599.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;272.0,-348.0&gt;--&lt;214.0,-345.0&gt;&gt; -&gt; L&lt;&lt;214.0,-345.0&gt;--&lt;171.0,-343.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;344.0,-349.0&gt;--&lt;272.0,-348.0&gt;&gt; -&gt; L&lt;&lt;272.0,-348.0&gt;--&lt;214.0,-345.0&gt;&gt;

* oe (U+0153): L&lt;&lt;1081.0,953.0&gt;--&lt;1094.0,960.0&gt;&gt; -&gt; L&lt;&lt;1094.0,960.0&gt;--&lt;1124.0,975.0&gt;&gt;

* s (U+0073): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* sacute (U+015B): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* scaron (U+0161): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* scedilla (U+015F): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* scircumflex (U+015D): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* uni0219 (U+0219): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* uni03020303: L&lt;&lt;1005.0,1961.0&gt;--&lt;856.0,1766.0&gt;&gt; -&gt; L&lt;&lt;856.0,1766.0&gt;--&lt;842.0,1750.0&gt;&gt;

* uni03020303: L&lt;&lt;178.0,1798.0&gt;--&lt;328.0,1993.0&gt;&gt; -&gt; L&lt;&lt;328.0,1993.0&gt;--&lt;341.0,2009.0&gt;&gt;

* uni03060303: L&lt;&lt;58.0,1798.0&gt;--&lt;208.0,1993.0&gt;&gt; -&gt; L&lt;&lt;208.0,1993.0&gt;--&lt;221.0,2009.0&gt;&gt;

* uni03060303: L&lt;&lt;885.0,1961.0&gt;--&lt;736.0,1766.0&gt;&gt; -&gt; L&lt;&lt;736.0,1766.0&gt;--&lt;722.0,1750.0&gt;&gt;

* uni1E61 (U+1E61): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* uni1E63 (U+1E63): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* uni1E93 (U+1E93): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt; -&gt; L&lt;&lt;1214.0,901.0&gt;--&lt;1214.0,762.0&gt;&gt;

* uni1E93 (U+1E93): L&lt;&lt;125.0,0.0&gt;--&lt;127.0,100.0&gt;&gt; -&gt; L&lt;&lt;127.0,100.0&gt;--&lt;127.0,261.0&gt;&gt;

* z (U+007A): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt; -&gt; L&lt;&lt;1214.0,901.0&gt;--&lt;1214.0,762.0&gt;&gt;

* z (U+007A): L&lt;&lt;125.0,0.0&gt;--&lt;127.0,100.0&gt;&gt; -&gt; L&lt;&lt;127.0,100.0&gt;--&lt;127.0,261.0&gt;&gt;

* zacute (U+017A): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt; -&gt; L&lt;&lt;1214.0,901.0&gt;--&lt;1214.0,762.0&gt;&gt;

* zacute (U+017A): L&lt;&lt;125.0,0.0&gt;--&lt;127.0,100.0&gt;&gt; -&gt; L&lt;&lt;127.0,100.0&gt;--&lt;127.0,261.0&gt;&gt;

* zcaron (U+017E): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt; -&gt; L&lt;&lt;1214.0,901.0&gt;--&lt;1214.0,762.0&gt;&gt;

* zcaron (U+017E): L&lt;&lt;125.0,0.0&gt;--&lt;127.0,100.0&gt;&gt; -&gt; L&lt;&lt;127.0,100.0&gt;--&lt;127.0,261.0&gt;&gt;

* zdotaccent (U+017C): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt; -&gt; L&lt;&lt;1214.0,901.0&gt;--&lt;1214.0,762.0&gt;&gt;

* zdotaccent (U+017C): L&lt;&lt;125.0,0.0&gt;--&lt;127.0,100.0&gt;&gt; -&gt; L&lt;&lt;127.0,100.0&gt;--&lt;127.0,261.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* aogonek (U+0105): B&lt;&lt;969.0,5.0&gt;-&lt;1008.0,32.0&gt;-&lt;1056.0,44.0&gt;&gt;/L&lt;&lt;1056.0,44.0&gt;--&lt;1052.0,44.0&gt;&gt; = 14.036243467926457

* eight (U+0038): B&lt;&lt;281.5,643.0&gt;-&lt;354.0,681.0&gt;-&lt;421.0,688.0&gt;&gt;/L&lt;&lt;421.0,688.0&gt;--&lt;419.0,688.0&gt;&gt; = 5.964487101253088

* eight (U+0038): L&lt;&lt;1193.0,688.0&gt;--&lt;1191.0,688.0&gt;&gt;/B&lt;&lt;1191.0,688.0&gt;-&lt;1259.0,681.0&gt;-&lt;1331.5,642.0&gt;&gt; = 5.8773926066431

* registered (U+00AE): B&lt;&lt;1596.5,615.5&gt;-&lt;1508.0,553.0&gt;-&lt;1365.0,536.0&gt;&gt;/B&lt;&lt;1365.0,536.0&gt;-&lt;1440.0,534.0&gt;-&lt;1508.5,517.5&gt;&gt; = 8.30709338736285

* section (U+00A7): B&lt;&lt;1392.0,378.0&gt;-&lt;1335.0,353.0&gt;-&lt;1260.0,344.0&gt;&gt;/L&lt;&lt;1260.0,344.0&gt;--&lt;1276.0,344.0&gt;&gt; = 6.842773412630916

* section (U+00A7): B&lt;&lt;382.0,913.0&gt;-&lt;462.0,999.0&gt;-&lt;611.0,1017.0&gt;&gt;/L&lt;&lt;611.0,1017.0&gt;--&lt;595.0,1017.0&gt;&gt; = 6.888258276994703
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* Eng (U+014A): L&lt;&lt;831.0,-538.0&gt;--&lt;829.0,0.0&gt;&gt;

* Eng.loclNSM: L&lt;&lt;831.0,-538.0&gt;--&lt;829.0,0.0&gt;&gt;

* ampersand (U+0026): L&lt;&lt;823.0,398.0&gt;--&lt;822.0,680.0&gt;&gt;

* five (U+0035): L&lt;&lt;730.0,680.0&gt;--&lt;125.0,681.0&gt;&gt;

* integral (U+222B): L&lt;&lt;1375.0,1549.0&gt;--&lt;1373.0,148.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;1265.0,138.0&gt;--&lt;1266.0,655.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;268.0,827.0&gt;--&lt;1438.0,825.0&gt;&gt;

* numbersign (U+0023): L&lt;&lt;831.0,1117.0&gt;--&lt;1127.0,1116.0&gt;&gt;

* onehalf (U+00BD): L&lt;&lt;472.0,-510.0&gt;--&lt;471.0,-341.0&gt;&gt;

* uni00B2 (U+00B2): L&lt;&lt;315.0,850.0&gt;--&lt;314.0,1019.0&gt;&gt;

* uni0198 (U+0198): L&lt;&lt;1640.0,932.0&gt;--&lt;829.0,934.0&gt;&gt;

* uni1E93 (U+1E93): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;

* z (U+007A): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;

* zacute (U+017A): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;

* zcaron (U+017E): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;

* zdotaccent (U+017C): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* A (U+0041) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Aacute (U+00C1) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Abreve (U+0102) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EAE (U+1EAE) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EB6 (U+1EB6) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EB0 (U+1EB0) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EB2 (U+1EB2) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EB4 (U+1EB4) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni01CD (U+01CD) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Acircumflex (U+00C2) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EA4 (U+1EA4) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EAC (U+1EAC) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EA6 (U+1EA6) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EA8 (U+1EA8) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EAA (U+1EAA) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Adieresis (U+00C4) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni01DE (U+01DE) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni0226 (U+0226) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EA0 (U+1EA0) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Agrave (U+00C0) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EA2 (U+1EA2) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Amacron (U+0100) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Aogonek (U+0104) contains a short segment L&lt;&lt;1124.0,0.0&gt;--&lt;1124.0,-28.0&gt;&gt;

* Aring (U+00C5) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Atilde (U+00C3) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* AE (U+00C6) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* AEacute (U+01FC) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni01E2 (U+01E2) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Lslash (U+0141) contains a short segment L&lt;&lt;150.0,679.0&gt;--&lt;134.0,679.0&gt;&gt;

* Lslash (U+0141) contains a short segment L&lt;&lt;656.0,670.0&gt;--&lt;672.0,670.0&gt;&gt;

* Oslash (U+00D8) contains a short segment L&lt;&lt;1330.0,1187.0&gt;--&lt;1331.0,1187.0&gt;&gt;

* Oslash (U+00D8) contains a short segment L&lt;&lt;214.0,182.0&gt;--&lt;212.0,182.0&gt;&gt;

* S (U+0053) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* Sacute (U+015A) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* Scaron (U+0160) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* Scedilla (U+015E) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* Scircumflex (U+015C) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* uni0218 (U+0218) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* uni1E60 (U+1E60) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* uni1E62 (U+1E62) contains a short segment L&lt;&lt;131.0,959.0&gt;--&lt;125.0,959.0&gt;&gt;

* eth (U+00F0) contains a short segment L&lt;&lt;1358.0,1412.0&gt;--&lt;1375.0,1412.0&gt;&gt;

* eth (U+00F0) contains a short segment L&lt;&lt;867.0,1484.0&gt;--&lt;848.0,1484.0&gt;&gt;

* iogonek (U+012F) contains a short segment L&lt;&lt;449.0,0.0&gt;--&lt;449.0,-28.0&gt;&gt;

* lslash (U+0142) contains a short segment L&lt;&lt;250.0,704.0&gt;--&lt;240.0,704.0&gt;&gt;

* lslash (U+0142) contains a short segment L&lt;&lt;768.0,826.0&gt;--&lt;778.0,826.0&gt;&gt;

* oslash (U+00F8) contains a short segment L&lt;&lt;1329.0,830.0&gt;--&lt;1332.0,830.0&gt;&gt;

* oslash (U+00F8) contains a short segment L&lt;&lt;204.0,188.0&gt;--&lt;201.0,188.0&gt;&gt;

* oe (U+0153) contains a short segment L&lt;&lt;1081.0,953.0&gt;--&lt;1094.0,960.0&gt;&gt;

* s (U+0073) contains a short segment L&lt;&lt;156.0,636.0&gt;--&lt;149.0,636.0&gt;&gt;

* sacute (U+015B) contains a short segment L&lt;&lt;156.0,636.0&gt;--&lt;149.0,636.0&gt;&gt;

* scaron (U+0161) contains a short segment L&lt;&lt;156.0,636.0&gt;--&lt;149.0,636.0&gt;&gt;

* scedilla (U+015F) contains a short segment L&lt;&lt;156.0,636.0&gt;--&lt;149.0,636.0&gt;&gt;

* scircumflex (U+015D) contains a short segment L&lt;&lt;156.0,636.0&gt;--&lt;149.0,636.0&gt;&gt;

* uni0219 (U+0219) contains a short segment L&lt;&lt;156.0,636.0&gt;--&lt;149.0,636.0&gt;&gt;

* uni1E61 (U+1E61) contains a short segment L&lt;&lt;156.0,636.0&gt;--&lt;149.0,636.0&gt;&gt;

* uni1E63 (U+1E63) contains a short segment L&lt;&lt;156.0,636.0&gt;--&lt;149.0,636.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;1149.0,0.0&gt;--&lt;1149.0,-28.0&gt;&gt;

* uni0394 (U+0394) contains a short segment L&lt;&lt;856.0,1529.0&gt;--&lt;857.0,1530.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;305.0,680.0&gt;--&lt;299.0,680.0&gt;&gt;

* dollar (U+0024) contains a short segment L&lt;&lt;275.0,959.0&gt;--&lt;269.0,959.0&gt;&gt;

* integral (U+222B) contains a short segment L&lt;&lt;835.0,142.0&gt;--&lt;837.0,150.0&gt;&gt;

* uni2206 (U+2206) contains a short segment L&lt;&lt;856.0,1529.0&gt;--&lt;857.0,1530.0&gt;&gt;

* radical (U+221A) contains a short segment L&lt;&lt;681.0,-337.0&gt;--&lt;681.0,-340.0&gt;&gt;

* radical (U+221A) contains a short segment L&lt;&lt;681.0,-340.0&gt;--&lt;680.0,-339.0&gt;&gt;

* radical (U+221A) contains a short segment L&lt;&lt;680.0,-339.0&gt;--&lt;680.0,-337.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;756.0,1527.0&gt;--&lt;757.0,1529.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;757.0,1529.0&gt;--&lt;758.0,1530.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;758.0,1530.0&gt;--&lt;759.0,1527.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;758.0,-337.0&gt;--&lt;758.0,-340.0&gt;&gt;

* lozenge (U+25CA) contains a short segment L&lt;&lt;758.0,-340.0&gt;--&lt;757.0,-339.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 5 | 27 | 209 | 15 | 199 | 0 | 
| 0% | 0% | 1% | 6% | 46% | 3% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
