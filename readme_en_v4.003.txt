Kanji Stroke Order Font v4.003
==============================

   Released 15 March 2020
   ======================

   Latest version at: http://nihilist.org.uk

INTRODUCTION
This font provides an easy way to view stroke order diagrams for over 6500
kanji, over 180 kana symbols, the Latin characters and quite a few other
symbols. I have also used it as a dumping ground for my own character
creation doodles.

My hope is that this font will assist people who are learning kanji. I
also hope it will help teachers of Japanese in the preparation of
classroom material. Beware that Japanese stroke order can differ from the
stroke order used in other languages that use Chinese characters.

HOW TO INSTALL AND USE THIS FONT
Install this font as you would any other TrueType font. In the parts of
your document where you want the kanji to be annotated with stroke order
numbers simply set your document's font to KanjiStrokeOrders. You will
need to set the size of the font to be large to allow the stroke order
numbers to show up: 100pt seems to be the minimum usable size.

As of version v4.003, KSOF works with Microsoft Word on Macintosh as well
as with Microsoft Word for Windows. This was the most significant change
from v4.001 to v4.002.

If you use the Anki flashcard program then the Anki website includes some
instructions on using custom fonts (such as KSOF) with that package. One
user reported needing to rename the font filename to remove the version
number to get it to work with AnkiDroid.

I have had one report from the field of Mac OS X 10.4.11 complaining about
missing OpenType data, although this does not happen with OS X 10.5. I am
told that KSOF works fine on OS X 10.4.11 if you ignore the warning, so it's
nothing to worry about. Thanks are due to Phil for reporting this.

LICENCE
This font may be freely distributed under the terms of the BSD-style licence
included with this archive in the file copyright.txt. This licence is very
permissive. In particular, the licence permits:
1. Use of the font for producing documents, including commercial documents.
2. Redistribution of the font, provided you leave the copyright notice intact.
   This includes selling the font commercially for a profit.
3. Use of the font in non-commercial and commercial software.

The kanji stroke order diagrams remain under the copyright of Ulrich Apel
and the AAAA and Wadoku projects. If you find this font useful then please
consider making a donation to the Wadoku project by pointing your Web
browser at http://www.wadoku.de and clicking on "Spenden".

INTEGRATION WITH JWPCE
This font enables you to view kanji stroke orders in JWPce. Set the "Big
Kanji Font" to KanjiStrokeOrders in the Options dialog. Some kanji stroke
order diagrams might show a different stroke count to that reported by
JWPce in the same kanji information window. This is because some kanji
have more than one valid stroke count.

TECHNICAL INFORMATION
I created this font by using the Batik library to convert the AAAA and
Wadoku projects' SVG files into high-resolution PNG images. I turned these
into a font using Fontforge. I use Fontforge for ongoing development.

The Kanji Stroke Order Font includes all the characters defined by JIS X
0208:1997, plus many more.

EXAMPLES
Included in this archive are two examples of the use of this font with popular
office software. They are in PDF format.

CORRECTIONS
As the changelog below shows, users have found quite a few errors in the
stroke orders diagrams. There are probably more. If you find any errors
please let me know by email: mail |at| nihilist (dot) org (dot) uk. You
can expect your changes to appear once enough fixes have accumulated to
make a new release worthwhile. When reporting an error, please tell me
what you think is wrong with the kanji and provide a link to a reference
if possible.

While working on this font I was interested to find that references
generally considered to be authoratitive sometimes disagree on stroke
order and even stroke count. U+53CE ??? and U+6E1B ??? are examples of
kanji that vary in documented stroke order. Furthermore, the
well-respected reference Kanjidic lists hundreds of kanji with multiple
valid stroke counts. Appendix E of the Kanjidic documentation discusses
stroke counts in detail. If you are not sure whether a character needs
correcting please let me know anyway so I can investigate. My primary
reference is http://kakijun.jp/.

OPENTYPE FEATURES
+smcp Small capitals for a-z. For example, in XeTeX use
      \font\smallcaps="KanjiStrokeOrders:+smcp" at 10pt
+utop Thomas More's Utopian characters plus the product integral symbol.
      The lowercase Latin characters map to their Utopian counterparts and z
      maps to the product integral symbol. Note that Thomas More wrote
      "Utopia" in Latin and, as such, this range of characters does not
      include the letters j, u, w or z (but z maps to the product integral
      symbol).
+spec The Sinclair ZX spectrum block graphics characters. These originally
      occupied the range 0x80 to 0x8F in the Sinclair ZX Spectrum character
      set. The symbol @ maps to the blank block and the letters A to O
      correspond to the non-blank block graphics. Why @? Because in the ZX
      Spectrum character set @ was 0x40 and A-O were 0x41-0x4F.

CHANGELOG
2020/03/15  4.003 Corrected errors reported by users and added more glyphs
                  to provide coverage of all KanjiVG glyphs.
                  J??y?? and other common use kanji that have changed:
                    U+4E00 ??? Adjusted vertical position
                    U+4E91 ??? Adjusted size
                    U+4FFA ??? Adjusted size
                    U+5099 ??? Reverted to textbook form
                    U+515C ??? Adjusted size
                    U+698A ??? Improved appearance
                    U+79B0 ??? Improved appearance
                    U+82A5 ??? Adjusted vertical position
                  Non-J??y?? kanji that have changed:
                    U+00D0 ?? Added stroke numbers to character
                    U+00DE ?? Added stroke numbers to character
                    U+00F0 ?? Added stroke numbers to character
                    U+00FE ?? Added stroke numbers to character
                    U+0262 ?? Added
                    U+0274 ?? Added
                    U+0280 ?? Added
                    U+028F ?? Added
                    U+0299 ?? Added
                    U+029C ?? Added
                    U+029F ?? Added
                    U+1D00 ??? Added
                    U+1D04 ??? Added
                    U+1D05 ??? Added
                    U+1D07 ??? Added
                    U+1D0A ??? Added
                    U+1D0B ??? Added
                    U+1D0D ??? Added
                    U+1D0E ??? Added
                    U+1D0F ??? Added
                    U+1D18 ??? Added
                    U+1D1B ??? Added
                    U+1D1C ??? Added
                    U+1D20 ??? Added
                    U+1D21 ??? Added
                    U+1D22 ??? Added
                    U+34C1 ??? Added
                    U+5173 ??? Added
                    U+5300 ??? Added
                    U+55BB ??? Added
                    U+5653 ??? Added
                    U+5723 ??? Added
                    U+57F6 ??? Added
                    U+59F8 ??? Added
                    U+5C03 ??? Added
                    U+5C5B ??? Added
                    U+5E77 ??? Added
                    U+6220 ??? Added
                    U+65BF ??? Added
                    U+687C ??? Added
                    U+6C10 ??? Improved appearance
                    U+701E ??? Improve appearance
                    U+79BB ??? Added
                    U+7FF3 ??? Changed to handwritten form
                    U+96E9 ??? Added
                    U+A730 ??? Added
                    U+A731 ??? Added
                    U+A764 ??? Added
                    U+A765 ??? Added
                    U+A766 ??? Added
                    U+A767 ??? Added
                    U+A7AF ??? Added
                    U+F92E ??? Added, identical to U+51B7 ???
                    U+F9A8 ??? Added, identical to U+4EE4 ???
                    U+F9AB ??? Added, identical to U+5DBA ???
                    U+F9AD ??? Added, identical to U+73B2 ???
                    U+F9AF ??? Added, identical to U+7F9A ???
                    U+F9B0 ??? Added, identical to U+8046 ???
                    U+F9B1 ??? Added, identical to U+9234 ???
                    U+F9B2 ??? Added, identical to U+96F6 ???
                    U+F9B4 ??? Added, identical to U+9818 ???
                    U+2008A ???? Added to private use area at U+F780
                    U+200A4 ???? Added to private use area at U+F781
                    U+26951 ???? Added to private use area at U+F782
2018/07/27  4.002 Added support for Microsoft Word on Macintosh.
                  Corrected errors reported by users, general clean-up and added some more glyphs
                  J??y?? and other common use kanji that have changed:
                    U+5026 ??? Updated to JIS2004 appearance
                    U+5099 ??? Updated appearance to more common form
                    U+53A9 ??? Improved appearance by raising character
                    U+5FD7 ??? Improved appearance
                    U+76E1 ??? Corrected stroke order
                  Non-J??y?? kanji that have changed:
                    U+2150 ??? Removed hole
                    U+2151 ??? Removed hole
                    U+2152 ??? Removed hole
                    U+2153 ??? Removed hole
                    U+2154 ??? Removed hole
                    U+2155 ??? Removed hole
                    U+2156 ??? Removed hole
                    U+2157 ??? Removed hole
                    U+2158 ??? Removed hole
                    U+215A ??? Removed hole
                    U+215B ??? Removed hole
                    U+215C ??? Removed hole
                    U+215F ??? Removed hole
                    U+23FB ??? Added IEC Power symbol
                    U+23FC ??? Added IEC Power On-Off symbol
                    U+23FD ??? Added IEC Power On symbol
                    U+23FE ??? Added IEC Power Sleep symbol
                    U+2B58 ??? Added Heavy Circle = IEC Power Off symbol
                    U+4E02 ??? Added
                    U+4E04 ??? Added
                    U+4E05 ??? Added
                    U+4E0C ??? Added
                    U+4E29 ??? Added
                    U+4E40 ??? Added
                    U+4E41 ??? Added
                    U+4E47 ??? Added
                    U+4E61 ??? Improved appearance
                    U+4E8D ??? Added
                    U+4E96 ??? Added
                    U+53AD ??? Improved appearance by raising character
                    U+58D7 ??? Corrected stroke order, clarified numbering
                    U+6108 ??? Updated to JIS2004 appearance
                    U+6260 ??? Improved appearance
2016/09/25  4.001 Corrected errors reported by users
                  J??y?? and other common use kanji that have changed:
                    U+5265 ??? Added numer for stroke 1
                    U+584A ??? Clarified numbering
                    U+5EDF ??? Updated to JIS2004 appearance
                    U+63C3 ??? Updated to JIS2004 appearance
                    U+6F81 ??? Clarified numbering
                    U+714E ??? Improved appearance
                    U+76E3 ??? Clarified numbering
                    U+840E ??? Adjusted position relative to baseline
                    U+8888 ??? Corrected stroke order
                    U+88CF ??? Clarified numbering
                    U+8AD6 ??? Clarified numbering
                    U+8CBC ??? Corrected appearance
                    U+9061 ??? Added extra stroke in line with JIS X 0213:2004
                    U+9A57 ??? Corrected stroke order and clarified numbering
                    U+9A5A ??? Clarified numbering
                  Non-J??y?? kanji that have changed:
                    U+34B5 ??? Corrected appearance
                    U+5078 ??? Corrected appearance
                    U+5118 ??? Corrected stroke order
                    U+516A ??? Corrected appearance
                    U+5614 ??? Clarified numbering
                    U+56C0 ??? Updated to JIS2004 appearance
                    U+56CE ??? Corrected appearance
                    U+589F ??? Corrected stroke order
                    U+58D7 ??? Clarified numbering
                    U+58E4 ??? Clarified numbering
                    U+5910 ??? Improved appearance
                    U+5C28 ??? Corrected stroke order
                    U+5D90 ??? Clarified numbering
                    U+601B ??? Corrected appearance
                    U+6026 ??? Corrected stroke order
                    U+60BD ??? Corrected stroke order
                    U+61CB ??? Corrected stroke order
                    U+6260 ??? Clarified numbering
                    U+63C4 ??? Corrected appearance
                    U+6801 ??? Increased size
                    U+6961 ??? Corrected appearance
                    U+69DD ??? Clarified numbering
                    U+6A62 ??? Corrected stroke order
                    U+6B16 ??? Clarified numbering
                    U+6B1F ??? Clarified numbering
                    U+6B54 ??? Corrected stroke order and clarified numbering
                    U+6BB2 ??? Corrected stroke order
                    U+6CEA ??? Corrected appearance
                    U+6E1D ??? Corrected appearance
                    U+6E76 ??? Corrected stroke order
                    U+6F80 ??? Corrected to 17 strokes
                    U+701B ??? Corrected stroke order and clarified numbering
                    U+71E0 ??? Corrected stroke order
                    U+7228 ??? Corrected stroke order
                    U+745C ??? Corrected appearance
                    U+7609 ??? Corrected appearance
                    U+7AC4 ??? Corrected appearance
                    U+7AC7 ??? Clarified numbering
                    U+7BAD ??? Updated to JIS2004 appearance
                    U+7BDD ??? Corrected appearance of stroke 15
                    U+7CB2 ??? Corrected stroke order
                    U+7C6C ??? Corrected appearance
                    U+7E90 ??? Corrected stroke order
                    U+7FB8 ??? Corrected stroke order
                    U+81BD ??? Corrected stroke order and appearance
                    U+84AD ??? Corrected stroke order
                    U+8590 ??? Corrected stroke order
                    U+8753 ??? Corrected appearance
                    U+8805 ??? Improved appearance of stroke 13 and clarified numbering
                    U+8836 ??? Clarified numbering
                    U+891E ??? Clarified numbering
                    U+8960 ??? Clarified numbering
                    U+89A6 ??? Corrected appearance
                    U+8A85 ??? Corrected stroke order
                    U+8B6B ??? Corrected stroke order and appearance
                    U+8B96 ??? Corrected stroke order and clarified numbering
                    U+8D0A ??? Clarified numbering
                    U+8D0D ??? Corrected stroke order
                    U+8D0F ??? Corrected stroke order
                    U+8E10 ??? Corrected stroke order
                    U+8E50 ??? Corrected stroke order
                    U+8E81 ??? Corrected stroke order and clarified numbering
                    U+8EAA ??? Clarified numbering
                    U+8EDB ??? Clarified numbering
                    U+8F15 ??? Clarified numbering
                    U+8F57 ??? Corrected stroke order and appearance, clarified numbering
                    U+903E ??? Corrected appearance
                    U+905E ??? Corrected stroke order
                    U+91C1 ??? Corrected stroke order
                    U+936E ??? Corrected appearance
                    U+95CC ??? Clarified numbering
                    U+974D ??? Clarified numbering
                    U+991E ??? Corrected stroke order
                    U+9AE3 ??? Added missing stroke 6, clarified numbering
                    U+9B06 ??? Clarified numbering
                    U+9B22 ??? Clarified numbering
                    U+9B43 ??? Clarified numbering
                    U+9C47 ??? Clarified numbering
                    U+9ED0 ??? Corrected to 23 strokes
                               The character U+9ED0 ??? has changed twice before in
                               KSOF. The reference I use is http://kakijun.jp and
                               this shows 22 strokes in the image but 23 strokes in
                               the reference information. For this release I have
                               settled on 23 strokes.
                    U+FA1E ??? Corrected appearance
                    U+FA1F ??? Corrected size
                    U+FA49 ??? Added
                    U+FA66 ??? Added
                  Cleaned up self-intersecting paths in font (no significant visible effect).
                  Cleaned up inconsistent directions in font (no visible effect).
2016/07/04  4.000 Corrected errors reported by users and added some characters.
                  Many of the changes relate to JIS X 0213:2004. In detail:
                  J??y?? kanji that have changed:
                    U+5099 ??? Improved appearence
                    U+50C5 ??? Corrected appearence and added stroke in line with JIS X 0213:2004
                    U+525D ??? Added
                    U+52E7 ??? Adjusted position of some stroke order numbers for clarity without changing the order
                    U+55C5 ??? Changed appearence
                    U+5632 ??? Corrected appearence slightly in line with JIS X 0213:2004
                    U+5861 ??? Corrected appearence
                    U+5C5E ??? Corrected direction of stroke 4 (slightly controversial)
                    U+60E7 ??? Corrected appearence
                    U+6144 ??? Corrected order of strokes 7,8 and 9
                    U+6975 ??? Adjusted position of the number for stroke 7 slightly for clarity.
                    U+6BC0 ??? Corrected stroke order
                    U+6DEB ??? Corrected appearence in line with JIS X 0213:2004
                    U+6E80 ??? Improved appearence slightly
                    U+6EBA ??? Corrected appearence in line with JIS X 0213:2004
                    U+6F5F ??? Corrected order of strokes 6 and 7
                    U+7B8B ??? Corrected appearence
                    U+8108 ??? Improved appearence
                    U+81A8 ??? Improved appearence
                    U+81FC ??? Reversed strokes 3 and 4
                    U+8328 ??? Corrected appearence in line with JIS X 0213:2004
                    U+845B ??? Corrected appearence in line with JIS X 0213:2004
                    U+8511 ??? Corrected appearence in line with JIS X 0213:2004
                    U+853D ??? Corrected appearence in line with JIS X 0213:2004
                    U+8AE7 ??? Reversed strokes 10 and 11
                    U+8AFE ??? Clarified numbering
                    U+8B0E ??? Added an extra stroke in line with JIS X 0213:2004
                    U+8CED ??? Corrected appearence
                    U+905C ??? Added an extra stroke in line with JIS X 0213:2004
                    U+9061 ??? Corrected appearence in line with JIS X 0213:2004
                    U+91C8 ??? Improved appearence slightly by unmerging stroke 10 from the stroke itself
                    U+9699 ??? Corrected appearence in line with JIS X 0213:2004
                    U+96E2 ??? Improved appearence (more like handwritten version)
                    U+96EA ??? Improved appearence slightly
                    U+9905 ??? Corrected appearence in line with JIS X 0213:2004
                    U+990C ??? Corrected appearence in line with JIS X 0213:2004
                  Non-J??y?? kanji that have changed:
                    U+2E84 ??? Added
                    U+2EA9 ??? Added
                    U+2EAC ??? Added
                    U+2EBA ??? Added
                    U+2ECF ??? Added
                    U+2ED6 ??? Added
                    U+2ED7 ??? Added
                    U+342C ??? Added
                    U+353E ??? Added
                    U+38FA ??? Added
                    U+4ECD ??? Swapped strokes 3 and 4
                    U+4FAB ??? Corrected stroke order
                    U+5026 ??? Corrected stroke order and appearence
                    U+502A ??? Corrected stroke order
                    U+5055 ??? Corrected stroke order
                    U+5080 ??? Clarified stroke order by adjusting position of number 6
                    U+5109 ??? Repositioned numbers for clarity
                    U+5132 ??? Corrected stroke order and appearence
                    U+514E ??? Corrected stroke order and appearence
                    U+5152 ??? Corrected stroke order
                    U+51A4 ??? Corrected stroke order and corrected appearence in line with JIS X 0213:2004
                    U+524F ??? Corrected stroke order
                    U+52F5 ??? Corrected stroke order
                    U+5333 ??? Corrected stroke order
                    U+5342 ??? Added
                    U+537F ??? Corrected appearence in line with JIS X 0213:2004
                    U+53A9 ??? Corrected appearence in line with JIS X 0213:2004
                    U+53DA ??? Added
                    U+53DB ??? Corrected appearence in line with JIS X 0213:2004
                    U+53DF ??? Corrected appearence in line with JIS X 0213:2004
                    U+53F1 ??? Moved stroke 4 back to starting on right side. See also U+FAFF.
                    U+54C8 ??? Corrected stroke order
                    U+54E8 ??? Corrected appearence in line with JIS X 0213:2004
                    U+5557 ??? Corrected stroke order
                    U+558A ??? Corrected stroke order
                    U+55B0 ??? Corrected appearence in line with JIS X 0213:2004
                    U+55BF ??? Added
                    U+5618 ??? Improved appearence of numbering
                    U+5642 ??? Corrected appearence in line with JIS X 0213:2004
                    U+564C ??? Corrected appearence in line with JIS X 0213:2004
                    U+57A0 ??? Corrected stroke order
                    U+582F ??? Reversed strokes 8 and 9
                    U+5835 ??? Corrected appearence in line with JIS X 0213:2004
                    U+583A ??? Corrected stroke order
                    U+583D ??? Corrected appearence and stroke order
                    U+590C ??? Added
                    U+590D ??? Added
                    U+5967 ??? Corrected stroke order by swapping strokes 7 and 8
                    U+5969 ??? Corrected stroke order
                    U+5A29 ??? Corrected appearence in line with JIS X 0213:2004
                    U+5A29 ??? Corrected stroke order
                    U+5A36 ??? Corrected stroke order
                    U+5A40 ??? Corrected stroke order
                    U+5A41 ??? Clarified numbering
                    U+5A6A ??? Corrected stroke order
                    U+5ABD ??? Corrected stroke order
                    U+5AC2 ??? Corrected stroke order
                    U+5AE3 ??? Corrected stroke order
                    U+5B70 ??? Corrected stroke order
                    U+5BEB ??? Corrected stroke order
                    U+5C05 ??? Corrected stroke order
                    U+5C08 ??? Corrected stroke order
                    U+5C1E ??? Added
                    U+5C51 ??? Corrected appearence in line with JIS X 0213:2004
                    U+5C60 ??? Corrected stroke order and appearence in line with JIS X 0213:2004
                    U+5CEF ??? Corrected stroke order
                    U+5D6C ??? Adjusted position of some stroke order numbers for clarity without changing the order
                    U+5DAC ??? Corrected stroke order
                    U+5DCD ??? Adjusted position of some stroke order numbers for clarity without changing the order
                    U+5DF7 ??? Corrected appearence in line with JIS X 0213:2004
                    U+5E43 ??? Corrected stroke count
                    U+5E96 ??? Corrected appearence in line with JIS X 0213:2004
                    U+5F98 ??? Corrected appearence in line with JIS X 0213:2004
                    U+5FBD ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+6062 ??? Corrected appearence in line with JIS X 0213:2004
                    U+60FB ??? Corrected stroke order
                    U+6108 ??? Corrected appearence in line with JIS X 0213:2004
                    U+6127 ??? Clarified numbering
                    U+6173 ??? Corrected stroke order
                    U+61FD ??? Corrected stroke order
                    U+6221 ??? Corrected stroke order
                    U+6241 ??? Corrected appearence in line with JIS X 0213:2004
                    U+6283 ??? Corrected stroke order
                    U+6302 ??? Corrected stroke order
                    U+633D ??? Corrected appearence in line with JIS X 0213:2004
                    U+6372 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+6406 ??? Corrected stroke order
                    U+641C ??? Corrected stroke order
                    U+647A ??? Corrected appearence in line with JIS X 0213:2004
                    U+64B0 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+64BB ??? Corrected stroke order
                    U+64D4 ??? Corrected stroke order
                    U+64E2 ??? Corrected appearence in line with JIS X 0213:2004
                    U+6505 ??? Corrected stroke order
                    U+651C ??? Corrected stroke order
                    U+6666 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+66C9 ??? Reversed strokes 11 and 12
                    U+6736 ??? Corrected stroke order by swapping strokes 1 and 2
                    U+6753 ??? Corrected appearence in line with JIS X 0213:2004
                    U+6801 ??? Added
                    U+6883 ??? Corrected stroke order
                    U+688F ??? Corrected stroke order
                    U+691B ??? Changed appearence
                    U+6962 ??? Corrected appearence in line with JIS X 0213:2004
                    U+698A ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+6994 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+69CC ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+69D0 ??? Corrected appearence and improved number placement
                    U+69F9 ??? Corrected stroke order
                    U+6A0B ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+6A3D ??? Corrected appearence in line with JIS X 0213:2004
                    U+6A48 ??? Improved position of numbers 9 and 12
                    U+6A9C ??? Corrected stroke order
                    U+6ADB ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+6B1D ??? Corrected stroke order
                    U+6B4E ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+6C10 ??? Added
                    U+6C72 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+6C9B ??? Corrected in line with JIS X 0213:2004
                    U+6EA2 ??? Corrected appearence in line with JIS X 0213:2004
                    U+6ED4 ??? Corrected stroke order
                    U+6F23 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+6F91 ??? Corrected stroke order
                    U+7009 ??? Corrected stroke order
                    U+7015 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+701E ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+7026 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+7058 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+707C ??? Corrected appearence in line with JIS X 0213:2004
                    U+70AC ??? Improved appearence
                    U+7109 ??? Corrected stroke order
                    U+7130 ??? Corrected stroke order
                    U+7149 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+7155 ??? Corrected stroke order
                    U+717D ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+723C ??? Adjusted position digit 9
                    U+724C ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+727D ??? Fixed stroke order
                    U+7296 ??? Corrected stroke order
                    U+72E0 ??? Corrected stroke order
                    U+730A ??? Corrected stroke order
                    U+7337 ??? Corrected appearence in line with JIS X 0213:2004
                    U+73F1 ??? Corrected stroke order
                    U+7425 ??? Reversed strokes 7 and 8
                    U+7470 ??? Corrected appearence
                    U+74A2 ??? Corrected stroke order
                    U+74F2 ??? Corrected stroke order
                    U+7511 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+751E ??? Improved position of numbering
                    U+754B ??? Corrected stroke order
                    U+7550 ??? Added
                    U+75BC ??? Corrected appearence in line with JIS X 0213:2004
                    U+75FA ??? Improved appearence
                    U+7620 ??? Corrected stroke order
                    U+7627 ??? Corrected stroke order
                    U+7661 ??? Corrected stroke order
                    U+7758 ??? Added
                    U+7768 ??? Corrected stroke order
                    U+77A5 ??? Corrected appearence in line with JIS X 0213:2004
                    U+77DA ??? Corrected stroke order
                    U+78FD ??? Improved position of number 10
                    U+7907 ??? Corrected stroke order
                    U+7941 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+7947 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+79B0 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+79E3 ??? Corrected stroke order
                    U+79E4 ??? Corrected appearence in line with JIS X 0213:2004
                    U+79EC ??? Corrected appearence
                    U+7A0D ??? Corrected stroke order
                    U+7A17 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+7A3B ??? Corrected stroke order
                    U+7A62 ??? Adjusted position of some numbers
                    U+7A63 ??? Improved number spacing for 11 and 12
                    U+7A7F ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+7AC4 ??? Corrected stroke order
                    U+7AC8 ??? Corrected stroke order in line with JIS X 0213:2004
                    U+7ACA ??? Corrected appearence and corrected stroke count to 22
                    U+7B08 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+7BC7 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+7BF6 ??? Corrected stroke order
                    U+7C3E ??? Corrected appearence in line with JIS X 0213:2004
                    U+7C6C ??? Corrected appearence
                    U+7C7E ??? Corrected appearence in line with JIS X 0213:2004
                    U+7CA6 ??? Added
                    U+7CAE ??? Corrected stroke order
                    U+7CC0 ??? Corrected stroke order
                    U+7DBD ??? Corrected stroke order
                    U+7E21 ??? Corrected stroke order
                    U+7E8E ??? Corrected stroke order
                    U+7FDF ??? Added
                    U+7FEB ??? Improved number positions and corrected appearence in line with JIS X 0213:2004
                    U+7FF0 ??? Corrected appearence in line with JIS X 0213:2004
                    U+80D6 ??? Corrected stroke order
                    U+817F ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+81DF ??? Corrected stroke order
                    U+81E7 ??? Corrected stroke order
                    U+8201 ??? Corrected stroke order
                    U+8202 ??? Corrected stroke order
                    U+8205 ??? Corrected stroke order
                    U+820A ??? Corrected stroke order
                    U+821B ??? Corrected stroke order
                    U+8258 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+8271 ??? Corrected stroke order
                    U+8277 ??? Reversed order of strokes 16 and 17
                    U+8292 ??? Corrected appearence in line with JIS X 0213:2004
                    U+82A6 ??? Corrected appearence in line with JIS X 0213:2004
                    U+82E1 ??? Corrected stroke order
                    U+83DF ??? Corrected stroke order
                    U+8479 ??? Reversed order of strokes 10 and 11
                    U+8490 ??? Adjusted position of number for stroke 7 without changing the stroke order
                    U+84D9 ??? Corrected stroke order
                    U+84EC ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+854B ??? Corrected appearence and stroke order
                    U+8588 ??? Adjusted position of some numbers
                    U+85A9 ??? Corrected appearence in line with JIS X 0213:2004
                    U+85AF ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+85F7 ??? Corrected stroke order and appearence in line with JIS X 0213:2004
                    U+86A4 ??? Corrected stroke order
                    U+86F8 ??? Corrected appearence in line with JIS X 0213:2004
                    U+8755 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+877F ??? Corrected position of numeral 6 and improved appearence of number 11
                    U+8782 ??? Corrected stroke order
                    U+87EF ??? Improved position of numbers 11 and 14
                    U+8836 ??? Clarified numbering
                    U+88F2 ??? Corrected stroke order
                    U+8938 ??? Corrected stroke order
                    U+8956 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+8974 ??? Corrected stroke order
                    U+89E7 ??? Corrected stroke order
                    U+8A0A ??? Corrected appearence in line with JIS X 0213:2004
                    U+8A3B ??? Corrected appearence in line with JIS X 0213:2004
                    U+8AB9 ??? Corrected appearence in line with JIS X 0213:2004
                    U+8AC2 ??? Corrected stroke order
                    U+8AFA ??? Corrected appearence in line with JIS X 0213:2004
                    U+8B14 ??? Corrected stroke order
                    U+8B2C ??? Corrected appearence in line with JIS X 0213:2004
                    U+8C50 ??? Reversed order of strokes 16 and 17
                    U+8C79 ??? Corrected appearence in line with JIS X 0213:2004
                    U+8C8E ??? Corrected stroke order
                    U+8CB2 ??? Corrected stroke order
                    U+8D13 ??? Corrected stroke order
                    U+8DA8 ??? Reversed order of strokes 1 and 2.
                    U+8E30 ??? Improved appearence
                    U+8E48 ??? Corrected stroke order
                    U+8F45 ??? Corrected stroke order
                    U+8F61 ??? Corrected stroke order
                    U+8FBB ??? Corrected stroke order and appearence in line with JIS X 0213:2004
                    U+8FBF ??? Corrected stroke order and appearence in line with JIS X 0213:2004
                    U+8FC2 ??? Corrected stroke order and appearence in line with JIS X 0213:2004
                    U+8FC4 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+8FE6 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9017 ??? Corrected stroke order and appearence in line with JIS X 0213:2004
                    U+9019 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9022 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+903C ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9041 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9112 ??? Corrected stroke order
                    U+912D ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9130 ??? Corrected shape and stroke order
                    U+914B ??? Corrected appearence in line with JIS X 0213:2004
                    U+91C6 ??? Swapped strokes 4 and 5
                    U+91C9 ??? Reversed strokes 4 and 5
                    U+91F5 ??? Reversed order of strokes 10 and 11
                    U+9248 ??? Corrected stroke order
                    U+9306 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+939A ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9453 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+95AD ??? Adjusted position of some numbers
                    U+95BB ??? Corrected stroke order
                    U+9677 ??? Corrected stroke order
                    U+9697 ??? Corrected appearence and reversed order of strokes 5 and 6
                    U+9708 ??? Corrected stroke order
                    U+9713 ??? Corrected stroke order
                    U+974D ??? Added
                    U+974F ??? Added
                    U+9768 ??? Corrected stroke order
                    U+9784 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9798 ??? Corrected appearence in line with JIS X 0213:2004
                    U+97DC ??? Corrected stroke order
                    U+97DC ??? Corrected stroke order
                    U+9824 ??? Corrected stroke order
                    U+98F4 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9910 ??? Corrected appearence in line with JIS X 0213:2004
                    U+9912 ??? Corrected stroke order
                    U+9921 ??? Corrected stroke order
                    U+992E ??? Corrected stroke order
                    U+993D ??? Improved appearence
                    U+9957 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9A19 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9A37 ??? Corrected strokes 12 & 13
                    U+9A55 ??? Corrected stroke order by swapping strokes 1 and 2
                    U+9A64 ??? Reversed order of strokes 26 and 27
                    U+9AE2 ??? Corrected stroke order
                    U+9B29 ??? Corrected stroke order
                    U+9B2F ??? Corrected stroke order
                    U+9B43 ??? Adjusted position of some numbers slightly without changing the stroke order
                    U+9B44 ??? Adjusted position of some numbers slightly without changing the stroke order
                    U+9B4D ??? Adjusted position of some numbers slightly without changing the stroke order
                    U+9B4F ??? Adjusted position of some numbers slightly without changing the stroke order
                    U+9B51 ??? Improved positioning of numbers 4 and 5
                    U+9BD6 ??? Corrected appearence and stroke order in line with JIS X 0213:2004
                    U+9BE2 ??? Corrected stroke order
                    U+9C2F ??? Corrected appearence in line with JIS X 0213:2004
                    U+9C52 ??? Corrected appearence in line with JIS X 0213:2004
                    U+9D60 ??? Corrected stroke order and appearence in line with JIS X 0213:2004
                    U+9DBA ??? Corrected stroke order and improved appearence
                    U+9E91 ??? Corrected stroke order
                    U+9E91 ??? Corrected stroke order
                    U+9EA5 ??? Corrected stroke order
                    U+9ED0 ??? Corrected stroke count to 22
                    U+9ED4 ??? Corrected stroke order
                    U+9EE5 ??? Corrected stroke order
                    U+9EF6 ??? Improved appearence
                    U+9F07 ??? Corrected stroke order
                    U+9F08 ??? Corrected stroke order
                    U+9F20 ??? Corrected order of strokes 3 and 4
                    U+9F2C ??? Corrected stroke order
                    U+F9DC ??? Added
                    U+FA10 ??? Added
                    U+FA1F ??? Added
                    U+FA32 ??? Added
                  Other characters:
                    U+2261 ??? Corrected width
                    U+226B ??? Corrected width
                    U+2536 ??? Corrected location within bounding box
                    U+25DD ??? Corrected location within bounding box
                    U+2400-U+2426 Added
                    U+FAFF ???? Version of ??? with stroke 4 starting on the left side,
                           in line with the official Joyo standard. This character
                           is supposed to live at U+20B9F and that is outside of
                           KSOF's encoding space so I have put it in a private use
                           area for users who would like to use this version.
2014/03/18  3.001 Corrected errors reported by users and added a few characters. In detail:
                  U+0126 ?? added Maltese H-bar
                  U+0127 ?? added Maltese h-bar
                  U+01C0 ?? added Nama dental click
                  U+01C1 ?? added Nama lateral click
                  U+01C2 ?? added Nama alveolar click
                  U+058F ?? added Armenian Dram symbol
                  U+20B9 ??? added Indian Rupee symbol
                  U+20BA ??? added Turkish Lira symbol
                  U+2217 ??? added mathematical asterisk operator
                  U+2248 ??? added mathematical almost equal to
                  U+41F3 ??? added new J??y?? character
                  U+4EC2 ??? added
                  U+5099 ??? converted to handwritten version
                  U+529E ??? added
                  U+53F1 ??? corrected to bring into line with J??y?? standard
                  U+55A9 ??? updated to look more like J??y?? standard
                  U+5631 ??? improved placement of stroke order numbers
                  U+5632 ??? updated to look more like J??y?? standard
                  U+5C5E ??? improved placement of stroke order numbers
                  U+67F5 ??? removed unwanted spike from glyph
                  U+6975 ??? changed back to 12 strokes
                  U+6F5F ??? corrected stroke order again
                  U+714E ??? updated to look more like J??y?? standard
                  U+7259 ??? converted to handwritten version, changed stroke count
                  U+7BB8 ??? added dot to bring into line with J??y?? standard
                  U+7C60 ??? improved placement of stroke order numbers
                  U+7DFB ??? improved appearance of glyph
                  U+7E7D ??? improved placement of stroke order numbers
                  U+8877 ??? changed to 10 strokes
                  U+8A6E ??? updated to look more like J??y?? standard
                  U+8CED ??? added dot to bring into line with J??y?? standard
                  U+8EB1 ??? corrected stroke order
                  U+9009 ??? added
                  U+90B8 ??? clarified numbering
                  U+96BE ??? added
                  U+97CB ??? improved appearance
                  U+97D3 ??? updated to look more like J??y?? standard
                  U+9905 ??? corrected to bring into line with J??y?? standard
                  U+990C ??? corrected to bring into line with J??y?? standard
                  U+F981 ??? added CJK compatibility version of 'woman'
                  U+F9D1 ??? added CJK compatibility version of 'six'
2012/05/27  3.000 Added missing Jinmeiyou kanji and miscellaneous other kanji
                  and symbols. Corrected errors reported by users. In detail:
                  U+9B31 ??? corrected order
                  U+9EFD ??? corrected order
                  U+9F9C ??? corrected order
                  U+8805 ??? corrected order
                  U+7E69 ??? corrected order
                  U+9F9D ??? corrected order
                  U+9EA9 ??? extended stroke 6 downwards
                  U+85CF ??? corrected order
                  U+624D ??? corrected appearance
                  U+6F5F ??? corrected order
                  U+8FB6 ??? added controversial fourth stroke back in
                  U+74E7 ??? added missing stroke
                  U+7511 ??? added missing stroke
                  U+74EE ??? corrected order
                  U+74F8 ??? corrected order
                  U+7483 ??? added (controversial) extra stroke
                  U+96E2 ??? added (controversial) extra stroke
                  U+6A8E ??? added (controversial) extra stroke
                  U+79BD ??? added (controversial) extra stroke
                  U+7ACA ??? added (controversial) extra stroke
                  U+9ED0 ??? added (controversial) extra stroke
                  U+753A ??? beautified
                  U+7DFB ??? added extra stroke
                  U+5750 ??? corrected (controversial) stroke order
                  U+632B ??? corrected (controversial) stroke order
                  U+805E ??? beautified
                  U+53D6 ??? beautified
                  U+767A ??? beautified
                  U+31C0 ??? added
                  U+31C1 ??? added
                  U+31C2 ??? added
                  U+31C3 ??? added
                  U+31C4 ??? added
                  U+31C5 ??? added
                  U+31C6 ??? added
                  U+31C7 ??? added
                  U+31C8 ??? added
                  U+31C9 ??? added
                  U+31CA ??? added
                  U+31CB ??? added
                  U+31CC ??? added
                  U+31CD ??? added
                  U+31CE ??? added
                  U+31CF ??? added
                  U+31D0 ??? added
                  U+31D1 ??? added
                  U+31D2 ??? added
                  U+31D3 ??? added
                  U+31D4 ??? added
                  U+31D5 ??? added
                  U+31D6 ??? added
                  U+31D7 ??? added
                  U+31D8 ??? added
                  U+31D9 ??? added
                  U+31DA ??? added
                  U+31DB ??? added
                  U+31DC ??? added
                  U+31DD ??? added
                  U+31DE ??? added
                  U+31DF ??? added
                  U+31E0 ??? added
                  U+31E1 ??? added
                  U+31E2 ??? added
                  U+31E3 ??? added
                  U+9A6C ??? added
                  U+4E44 ??? added
                  U+3514 ??? added
                  U+5861 ??? added
                  U+9830 ??? added
                  U+6B65 ??? added
                  U+6D89 ??? added
                  U+6BCF ??? added
                  U+FA41 ??? added
                  U+FA30 ??? added
                  U+FA45 ??? added
                  U+FA3D ??? added
                  U+FA44 ??? added
                  U+4FF1 ??? added
                  U+4FE0 ??? added
                  U+FA47 ??? added
                  U+FA22 ??? added
                  U+FA5B ??? added
                  U+FA5A ??? added
                  U+FA43 ??? added
                  U+FA5C ??? added
                  U+5DE2 ??? added
                  U+FA4C ??? added
                  U+FA4E ??? added
                  U+FA51 ??? added
                  U+FA19 ??? added
                  U+FA1A ??? added
                  U+FA4D ??? added
                  U+FA4F ??? added
                  U+FA50 ??? added
                  U+FA52 ??? added
                  U+FA53 ??? added
                  U+FA1B ??? added
                  U+FA61 ??? added
                  U+79B1 ??? added
                  U+72C0 ??? added
                  U+90DE ??? added
                  U+FA26 ??? added
                  U+F929 ??? added
                  U+FA64 ??? added
                  U+8CF4 ??? added
                  U+665A ??? added
                  U+FA67 ??? added
                  U+F928 ??? added
                  U+FA48 ??? added
                  U+FA5F ??? added
                  U+FA33 ??? added
                  U+7028 ??? added
                  U+FA55 ??? added
                  U+6DDA ??? added
                  U+F9D0 ??? added
                  U+FA65 ??? added
                  U+589E ??? added
                  U+FA57 ??? added
                  U+FA3F ??? added
                  U+FA37 ??? added
                  U+FA38 ??? added
                  U+537D ??? added
                  U+FA62 ??? added
                  U+FA31 ??? added
                  U+6A6B ??? added
                  U+6EAB ??? added
                  U+6E34 ??? added
                  U+FA69 ??? added
                  U+FA56 ??? added
                  U+FA68 ??? added
                  U+FA63 ??? added
                  U+6B77 ??? added
                  U+66C6 ??? added
                  U+F936 ??? added
                  U+FA54 ??? added
                  U+FA3B ??? added
                  U+FA3A ??? added
                  U+FA34 ??? added
                  U+FA59 ??? added
                  U+7DA0 ??? added
                  U+7DE3 ??? added
                  U+5BEC ??? added
                  U+5FB7 ??? added
                  U+FA40 ??? added
                  U+5FB5 ??? added
                  U+F91D ??? added
                  U+FA4B ??? added
                  U+7DD6 ??? added
                  U+9304 ??? added
                  U+85B0 ??? added
                  U+934A ??? added
                  U+865B ??? added
                  U+64CA ??? added
                  U+7626 ??? added
                  U+63ED ??? added
                  U+7E61 ??? added
                  U+7130 ??? added
                  U+91AC ??? added
                  U+9DD7 ??? added
                  U+FA16 ??? added
                  U+840A ??? added
                  U+6451 ??? added
                  U+985A ??? added
                  U+FA46 ??? added
                  U+541E ??? added
                  U+87EC ??? added
                  U+7C1E ??? added
                  U+7E6B ??? added
                  U+8523 ??? added
                  U+881F ??? added
                  U+FA4A ??? added
                  U+9EB5 ??? added
                  U+5020 ??? added
                  U+34B5 ??? added
                  U+4E37 ??? added
                  U+3031 ??? added
                  U+3032 ??? added
                  U+3033 ??? added
                  U+3034 ??? added
                  U+3035 ??? added
                  U+3018 ??? added
                  U+3019 ??? added
                  U+2022 ??? added
                  U+2023 ??? added
                  U+30A0 ??? added
                  U+2E2E ??? added
                  U+303D ??? added
                  U+303F ??? added
                  U+303E ??? added
                  U+3038 ??? added
                  U+3039 ??? added
                  U+303A ??? added
                  U+5344 ??? added
                  U+3037 ??? added
                  U+303B ??? added
                  U+3030 ??? added
                  U+2460-U+24FF added (circled and parenthesized numbers and
                              letters)
                  U+2150-U+215f added (fractions)
                  U+2160-U+2188 added (Roman numerals)
                  U+2189 ??? added
                  U+2126 ??? added
                  U+2127 ??? added
                  U+213A ??? added
                  U+2141 ??? added
                  U+2100 ??? added
                  U+2101 ??? added
                  U+2104 ??? added
                  U+2105 ??? added
                  U+2106 ??? added
                  U+2109 ??? added
                  U+2116 ??? added
                  U+2117 ??? added
                  U+2120 ??? added
                  U+2121 ??? added
                  U+212A ??? added
                  U+2132 ??? added
                  U+213B ??? added
                  U+2142 ??? added
                  U+2143 ??? added
                  U+2144 ??? added
                  U+214B ??? added
                  U+214D ??? added
                  U+214E ??? added
                  U+2654-2667 added (chess and playing card suits)
                  U+3004 ??? added
                  U+2614 ??? added
                  U+2602 ??? added
                  U+F81A new JIS symbol added as private use character. Can be
                         accessed as ??? with +smcp feature.
                  U+32CF ??? added
                  U+3250 ??? added
                  U+327F ??? added
                  U+2690 ??? added
                  U+2691 ??? added
                  U+26AD ??? added
                  U+26AE ??? added
                  U+26AF ??? added
                  U+26A0 ??? added
                  U+26A1 ??? added
                  U+F81B KPS ACA1 added
                  U+F81C KPS ACA2 added
2011/03/29  2.016 Added Thomas More's Utopian characters (see +utop above) at
                  U+F800 to U+F818. Added Product Integral symbol (see +utop
                  above) at U+F919. Added Sinclair ZX Spectrum block graphics
                  at U+F7F0 to U+F7FF. Added radicals at U+91D2, U+2ECA, U+8A01,
                  U+2EB6, U+2EAA, U+2EB7, U+2EA7, U+2EBB, U+7529, U+9763,
                  U+2EBC. Improved readability of U+9751. Adding missing character
                  glyph at U+0000.
2010/10/05  2.015 Removed one stroke from U+6357, notionally in compliance with
                  JIS X 0213 and the Unicode reference table but actually
                  because someone suggested it. There are many other characters
                  in KSOF that don't match JIS X 0213 but I don't intend to
                  change those; I made an exception for U+6357 because it's slated
                  to become a Joyo kanji. Corrected U+6E90, U+646F, U+7D68,
                  U+8650, U+6F5F, U+6557, U+8FB6 (controversial: it is unclear
                  whether this radical has 3 or 4 strokes). Added the following
                  extra radicals thanks to the generous help of Durand D'souza:
                  U+722B, U+2E99 (an unusual radical), U+6236, U+4E5A, U+725C,
                  U+2F21, U+8980, U+72AD, U+9751, U+6C35, U+9578, U+2EAE,
                  U+8FB5, U+5C23, U+5DDC, U+4E61, U+6237, U+6B7A, U+7CF9, U+8080.
                  Corrected U+718A. Added U+FA35 (variant of U+5351). Corrected
                  U+62C9. Shortened first stroke of U+308A. Shortened U+30FC.
2009/10/04  2.014 Added missing stroke order numbers to U+30EE, U+4EDD, U+9FA0.
2009/08/30  2.013 Changed U+53CE to 4-stroke version. Updated U+5099 with more
                  common version of cliff radical. Clarified U+6163. Corrected
                  U+7CA5, U+8258, U+5396
2008/12/29  2.012 Corrected U+544E, U+9D28, U+6388, U+5D8B
2008/10/01  2.011 Corrected U+9280, U+8607, U+6089, U+6955, U+7566, U+79A6,
                  U+7B08, U+9803, U+86E4, U+88DF. Clarified U+8511.
2008/07/17  2.010 Corrected U+74DC, U+9CE9, U+79BD, U+8DA8, U+82BB, U+50FB,
                  U+4FB6, U+586B, U+5835, U+5C3B, U+63F7, U+64E2. Clarified
                  U+50AD. Thanks once again to Scott Krogh.
2008/01/02: 2.009 Corrected U+76FE, U+8846, U+885B, U+5171. Thanks to Aaron
                  and Scott Krogh for spotting these.
2008/04/04: 2.008 Corrected U+5440, U+5BDE, U+6357, U+6E76, U+74DC, U+7C6C,
                  U+6A8E, U+6A23, U+9244, U+85AC, U+7CDE. Merged in the
                  Choumei v1.10 glyphs, thus providing KanjiStrokeOrders with
                  all the JIS 0208 characters. Added support for small caps.
2008/03/03: 2.007 Corrected U+641C, U+854B, U+6F80, U+83DF, U+5C65, U+65C6,
                  U+6F01, U+750D, U+750E, U+750C, U+7504, U+7503, U+74E9,
                  U+821B, U+74F1, U+5178, U+82E1, U+5BC3, U+9B42, U+6F11,
                  U+5E43, U+91D0, U+74F8, U+74EE, U+74F0, U+74F7, U+7513,
                  U+7505, U+7E4A, U+7515, U+6975, U+64D2, U+79BD, U+6F13,
                  U+6A8E, U+9B51, U+7DFB. Removed glyph list and moved &, ', (,
                  ) and * into their correct encoding slots. Correction from
                  Aaron: U+6E1B.
2008/02/29: 2.006 Corrections from Aaron: U+5EA7, U+51F8. Fixed
                  appearance of many characters and increased the overall
                  size of the glyphs.
2008/02/27: 2.005 More corrections from Scott Krogh: U+6570, U+6551, U+7B20,
                  U+4FC4, U+4F3C, U+74F6, U+629E, U+96EA, U+4E21, U+6E80,
                  U+5EFB, U+5EB6, U+534A, U+7554, U+754F, U+5224, U+5C04,
                  U+8DEF, U+96A3, U+9F62, U+5B9B, U+6028, U+990A, U+8A55.
                  Replaced Tuffy glyphs with those from Choumei, thus making
                  the font more consistent in appearence. Added a list of
                  glyphs provided by the font.
2008/01/14: 2.004 Fixed bugs in U+5BA2, U+843D, U+539F, U+9ED2, U+9B5A, U+5B89,
                  U+6728, U+837B, U+56E0, U+5EAB, U+78E8, U+61BE, U+6545,
                  U+790E, U+96F2, U+8328, U+596E, U+97FB, U+9054, U+5742,
                  U+70AD, U+5897 and U+66DC. Many thanks to the eagle-eyed
                  Scott Krogh for pointing out the errors.
2007/12/13: 2.003 Fixed bug with missing stroke number at U+5144 and adjusted
                  offset of U+4E2D.
2007/05/08: 2.002 Fixed bug whereby hiragana 'mo' was missing.
2007/01/08: 2.001 Improved the character 'n'. Corrected the character U+5E83.
                  Fixed the character spacing.
2006/12/28: 2.0   Greatly expanded with new stroke order diagrams to cover many
                  more kanji, the Latin alphabet, punctuation and some other
                  symbols. This used a fresh set of SVG data from Ulrich Apel.
2006/10/31: 1.01  Corrected the text strings embedded in the font.
2006/10/27: 1.0   Initial revision

ACKNOWLEDGEMENTS
Almost all the work for this font was done by the AAAA and Wadoku projects
under the supervision of Ulrich Apel. I just had the idea of turning the
SVG data into a font and did so. Thanks are due to Scott, Aaron, Paul,
Jeremy, Mifune-san, Gerrit, Brian, Noli, William, Alex, Jerome, Neale,
Nicolas, Przemyslaw, Piotrek, James, Tobias, Jakob, Edgar, Olga, Reinaert,
Mr. Yoon, Meirav, Alfredo, Josh, Sebastian, Samuli, Eugene, Jeff, Gerard,
Inoue-san, Ahmed, Grant, Takao-san, Michael, Kitamura-san, Shibuya-san,
Minh and Herouth for reporting errors in the stroke order data and making
suggestions for improvements. I have fixed all these errors in the current
version. Thanks also to Durand D'souza for doing the background research
on the Kanji radicals I added in version 2.015.

An especially big thank you is due to Toshir??-san, who sent me corrections
for literally hundreds of characters for the V4.0 release.

Please keep the feedback coming; I always welcome corrections and suggestions.

Tim Eyre

mail |at| nihilist (dot) org (dot) uk

