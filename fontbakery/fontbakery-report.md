## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[7] Delicious-Handrawn-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00A0 (NO-BREAK SPACE)


	- 0x2026 (HORIZONTAL ELLIPSIS)


	- 0x01CD (LATIN CAPITAL LETTER A WITH CARON)


	- 0x014A (LATIN CAPITAL LETTER ENG)


	- 0x016C (LATIN CAPITAL LETTER U WITH BREVE)


	- 0x01CE (LATIN SMALL LETTER A WITH CARON)


	- 0x014B (LATIN SMALL LETTER ENG)


	- 0x016D (LATIN SMALL LETTER U WITH BREVE)


	- 0x00AA (FEMININE ORDINAL INDICATOR)


	- 0x00BA (MASCULINE ORDINAL INDICATOR)
 

	- And 11 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains glyphs for whitespace characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphs">com.google.fonts/check/whitespace_glyphs</a>)</summary><div>


* 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0. [code: missing-whitespace-glyph-0x00A0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* d (U+0064): X=185.0,Y=502.0 (should be at x-height 500?)

	* j (U+006A): X=-16.0,Y=-1.0 (should be at baseline 0?)

	* p (U+0070): X=96.0,Y=1.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=168.5,Y=721.5 (should be at cap-height 720?)

	* Agrave (U+00C0): X=130.5,Y=721.0 (should be at cap-height 720?)

	* Acircumflex (U+00C2): X=156.0,Y=722.0 (should be at cap-height 720?)

	* Acircumflex (U+00C2): X=159.5,Y=718.0 (should be at cap-height 720?)

	* Acircumflex (U+00C2): X=156.0,Y=722.0 (should be at cap-height 720?)

	* Atilde (U+00C3): X=114.0,Y=722.0 (should be at cap-height 720?)

	* Eacute (U+00C9): X=165.0,Y=718.0 (should be at cap-height 720?) 

	* And 46 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 2 | 5 | 122 | 8 | 90 | 0 |
| 0% | 1% | 2% | 54% | 4% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**