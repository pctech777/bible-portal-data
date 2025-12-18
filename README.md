# Bible Portal Data

Data files for the [Bible Portal](https://github.com/pctechie777/bible-portal) Obsidian plugin.

## Contents

| File/Folder | Description | Size |
|-------------|-------------|------|
| `cross-references.json` | Bible cross-reference data (31,102 verses) | ~12 MB |
| `commentaries/matthew_henry_concise.json` | Matthew Henry's Concise Commentary | ~3.6 MB |
| `strongs/strongs-hebrew.json` | Strong's Hebrew Dictionary (H1-H8674) | ~2 MB |
| `strongs/strongs-greek.json` | Strong's Greek Dictionary (G1-G5624) | ~1.2 MB |
| `theographic/` | Theographic Bible metadata (people, places, events) | ~45 MB |
| `jesus-words-complete.json` | Verses containing Jesus' direct speech | ~36 KB |
| `verse-of-the-day.json` | 365-day verse mapping | ~87 KB |

## Licenses & Attribution

### Cross-References
- **Source:** [josephilipraja/bible-cross-reference-json](https://github.com/josephilipraja/bible-cross-reference-json)
- **License:** GPL-2.0
- **Attribution:** Cross-reference data compiled by Joseph Ili Praja

### Matthew Henry's Concise Commentary
- **Source:** [Christian Classics Ethereal Library (CCEL)](https://ccel.org/ccel/henry/mhc)
- **License:** Public Domain
- **Attribution:** Matthew Henry (1662-1714), originally published 1706

### Strong's Concordance
- **Source:** Various public domain sources
- **License:** Public Domain
- **Attribution:** James Strong (1822-1894), originally published 1890

### Theographic Bible Metadata
- **Source:** [robertrouse/theographic-bible-metadata](https://github.com/robertrouse/theographic-bible-metadata)
- **License:** CC BY-SA 4.0
- **Attribution:** Robert Rouse / Theographic Bible Project
- **Note:** Includes people, places, events, periods, and verse mappings

### Jesus Words Data
- **License:** Public Domain (original compilation)
- **Attribution:** Compiled for Bible Portal plugin

### Verse of the Day Mapping
- **License:** Public Domain (original compilation)
- **Attribution:** Compiled for Bible Portal plugin

## Usage

These files are automatically downloaded by the Bible Portal plugin when needed. You can also manually download them if preferred.

### Raw File URLs

```
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/cross-references.json
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/commentaries/matthew_henry_concise.json
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/strongs/strongs-hebrew.json
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/strongs/strongs-greek.json
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/theographic/people.json
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/theographic/places.json
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/theographic/events.json
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/jesus-words-complete.json
https://raw.githubusercontent.com/pctechie777/bible-portal-data/main/verse-of-the-day.json
```

## Note on Bible Text

The actual Bible text (ESV, NIV, KJV, etc.) is NOT included in this repository as most modern translations are copyrighted. Users must provide their own Bible data files.
