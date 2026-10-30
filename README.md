# United States (Hawaii): law history in git

A first build of Hawaii law as git: one file per provision, with the text published by the Hawaii Legislative Reference Bureau ([lrb.hawaii.gov](https://lrb.hawaii.gov/constitution/)). It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `united-states/hawaii/`. Language: English.

**What is in it now**

| Folder | Law | Versions | History |
| --- | --- | ---: | --- |
| `constitution/` | Constitution of the State of Hawaii (1950, as amended) | 1 | Oldest version available (retrieved 2026-10-30) |

## What it does not show

- **Past versions.** The Bureau publishes the current Constitution only. Each text therefore has one commit, "oldest version available", credited to the publisher and dated by the retrieval day.
- **Notes.** Source notes, histories and annotations are not law text and are not in the files.

## How it is checked

Every version names its source and the sha256 of the data it was read from. Each version is read back from git and must match `corpus.json` (`tools/check_repo.py`); the results are in `REPRODUCE.md`.

## Sources

| Source | Kind | Past versions | Licence |
| --- | --- | --- | --- |
| [the Hawaii Legislative Reference Bureau](https://lrb.hawaii.gov/constitution/) | Official publisher | no | Law text is not copyrightable (Georgia v. Public.Resource.Org, 2020) |

## Licence

See `LICENSE`. This repository is not legal advice and not an official publication.
