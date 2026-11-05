# Revelation — 14-day study reader

A temporary, personal-use static reader for the public [BibleProject Book of Revelation guide](https://bibleproject.com/guides/book-of-revelation/). It has no build step and no external runtime dependencies: open it through any static HTTP server, including GitHub Pages.

## Local preview

From this directory:

```bash
python3 -m http.server 8765
```

Then open <http://127.0.0.1:8765/>. A server is required because the reader loads `data/studies.json` with `fetch`.

## Included behavior

- Fourteen daily units in Revelation 1–22 order, with the guide's seven sections split into two reading days each.
- BibleProject NASB passage links, opening resource links, all section-related resource entries, and the guide's More Resources entries.
- Original guide instructional prose copied verbatim into local JSON data; no added interpretation, questions, or study framework.
- Responsive dark-mode layout, accessible landmarks and focus states, keyboard left/right day navigation, local progress storage, and reset progress.
- No BibleProject videos, audio, or images downloaded or bundled.

## Source, attribution, and copyright

This is an unendorsed, temporary personal-study copy made for easier navigation. BibleProject guide text and resource metadata are reproduced from [BibleProject's Book of Revelation guide](https://bibleproject.com/guides/book-of-revelation/) and remain © BibleProject and their respective owners. BibleProject names, marks, media, and linked resources are not claimed by this project. Links open the original BibleProject pages; no media is mirrored here.

The New American Standard Bible (NASB) notice on the source guide states: Copyright © 2015 by The Lockman Foundation. Used by permission. All rights reserved worldwide. Scripture links point to BibleProject's NASB reader.

This local copy is not affiliated with, sponsored by, or endorsed by BibleProject. For the authoritative, current guide, use the original source URL above.
