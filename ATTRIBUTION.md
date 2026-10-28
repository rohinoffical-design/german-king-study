# Data attribution and license

The vocabulary data in `vocabulary.js` is a derivative dataset shared under **CC BY-SA 4.0**. Keep this attribution and the included `LICENSE-CC-BY-SA-4.0.txt` with the data when you redistribute the site.

## Sources

- **German lemmas, frequency rank, parts of speech, CEFR estimates, noun gender, inflections, and verb forms:** [wordhoard 0.1.0](https://github.com/natema/wordhoard), using its German release data. The Wordhoard dataset is CC BY-SA 4.0. Its attribution notice is preserved in [NOTICE-wordhoard.md](NOTICE-wordhoard.md).
- **English glosses:** [Lector's German dictionary](https://lector.dev/free/german-dictionary/), release `dict-de-2026-06-25`, derived from Wiktionary content through Kaikki. The dictionary data is CC BY-SA 4.0.
- **Curated A1/A2 entries:** additional learner-friendly translations, plural labels, conjugations, and example sentences prepared for German King.

The built library contains 100,000 unique translated headwords. It includes 30,774 frequency-ranked Wordhoard entries with estimated CEFR labels and 69,226 additional Lector dictionary headwords marked `Reference`; those reference entries are not assigned a CEFR level. CEFR estimates are not an official Goethe-Institut exam syllabus. The included A1/A2 examples are a focused study set, and reference entries may have fewer grammar details when the source does not provide them.

Wordhoard's data notice also attributes Wiktionary contributors, OpenSubtitles frequency lists via FrequencyWords, and spaCy; see the preserved notice. Lector's source database is attributed to Wiktionary contributors through Kaikki. No Goethe-Institut list text is redistributed.

## License

This combined vocabulary dataset is distributed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). The site code is separate from the vocabulary dataset.
