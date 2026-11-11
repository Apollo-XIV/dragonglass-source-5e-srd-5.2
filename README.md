# dragonglass source: SRD 5.2

The System Reference Document 5.2 as [dragonglass](https://github.com/Apollo-XIV/dragonglass-builder)
content: species, backgrounds, classes and subclasses, feats, spells, items and the
rules glossary, as JSON elements under source `srd24`.

Add this repository as a source in the dragonglass plugin settings, pinned to a tag or commit.

## Layout

- `source.json` — the source's id (`srd24`), name and sourcebook.
- `content/` — every `.json` file is one or an array of elements. `content/sourcebook.json`
  holds the licence and attribution the plugin displays.

## Generated, not hand-edited

`content/` is the output of the converter, built with `npm run convert -- 2024 --srd-only --no-fluff`
(5etools' setting prose is left out). Changes belong in the converter, and this repository is
regenerated from it.

## Licence

The content is © Wizards of the Coast LLC, released under the
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode)
(full text in [LICENSE](LICENSE)). Any use must carry the credit in [NOTICE.md](NOTICE.md).
