## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Plaster-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 2053, but got 1531 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[21] Plaster-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check that legacy accents aren't used in composite glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Width of legacy accent &quot;hungarumlaut&quot; is zero; should be positive.</p>
 [code: legacy-accents-width]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table entries should not contain line-breaks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name entry COPYRIGHT_NOTICE on platform WINDOWS contains a line-break.</p>
 [code: line-break]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Plaster Regular: OS/2 sTypoAscender is 1531 when it should be 2000</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Plaster Regular: OS/2 sTypoDescender is -550 when it should be -560</p>
 [code: bad-typo-descender]



* 🔥 **FAIL** <p>Plaster Regular: hhea Ascender is 1531 when it should be 2000</p>
 [code: bad-hhea-ascender]



* 🔥 **FAIL** <p>Plaster Regular: hhea Descender is -550 when it should be -560</p>
 [code: bad-hhea-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
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
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
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

- Glyph name: Ncaron	Contours detected: 3	Expected: 2

- Glyph name: ncaron	Contours detected: 3	Expected: 2

- Glyph name: Eng	Contours detected: 2	Expected: 1

- Glyph name: eng	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 4	Expected: 2

- Glyph name: oe	Contours detected: 4	Expected: 3

- Glyph name: racute	Contours detected: 3	Expected: 2

- Glyph name: uni0156	Contours detected: 2	Expected: 3

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

- Glyph name: uni01B3	Contours detected: 3	Expected: 1

- Glyph name: uni01B4	Contours detected: 3	Expected: 1

- Glyph name: uni01CD	Contours detected: 2	Expected: 3

- Glyph name: uni01DD	Contours detected: 3	Expected: 2

- Glyph name: uni01DE	Contours detected: 4	Expected: 5

- Glyph name: Gcaron	Contours detected: 4	Expected: 2

- Glyph name: uni01F8	Contours detected: 3	Expected: 2

- Glyph name: uni01F9	Contours detected: 3	Expected: 2

- Glyph name: AEacute	Contours detected: 4	Expected: 3

- Glyph name: aeacute	Contours detected: 5	Expected: 4

- Glyph name: uni0218	Contours detected: 4	Expected: 2

- Glyph name: uni0219	Contours detected: 3	Expected: 2

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

- Glyph name: uni1E1E	Contours detected: 3	Expected: 2

- Glyph name: uni1E1F	Contours detected: 3	Expected: 2

- Glyph name: uni1E20	Contours detected: 4	Expected: 2

- Glyph name: uni1E25	Contours detected: 3	Expected: 2

- Glyph name: uni1E36	Contours detected: 3	Expected: 2

- Glyph name: uni1E3E	Contours detected: 4	Expected: 2

- Glyph name: uni1E3F	Contours detected: 4	Expected: 2

- Glyph name: uni1E40	Contours detected: 4	Expected: 2

- Glyph name: uni1E41	Contours detected: 4	Expected: 2

- Glyph name: uni1E44	Contours detected: 3	Expected: 2

- Glyph name: uni1E45	Contours detected: 3	Expected: 2

- Glyph name: uni1E46	Contours detected: 3	Expected: 2

- Glyph name: uni1E47	Contours detected: 3	Expected: 2

- Glyph name: uni1E60	Contours detected: 4	Expected: 2

- Glyph name: uni1E61	Contours detected: 4	Expected: 2

- Glyph name: uni1E62	Contours detected: 4	Expected: 2

- Glyph name: uni1E63	Contours detected: 4	Expected: 2

- Glyph name: uni1E6A	Contours detected: 4	Expected: 2

- Glyph name: uni1E6B	Contours detected: 3	Expected: 2

- Glyph name: Wgrave	Contours detected: 4	Expected: 2

- Glyph name: wgrave	Contours detected: 4	Expected: 2

- Glyph name: Wacute	Contours detected: 4	Expected: 2

- Glyph name: wacute	Contours detected: 4	Expected: 2

- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

- Glyph name: wdieresis	Contours detected: 5	Expected: 3

- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

- Glyph name: uni1EA0	Contours detected: 2	Expected: 3

- Glyph name: uni1EAC	Contours detected: 3	Expected: 4

- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

- Glyph name: uni1EC7	Contours detected: 5	Expected: 4

- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

- Glyph name: Ygrave	Contours detected: 3	Expected: 2

- Glyph name: ygrave	Contours detected: 3	Expected: 2

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

- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

- Glyph name: umacron	Contours detected: 3	Expected: 2

- Glyph name: uni00B5	Contours detected: 2	Expected: 1

- Glyph name: uni0122	Contours detected: 4	Expected: 2

- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

- Glyph name: uni013B	Contours detected: 3	Expected: 2

- Glyph name: uni013C	Contours detected: 1	Expected: 2

- Glyph name: uni0145	Contours detected: 3	Expected: 2

- Glyph name: uni0156	Contours detected: 2	Expected: 3

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

- Glyph name: uni01DD	Contours detected: 3	Expected: 2

- Glyph name: uni01DE	Contours detected: 4	Expected: 5

- Glyph name: uni01F8	Contours detected: 3	Expected: 2

- Glyph name: uni01F9	Contours detected: 3	Expected: 2

- Glyph name: uni0218	Contours detected: 4	Expected: 2

- Glyph name: uni0219	Contours detected: 3	Expected: 2

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

- Glyph name: uni1E1E	Contours detected: 3	Expected: 2

- Glyph name: uni1E20	Contours detected: 4	Expected: 2

- Glyph name: uni1E25	Contours detected: 3	Expected: 2

- Glyph name: uni1E36	Contours detected: 3	Expected: 2

- Glyph name: uni1E3E	Contours detected: 4	Expected: 2

- Glyph name: uni1E3F	Contours detected: 4	Expected: 2

- Glyph name: uni1E40	Contours detected: 4	Expected: 2

- Glyph name: uni1E41	Contours detected: 4	Expected: 2

- Glyph name: uni1E44	Contours detected: 3	Expected: 2

- Glyph name: uni1E45	Contours detected: 3	Expected: 2

- Glyph name: uni1E46	Contours detected: 3	Expected: 2

- Glyph name: uni1E47	Contours detected: 3	Expected: 2

- Glyph name: uni1E60	Contours detected: 4	Expected: 2

- Glyph name: uni1E61	Contours detected: 4	Expected: 2

- Glyph name: uni1E62	Contours detected: 4	Expected: 2

- Glyph name: uni1E63	Contours detected: 4	Expected: 2

- Glyph name: uni1E6A	Contours detected: 4	Expected: 2

- Glyph name: uni1E6B	Contours detected: 3	Expected: 2

- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

- Glyph name: uni1EA0	Contours detected: 2	Expected: 3

- Glyph name: uni1EAC	Contours detected: 3	Expected: 4

- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

- Glyph name: uni1EC7	Contours detected: 5	Expected: 4

- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

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
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1538 among a set of 8 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1358:
greater, less</p>
<p>Width = 1707:
logicalnot</p>
<p>Width = 1529:
approxequal</p>
<p>Width = 1018:
notequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, todhri, syriac, tifinagh, canadian-aboriginal, math, tai-le, malayalam, duployan, old-permic, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, math, greek</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
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
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Name table strings must not contain the string 'Reserved Font Name'. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name table entry contains &quot;Reserved Font Name&quot; for a family name (&quot;Plaster&quot;) that differs from the currently used family name (Plaster), which is fine.</p>
 [code: legacy-familyname]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋ į̣̌ į̨̀ į̨́ į̨̂ į̨̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Ekpeye (Latn, 226,000 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), South Central Banda (Latn, 244,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nzakara (Latn, 50,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Dan (Latn, 1,099,244 speakers), Kaska (Latn, 125 speakers), Aghem (Latn, 38,843 speakers), Yala (Latn, 200,000 speakers), Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Ngbaka (Latn, 1,020,000 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Sar (Latn, 500,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Heiltsuk (Latn, 300 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers), Fur (Latn, 1,230,163 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Mundani (Latn, 34,000 speakers), Mfumte (Latn, 79,000 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Kisi (Latn, 360,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dii (Latn, 71,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* A (U+0041) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Aacute (U+00C1) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Abreve (U+0102) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni01CD (U+01CD) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Acircumflex (U+00C2) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EAC (U+1EAC) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Adieresis (U+00C4) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni01DE (U+01DE) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni0226 (U+0226) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* uni1EA0 (U+1EA0) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Agrave (U+00C0) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Amacron (U+0100) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Aogonek (U+0104) contains a short segment L&lt;&lt;1124.0,0.0&gt;--&lt;1124.0,-28.0&gt;&gt;

* Aring (U+00C5) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* Atilde (U+00C3) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* AE (U+00C6) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

* AEacute (U+01FC) contains a short segment L&lt;&lt;685.0,462.0&gt;--&lt;685.0,424.0&gt;&gt;

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

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* Eng (U+014A): L&lt;&lt;831.0,-538.0&gt;--&lt;829.0,0.0&gt;&gt; -&gt; L&lt;&lt;829.0,0.0&gt;--&lt;829.0,1361.0&gt;&gt;

* ampersand (U+0026): L&lt;&lt;823.0,398.0&gt;--&lt;822.0,680.0&gt;&gt; -&gt; L&lt;&lt;822.0,680.0&gt;--&lt;822.0,1361.0&gt;&gt;

* atilde (U+00E3): L&lt;&lt;1340.0,1609.0&gt;--&lt;1113.0,1311.0&gt;&gt; -&gt; L&lt;&lt;1113.0,1311.0&gt;--&lt;1092.0,1288.0&gt;&gt;

* atilde (U+00E3): L&lt;&lt;79.0,1360.0&gt;--&lt;307.0,1658.0&gt;&gt; -&gt; L&lt;&lt;307.0,1658.0&gt;--&lt;327.0,1682.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;1023.0,-343.0&gt;--&lt;980.0,-345.0&gt;&gt; -&gt; L&lt;&lt;980.0,-345.0&gt;--&lt;934.0,-347.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;854.0,1599.0&gt;--&lt;925.0,1598.0&gt;&gt; -&gt; L&lt;&lt;925.0,1598.0&gt;--&lt;982.0,1595.0&gt;&gt;

* braceleft (U+007B): L&lt;&lt;925.0,1598.0&gt;--&lt;982.0,1595.0&gt;&gt; -&gt; L&lt;&lt;982.0,1595.0&gt;--&lt;1023.0,1593.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;171.0,1593.0&gt;--&lt;258.0,1597.0&gt;&gt; -&gt; L&lt;&lt;258.0,1597.0&gt;--&lt;340.0,1599.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;272.0,-348.0&gt;--&lt;214.0,-345.0&gt;&gt; -&gt; L&lt;&lt;214.0,-345.0&gt;--&lt;171.0,-343.0&gt;&gt;

* braceright (U+007D): L&lt;&lt;344.0,-349.0&gt;--&lt;272.0,-348.0&gt;&gt; -&gt; L&lt;&lt;272.0,-348.0&gt;--&lt;214.0,-345.0&gt;&gt;

* itilde (U+0129): L&lt;&lt;-200.0,1360.0&gt;--&lt;28.0,1658.0&gt;&gt; -&gt; L&lt;&lt;28.0,1658.0&gt;--&lt;48.0,1682.0&gt;&gt;

* itilde (U+0129): L&lt;&lt;1061.0,1609.0&gt;--&lt;834.0,1311.0&gt;&gt; -&gt; L&lt;&lt;834.0,1311.0&gt;--&lt;813.0,1288.0&gt;&gt;

* ntilde (U+00F1): L&lt;&lt;134.0,1360.0&gt;--&lt;362.0,1658.0&gt;&gt; -&gt; L&lt;&lt;362.0,1658.0&gt;--&lt;382.0,1682.0&gt;&gt;

* ntilde (U+00F1): L&lt;&lt;1395.0,1609.0&gt;--&lt;1168.0,1311.0&gt;&gt; -&gt; L&lt;&lt;1168.0,1311.0&gt;--&lt;1147.0,1288.0&gt;&gt;

* oe (U+0153): L&lt;&lt;1081.0,953.0&gt;--&lt;1094.0,960.0&gt;&gt; -&gt; L&lt;&lt;1094.0,960.0&gt;--&lt;1124.0,975.0&gt;&gt;

* otilde (U+00F5): L&lt;&lt;1358.0,1609.0&gt;--&lt;1131.0,1311.0&gt;&gt; -&gt; L&lt;&lt;1131.0,1311.0&gt;--&lt;1110.0,1288.0&gt;&gt;

* otilde (U+00F5): L&lt;&lt;97.0,1360.0&gt;--&lt;325.0,1658.0&gt;&gt; -&gt; L&lt;&lt;325.0,1658.0&gt;--&lt;345.0,1682.0&gt;&gt;

* s (U+0073): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* sacute (U+015B): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* scaron (U+0161): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* scedilla (U+015F): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* scircumflex (U+015D): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* tildecomb (U+0303): L&lt;&lt;1351.0,1609.0&gt;--&lt;1124.0,1311.0&gt;&gt; -&gt; L&lt;&lt;1124.0,1311.0&gt;--&lt;1103.0,1288.0&gt;&gt;

* tildecomb (U+0303): L&lt;&lt;90.0,1360.0&gt;--&lt;318.0,1658.0&gt;&gt; -&gt; L&lt;&lt;318.0,1658.0&gt;--&lt;338.0,1682.0&gt;&gt;

* uni0219 (U+0219): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* uni1E61 (U+1E61): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* uni1E63 (U+1E63): L&lt;&lt;149.0,636.0&gt;--&lt;144.0,662.0&gt;&gt; -&gt; L&lt;&lt;144.0,662.0&gt;--&lt;140.0,690.0&gt;&gt;

* uni1EBD (U+1EBD): L&lt;&lt;1341.0,1609.0&gt;--&lt;1114.0,1311.0&gt;&gt; -&gt; L&lt;&lt;1114.0,1311.0&gt;--&lt;1093.0,1288.0&gt;&gt;

* uni1EBD (U+1EBD): L&lt;&lt;80.0,1360.0&gt;--&lt;308.0,1658.0&gt;&gt; -&gt; L&lt;&lt;308.0,1658.0&gt;--&lt;328.0,1682.0&gt;&gt;

* uni1EF9 (U+1EF9): L&lt;&lt;129.0,1360.0&gt;--&lt;357.0,1658.0&gt;&gt; -&gt; L&lt;&lt;357.0,1658.0&gt;--&lt;377.0,1682.0&gt;&gt;

* uni1EF9 (U+1EF9): L&lt;&lt;1390.0,1609.0&gt;--&lt;1163.0,1311.0&gt;&gt; -&gt; L&lt;&lt;1163.0,1311.0&gt;--&lt;1142.0,1288.0&gt;&gt;

* utilde (U+0169): L&lt;&lt;129.0,1360.0&gt;--&lt;357.0,1658.0&gt;&gt; -&gt; L&lt;&lt;357.0,1658.0&gt;--&lt;377.0,1682.0&gt;&gt;

* utilde (U+0169): L&lt;&lt;1390.0,1609.0&gt;--&lt;1163.0,1311.0&gt;&gt; -&gt; L&lt;&lt;1163.0,1311.0&gt;--&lt;1142.0,1288.0&gt;&gt;

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
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* aogonek (U+0105): B&lt;&lt;969.0,5.0&gt;-&lt;1008.0,32.0&gt;-&lt;1056.0,44.0&gt;&gt;/L&lt;&lt;1056.0,44.0&gt;--&lt;1052.0,44.0&gt;&gt; = 14.036243467926457

* registered (U+00AE): B&lt;&lt;1695.0,785.0&gt;-&lt;1695.0,571.0&gt;-&lt;1305.0,536.0&gt;&gt;/B&lt;&lt;1305.0,536.0&gt;-&lt;1468.0,531.0&gt;-&lt;1530.0,507.0&gt;&gt; = 6.885179351761033

* section (U+00A7): B&lt;&lt;1392.0,378.0&gt;-&lt;1335.0,353.0&gt;-&lt;1260.0,344.0&gt;&gt;/L&lt;&lt;1260.0,344.0&gt;--&lt;1276.0,344.0&gt;&gt; = 6.842773412630916

* section (U+00A7): B&lt;&lt;382.0,913.0&gt;-&lt;462.0,999.0&gt;-&lt;611.0,1017.0&gt;&gt;/L&lt;&lt;611.0,1017.0&gt;--&lt;595.0,1017.0&gt;&gt; = 6.888258276994703
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* Eng (U+014A): L&lt;&lt;831.0,-538.0&gt;--&lt;829.0,0.0&gt;&gt;

* ampersand (U+0026): L&lt;&lt;823.0,398.0&gt;--&lt;822.0,680.0&gt;&gt;

* five (U+0035): L&lt;&lt;730.0,680.0&gt;--&lt;125.0,681.0&gt;&gt;

* integral (U+222B): L&lt;&lt;1375.0,1549.0&gt;--&lt;1373.0,148.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;1265.0,138.0&gt;--&lt;1266.0,655.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;268.0,827.0&gt;--&lt;1438.0,825.0&gt;&gt;

* numbersign (U+0023): L&lt;&lt;831.0,1117.0&gt;--&lt;1127.0,1116.0&gt;&gt;

* onehalf (U+00BD): L&lt;&lt;472.0,-510.0&gt;--&lt;471.0,-341.0&gt;&gt;

* uni00B2 (U+00B2): L&lt;&lt;315.0,850.0&gt;--&lt;314.0,1019.0&gt;&gt;

* uni0198 (U+0198): L&lt;&lt;1640.0,932.0&gt;--&lt;829.0,934.0&gt;&gt;

* z (U+007A): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;

* zacute (U+017A): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;

* zcaron (U+017E): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;

* zdotaccent (U+017C): L&lt;&lt;1215.0,1020.0&gt;--&lt;1214.0,901.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 16 | 116 | 9 | 104 | 0 | 
| 0% | 0% | 2% | 6% | 46% | 4% | 41% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
