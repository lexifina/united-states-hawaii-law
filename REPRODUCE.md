# How this repository was made (United States (Hawaii))

This file is written by the build on 2026-10-30, the day the source data was retrieved.

## Sources

| Source | Address | Retrieved | Licence |
| --- | --- | --- | --- |
| Hawaii Legislative Reference Bureau, State Constitution | <https://lrb.hawaii.gov/constitution/> | 2026-10-30 | Public constitutional text; the site footer reserves rights in the LRB pages, not in the law |

Every word of law in this repository comes from these sources. Lexifina reads them and records each act's dated versions, and the laws that made each change, in one corpus file. This repository is built from that file.

## What is in it

| Act | Title | Versions | Span |
| --- | --- | ---: | --- |
| `constitution` | Constitution of the State of Hawaii | 1 | 2026-10-30 to 2026-10-30 |

The build made 1 commits:

| Commits | Kind |
| ---: | --- |
| 1 | first version of an act |
| 0 | one law on its in-force day |
| 0 | changes no amendment note explains, credited to the publisher |

Other counts:
- 0 commits on the branch `future`: laws not yet in force on 2026-10-30.
- 0 commits dated 1 January 1970: in force before 1970, with the real day in their `In-force` trailer.
- 1 laws in the record.
- 1 tags.

## Dates

Each commit is dated at noon (Pacific/Honolulu) on the day the change took effect. The other dates, enacted and published, are trailers.

When a law gives no date of its own, the default rule applies: No dated history is published: the text is the oldest version available, dated from the retrieval day. https://lrb.hawaii.gov/constitution/

## How the history is built

`tools/build.py` turns the corpus into this history in one pass: one commit per law, on the day it took effect. The same corpus always gives the same commit hashes. `tools/check_repo.py` reads every version back from git and compares it with the corpus. `tools/on.py` shows the law as it stood on any date. The corpus format is described in `tools/SCHEMA.md`.

- Corpus: sha256 `3c64ec0b7785481dffee12cecc189bbd6288a43185a0ad40ebb0ca0be0f87d8c` (135092 bytes).
- Builder blob hashes (`git hash-object`): `build.py` `a4faa25af85facb64b956b372f6b528aafdd7ec1`, `check.py` `3e59cb6f05eccb94a9ec14431a7f6781221e83ef`, `on.py` `644a6c0857fbcc72562032b58d57aa113fee0641`.
- Python 3.12.10; git version 2.46.0.windows.1.

## Checks

Not yet run for this build.

No second build of this corpus has been compared yet.

## Decisions made by hand

- English only. First build: the State Constitution only.
- One version, "oldest version available", dated from the retrieval day and credited to the publisher.
- Bracketed source notes after each section and the revision note are not kept; section captions become part of the heading line.

## What AI did and did not do

The scripts that read the sources and build this repository were written by Claude Code running Claude Opus 5.5 (`claude-opus-5-5`) under Lexifina's direction.

No model wrote, translated or corrected legal text. No model runs at build time. Every word of law in this repository comes from the official sources above.

The commit messages are written by `build.py` from the source data.

Model use at data-build time:
- none (scripts only; no model wrote or altered legal text)
