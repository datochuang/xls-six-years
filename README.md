# Six Years of XLS

An interactive 3D tour of [XLS](https://github.com/google/xls), Google's open-source hardware design toolkit, from its release in 2020 to November 2026.

Live page: https://datochuang.github.io/xls-six-years/

Two tracks, switchable at the top of the page:

- **History: people and direction** (8 stations). One bar per contributor, colored by employer at the time; arcs mark a change of employer; arrows mark changes sent back upstream from outside companies. Behind them: the xlsynth side road, the main line that moved three times, commits per year, and each period's direction. The overview station replays the six years as a sequence of events.
- **Concepts: five basics** (5 stations). The translation chain, how the clock sets the stage count, modules and channels with a ready/valid handshake, scheduling many modules as one system, and the fuzzing loop that keeps the translation correct. Each station is hands-on.

## Data

Commit and issue statistics of `google/xls` and `xlsynth/xlsynth`, window 2020-05-13 to 2026-11-19. Contributor affiliation is taken from the author e-mail domain; per-person counts are per account. "Busiest areas" counts commits that touch a directory (one commit can count toward several areas); "bug finding (fuzz)" counts commit subjects that mention fuzz.

## Build

`index.html` is a single static file: Three.js r128 from cdnjs, fonts from Google Fonts, no build step and no backend. It is generated from the source page in a separate assessment repository and copied here. Deep links work: `index.html#s=4` opens station 4.
