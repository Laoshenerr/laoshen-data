# laoshen-data

Static data mirror for `laoshen-library`.

- `library-head.json` — newest 300 entries, used for first paint (~26 KB gzip)
- `library.json` — full index (14887 books, list fields only, no book text)
- `build-version.json` — build stamp used for cache busting

This repository contains **book index metadata only** (title / author / tags / dates).
No book text is stored here. Text is served by the main site.

If you are a rights holder and want something removed, open an issue and it will be deleted.
