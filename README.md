# University of Cologne Japanese Studies Zotero Citation Style

This is a Zotero citation style `.csl` file for use by students at the department of Japanese Studies at the Institute for East Asian Studies, University of Cologne. It aims to implement all specific formatting instructions as laid out it https://japanologie.phil-fak.uni-koeln.de/sites/ostas/japanologie/Wissenschaftliches\_Arbeiten/Richtlinien-Wiss-Arbeiten-2023\_bearbeitet.pdf (German, last accessed 2025-09-06) correctly. This is an independent student project and not affiliated with the Institute of East Asian studies in any way.

**Caution: The citation style is not yet complete or well-tested.** While academic works (i.e. books, journal articles and book chapters) are more or less fully implemented, all other types of citations (such as films, internet sources) either don't work at all or are mostly untested. **Always double-check the generated bibliography!** Contributions and feedback are welcome.

## Installation

The `.csl` file can be downloaded and added to Zotero using `Bearbeiten > Einstellungen > Zitieren > +`. Once completed, the citation style will also be uploaded to the Zotero Style Repository. 

## Usage

### Kanji for Japanese works

In general, Japanese symbols can be appended to the respective field, for example: Author's full name in kanji after transcribed first name, such as `Yamato, Nadeshiko 大和撫子`. This is also true for article titles, and most fields in general.

Book titles and journal names are formatted *in cursive*. Japanese symbols should **never** be cursive. Therefore, don't append kanji after the transcription of book titles and journal titles. Instead, add the following to the `Extra` section at the bottom:

```
original-title: [Title in kanji]
```

That way, all kanji should be displayed correctly. Note: The `original-title` field refers to the *book title*, not the chapter title, when a single chapter is cited.

### In-text citations

In-text citations should be in footnotes. The footnotes themselves have to be added manually, but the citations can be inserted into the footnote the usual way through the Zotero plugin. The full bibliography entry is displayed for the first citation, subsequent citations are generated as `AUTHOR: TITLE [KANJI-TITLE], S. PAGE`. 

## License
This citation style is published under the Creative Commons Attribution-ShareAlike 3.0 Unported license, obtainable from https://creativecommons.org/licenses/by-sa/3.0/. It is originally based on the APSA citation style for Zotero by Julian Onions et al. (http://www.zotero.org/styles/american-political-science-association), also published under the CC-BY-SA 3.0, though most of it has been replaced.
