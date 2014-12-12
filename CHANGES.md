
Fira is a trademark of The Mozilla Corporation.

Digitized data copyright © 2012-2014, The Mozilla Foundation and Telefonica S.A.

Design: Carrois Corporate GbR & Edenspiekermann AG

--------------------

Note:

All weights below "Thin" should be seen as an experiment by now.
They will be optimized within the coming versions.
Same applies to "Ultra".


Fira font weights:

| Weight     | EM    | CSS weight |
| ---------- | -----:| ----------:|
| Two        | 2em   | 20         |
| Four       | 4em   | 40         |
| Six        | 6em   | 60         |
| Eight      | 8em   | 80         |
| Hair       | 14em  | 100        |
| Thin       | 22em  | 150        |
| UltraLight | 34em  | 200        |
| ExtraLight | 46em  | 250        |
| Light      | 58em  | 300        |
| Book       | 84em  | 350        |
| Regular    | 92em  | 400        |
| Medium     | 128em | 500        |
| SemiBold   | 142em | 600        |
| Bold       | 158em | 700        |
| ExtraBold  | 178em | 800        |
| Heavy      | 198em | 900        |
| Ultra      | 222em | 950        |

--------------------

### Version/Build 3.111

- TTFautohint via Glyphs 2 developer Beta GUI for TTF export
- fixed zero width glyphs with no zero value in Italic
   * PDFs stay version 3110, just renamed the zip-folder


### Version/Build 3.110

- fixed TTF/WOFF/EOT in Mono export error caused by database divergence Glyphs2 Beta
- fixed interpolation glitches coming with new behavior of anchors in Glyphs2 Beta
- fixed zero width glyphs with no zero value in Mono
- legibility improvement for code applications: braces, brackets and parens in Mono


### Version/Build 3.109

- mozilla/Fira#43
   * impossible to get equal values for all OS issues with common methods.
- catch:
   * set typoLineGap to 400 (was 200)
   * set winDescender to -350 (was -500)
- **Known bug**: cuts of lowest glyphs (-353 Ultra)
   * Arabic (should not become lower)
   * Vietnamese (should not become higher)


### Version/Build 3.108

- NEW Mono Medium weight
- added style linking for all weights and styles
- panose information for single weights
- Italic: uni0414 De-cyr in upright shape – commissioned by mozilla, but handwritten shape will come back with Bulgarian and Serbian localized feature in 3.2 :wink:
- zip-archives without Mac-Resources

### Version/Build 3.107

- **line spacing**
- added “Use Typo Metrics” to sfSelection in OS/2 table
   * OS/2 table and bbox size are equal to Fira 1.4 and 2.1
   * If you have any issues with increased linespacing, make sure your render engine and/or software application DOES read the OS/2 table based information and/or the bbox size.
- panose information added to OS/2 table
- uni0400 & uni0450 (small & capital/sc cyrillic i with grave – Bulgarian/Macedonian)
- uni040D & uni045D (small & capital/sc cyrillic i with grave – Bulgarian/Macedonian)
- Mono: now set as isFixedPitch
- Mono: asterisk * uni002A now on x-height and a little bit larger
- fixed interpolation glitches
- New grid export parameters for Two, Four, Eight and Hair
- UFO source files instead of Glyphs-files

### Version/Build 3.106

- aogonec uni0105 (`>`) nicer connection
- outline corrections concerning some interpolation glitches
- web font formats added (beta version only)

### Version/Build 3.105-lhmod *(unofficial)*

- Correct Mono line-height on OS X

### Version/Build 3.105

- smaller kerning issues
- minor outline corrections concerning interpolation issues
- T cedilla centered in Mono

### Version/Build  3.104

_ smaller kerning issues
_ all Bold weights from 160 to 158 (better results with hinting)
_ j Mono: wider shape
_ g Mono: equal style to Sans now (lower terminal)


### Version/Build 3.103

- auto linespacing fixed (equal to Fira2.x)
- ligature feature set to ‚dliv’ in Mono faces
- new shape for J in Mono faces
- fixed hinting bug in heavy weights
- fixed hcircumflex accent position in lighter weights
- adding SmallCaps for free valuation service: adding as much composites as possible via Glyph 1.4.4 database from 3.001


### Version/Build 3.102

- improved for el-cyrillic / all cases л Л л.sc
- improved shape for alpha α, pi π, tau τ
- minor kerning issues for punctuation
- minor spacing issues


### Version/Build 3.101

- no more empty glyphs in CYR


### Version/Build 3.100

! all new Italic !
! all new SmallCaps !

- mark feature for combining accents
- new bbox
- new family zones
- UC 0313 and 0314 added
- UC 2205 added
- similar shape for ampersand Italic and Upright
- more common greek as mentioned in Deu. 2013
- new shape cyrillic я (ia) lowercase
- possibility of a stylistic set for /beta /zeta /sigma (ss10)
- restored combing accents
- no more hard ink-traps in M N 3 and relatives
- fixed interpolation difficulties Cyrillic
- added lost mu to Greek
- improved kerning
- new shape for ogonek
- improved connection of ogonek to e and U
- fixed witdth .tf .tosf
- removed figurespace form .tf and .tosf

### Version/Build 3.002

- improved kerning
- overlap crash fi lig fixed
- Unicode Ranges rebuilt by Glyphs2Beta via makeOTF
- removed helping glyphs from cyrillic part

### Version/Build 3.001

- first Beta
