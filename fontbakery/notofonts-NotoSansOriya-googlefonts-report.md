## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[8] NotoSansOriya[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



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
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- omoriya

- uni0B1F.base.001

- uni0B4D0B30.single
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
aiLengthcandraBinduoriya.BRACKET.varAlt01, aiLengthcandraBinduoriya.stem.BRACKET.varAlt01, aiLengthcandraBinduoriya.umbrella, aiLengthcandraBinduoriya.umbrella.BRACKET.varAlt01, aicandraBinduoriya.BRACKET.varAlt01, airephcandraBinduoriya.BRACKET.varAlt01, auLengthcandraBinduoriya.BRACKET.varAlt01, aucandraBinduoriya.BRACKET.varAlt01, aurephcandraBinduoriya.BRACKET.varAlt01, iMatracandraBinduoriya.BRACKET.varAlt01, iMatracandraBinduoriya.wide.BRACKET.varAlt01, iMatrarephcandraBinduoriya.BRACKET.varAlt01, iMatrarephcandraBinduoriya.wide.BRACKET.varAlt01, rephaiLengthcandraBinduoriya.BRACKET.varAlt01, rephaiLengthcandraBinduoriya.stem, rephaiLengthcandraBinduoriya.stem.BRACKET.varAlt01, rephaiLengthcandraBinduoriya.umbrella, rephaiLengthcandraBinduoriya.umbrella.BRACKET.varAlt01, rephauLengthcandraBinduoriya.BRACKET.varAlt01 and rephcandraBinduoriya.BRACKET.varAlt01</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansOriya/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, todhri, tifinagh, math, old-permic, hebrew, malayalam, duployan, coptic, tai-le, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+035A COMBINING DOUBLE RING BELOW: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>oriya</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers), Han (Latn, 6 speakers), Kaska (Latn, 125 speakers), Navajo (Latn, 166,319 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Cicipu (Latn, 44,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Sar (Latn, 500,000 speakers), Yala (Latn, 200,000 speakers), Basaa (Latn, 332,940 speakers), Zapotec (Latn, 490,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Dii (Latn, 71,000 speakers), Aghem (Latn, 38,843 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Fur (Latn, 1,230,163 speakers), Mundani (Latn, 34,000 speakers), Makaa (Latn, 221,000 speakers), Bafut (Latn, 158,146 speakers), Vute (Latn, 21,000 speakers), Ekpeye (Latn, 226,000 speakers), Ma’di (Latn, 584,000 speakers), Koonzime (Latn, 40,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Gulay (Latn, 250,478 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Nzakara (Latn, 50,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 7 | 94 | 7 | 142 | 0 | 
| 0% | 0% | 0% | 3% | 37% | 3% | 57% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG