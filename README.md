# MuseScore MusicXML project

This project aims to develop MuseScore Studio further into a feature complete MusicXML editor.

## Overview of PRs and new features

You can get a full overview of all connected pull requests that have been opened to [upstream MuseScore Studio](https://github.com/musescore/MuseScore/pulls?q=is%3Apr+author%3Arettinghaus+MusicXML).
You will find more branches in active development on [my fork](https://github.com/rettinghaus/MuseScore).

I also contribute to the [MEI support](https://github.com/musescore/MuseScore/pulls?q=is%3Apr+author%3Arettinghaus+MEI) of MuseScore Studio.

## List of features, improvements, and fixes

### For 3.x [New features from MusicXML 3.1]

* add support for Gould arrow quarter tone accidentals
<https://github.com/musescore/MuseScore/pull/6263>
* add support for all fermata symbols
<https://github.com/musescore/MuseScore/pull/6560>

### For 4.x

* add support for turn with slash
<https://github.com/musescore/MuseScore/pull/17300>
<https://github.com/musescore/MuseScore/pull/27412>
* extended export of key accidentals (e.g. Persian)
<https://github.com/musescore/MuseScore/pull/18540>
* add extended support for colors
<https://github.com/musescore/MuseScore/pull/19132>
<https://github.com/musescore/MuseScore/pull/20952>
<https://github.com/musescore/MuseScore/pull/21433>
<https://github.com/musescore/MuseScore/pull/25893>
<https://github.com/musescore/MuseScore/pull/26006>
<https://github.com/musescore/MuseScore/pull/27384>
<https://github.com/musescore/MuseScore/pull/27571>
* export for all supported SMuFL noteheads
<https://github.com/musescore/MuseScore/pull/19506>
* add support for system dividers and appearance
<https://github.com/musescore/MuseScore/pull/19696>
* add import of fermatas on bar lines
<https://github.com/musescore/MuseScore/pull/20213>
* add support for sostenuto pedal
<https://github.com/musescore/MuseScore/pull/20219>
* fix export of invisible spanners
<https://github.com/musescore/MuseScore/pull/20225>
* extended export of technical elements
<https://github.com/musescore/MuseScore/pull/20252>
* export all available types of trills
<https://github.com/musescore/MuseScore/pull/20285>
* support for group-symbol color and group-barline
<https://github.com/musescore/MuseScore/pull/20952>
<https://github.com/musescore/MuseScore/pull/26006>
* add possibility to export scores in concert pitch
<https://github.com/musescore/MuseScore/pull/21075>
* support for chord symbol color, visibility and placement
<https://github.com/musescore/MuseScore/pull/21362>
* export accidentals on ornaments
<https://github.com/musescore/MuseScore/pull/21364>
* add support for changes between swing and straight rhythms
<https://github.com/musescore/MuseScore/pull/21536>
<https://github.com/musescore/MuseScore/pull/27040>
* add support for invisible lyrics
<https://github.com/musescore/MuseScore/pull/21561>
* export beams starting or ending on rests
<https://github.com/musescore/MuseScore/pull/21602>
* fixed invalid MusicXML with empty figured bass
<https://github.com/musescore/MuseScore/pull/21772>
* add support for harp pedals
<https://github.com/musescore/MuseScore/pull/21828>
<https://github.com/musescore/MuseScore/pull/28169>
* add support for staff sizes
<https://github.com/musescore/MuseScore/pull/22154>
* add support for part-name-display
<https://github.com/musescore/MuseScore/pull/22322>
* improve import of invisible notes
<https://github.com/musescore/MuseScore/pull/22943>
* properly export Nashville numbers and Roman numerals
<https://github.com/musescore/MuseScore/pull/24174>
* export tempo as system text
<https://github.com/musescore/MuseScore/pull/25312>
* export all instrument changes
<https://github.com/musescore/MuseScore/pull/24932>
<https://github.com/musescore/MuseScore/pull/25615>
* extend support of notations
<https://github.com/musescore/MuseScore/pull/25869>
* add full support for Harmon mute symbols
<https://github.com/musescore/MuseScore/pull/25888>
* add support for notehead-text element
<https://github.com/musescore/MuseScore/pull/25916>
<https://github.com/musescore/MuseScore/pull/26911>
* import ornaments as ornament objects
<https://github.com/musescore/MuseScore/pull/25870>
* add full support for holes element
<https://github.com/musescore/MuseScore/pull/25932>
* add full support for hand bells
<https://github.com/musescore/MuseScore/pull/25934>
* add support for single number time signatures
<https://github.com/musescore/MuseScore/pull/26111>
* add support for line styles of slides
<https://github.com/musescore/MuseScore/pull/26559>
* read non-arpeggiate color
<https://github.com/musescore/MuseScore/pull/26773>
* add support for staff line details
<https://github.com/musescore/MuseScore/pull/26472>
<https://github.com/musescore/MuseScore/pull/26856>
* export Bezier points for slurs
<https://github.com/musescore/MuseScore/pull/26568>
* add positioning attributes to breath marks, fingerings and articulations
<https://github.com/musescore/MuseScore/pull/26723>
* extend metadata support
<https://github.com/musescore/MuseScore/pull/26770>
* add guitar golpe and brass half-muted indications to import
<https://github.com/musescore/MuseScore/pull/26771>
* align import and export of natural harmonics glyph
<https://github.com/musescore/MuseScore/pull/26801>
* add support for guitar tap
<https://github.com/musescore/MuseScore/pull/26855>
* full support for hook endings on dashed lines
<https://github.com/musescore/MuseScore/pull/19455>
<https://github.com/musescore/MuseScore/pull/26876>
* export correct bpm for "a tempo" and "tempo primo"
<https://github.com/musescore/MuseScore/pull/26927>
* import feathered beams
<https://github.com/musescore/MuseScore/pull/26990>
* add support for accidental size
<https://github.com/musescore/MuseScore/pull/27387>
* add support for invisible notations
<https://github.com/musescore/MuseScore/pull/27422>
* add import of shake element
<https://github.com/musescore/MuseScore/pull/27426>
* add export of invisible tempo changes
<https://github.com/musescore/MuseScore/pull/27538>
* add support for layout of rehearsal marks
<https://github.com/musescore/MuseScore/pull/27679>
* add limited support of part name color and visibility
<https://github.com/musescore/MuseScore/pull/27843>
* extend semantic encoding of technical symbols
<https://github.com/musescore/MuseScore/pull/27919>
* improve tempo import from Dorico
<https://github.com/musescore/MuseScore/pull/28052>
* allow export of text time signatures
<https://github.com/musescore/MuseScore/pull/28156>
* export tremolo bar symbols
<https://github.com/musescore/MuseScore/pull/28170>
* add support for hairpin style
<https://github.com/musescore/MuseScore/pull/28221>

## list of newly supported elements

* [`<accidental-mark>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/accidental-mark/)
* [`<appearance>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/appearance/)
* [`<concert-score>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/concert-score/appearance/)
* [`<first>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/first/)
* [`<golpe>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/golpe/)
* [`<group-barline>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/group-barline/)
* [`<handbell>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/handbell/)
* [`<harmon-closed>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/harmon-closed/)
* [`<harmon-mute>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/harmon-mute/)
* [`<harp-pedals>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/harp-pedals/)
* [`<hole>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/hole/)
* [`<hole-closed>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/hole-closed/)
* [`<instrument-change>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/instrument-change/)
* [`<line-detail>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/line-detail/)
* [`<line-width>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/line-width/)
* [`<measure-distance>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/measure-distance/)
* [`<measure-layout>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/measure-layout/)
* [`<miscellaneous>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/miscellaneous/)
* [`<mute>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/mute/)
* [`<note-size>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/note-size/)
* [`<notehead-text>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/notehead-text/)
* [`<numeral>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/numeral/)
* [`<numeral-root>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/numeral-root/)
* [`<numeral-alter>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/numeral-alter/)
* [`<part-name-display>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/part-name-display/)
* [`<part-abbreviation-display>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/part-abbreviation-display/)
* [`<play>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/play/)
* [`<second>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/second/)
* [`<staff-size>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/staff-size/)
* [`<straight>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/straight/)
* [`<swing>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/swing/)
* [`<swing-type>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/swing-type/)
* [`<system-dividers>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/system-dividers/)
* [`<with-bar>`](https://www.w3.org/2021/06/musicxml40/musicxml-reference/elements/with-bar/)