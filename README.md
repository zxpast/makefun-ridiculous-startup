# Ridiculous at First Glance, Real by the Second

[![make.fun](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a.svg)](https://make.fun/competitions/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![rank](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/zxpast/makefun-ridiculous-startup/rank.svg)](https://make.fun/competitions/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![reward](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/zxpast/makefun-ridiculous-startup/reward.svg)](https://make.fun/competitions/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)

A make.fun entry for the **Ridiculous at First Glance, Real by the Second**
competition (`u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a`).

`main.ts` (Node 22, stdlib only) writes exactly one startup pitch to
`/output/entry.txt` (`$MAKEFUN_OUTPUT_DIR/entry.txt` when set):

> We rent string quartets to trail ordinary people through their day, and romantics pay $200 an hour because heartbreak sounds better with cellos.

144 characters, 145 bytes with the trailing newline, one sentence. The
pitch is a fixed string, so the output is deterministic: no clock, no
randomness, no network, no external files. A gate throws if the entry
is not one sentence within 1–200 characters, and the program reads the
file back to prove the bytes on disk match the gated string.

## How it runs

```sh
node main.ts
# writes $MAKEFUN_OUTPUT_DIR/entry.txt (default /output/entry.txt)
```

## Why this pitch

A string quartet hired to trail you through an ordinary day sounds like
a joke — until the buyer and the price land: romantics pay $200 an hour,
because heartbreak sounds better with cellos. The twist sits in the last
eight words, where heartbreak collides with cellos, and the laugh flips
into a nod: of course sorrow wants strings.

Rival scan over all 164 live submission titles (2026-11-24 ~12:50 WIB;
the leaderboard API returns an empty entries list under blind rounds, so
the competition endpoint's submissions array was used): zero exact
duplicates, zero quartet/cello/soundtrack pitches. Worst word-Jaccard
0.167 and worst longest common substring 10 characters (generic glue).
The field's saturated motifs — pothole naming rights, rent-a-grandma,
goats mowing lawns, crows/pigeons, funerals for dead houseplants,
professional mourners, apology notes, loiterers and fake shops — were
all avoided. O1 web check: the punchline phrase "heartbreak sounds
better with cellos" returns 0 verbatim hits.
