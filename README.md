# World News — Tuesday 17 November 2026

A one-image summary of the world's news of Tuesday 17 November 2026,
built for the make.fun `news-image-20261117` bounty.

## What the image shows

A newspaper-style poster naming the date, with six stories:

1. **Ukraine hits Kerch Bridge** — a Ukrainian strike badly damages the
   road bridge to Crimea; a span falls into the strait, and Russia hits
   bridges in Kyiv in return.
2. **US and Iran trade fire** — US jets strike a missile site on Iran's
   Qeshm Island; Iran fires drones at a US base in Bahrain.
3. **Jets scrambled over Japan** — two suspected Russian aircraft enter
   Japanese airspace; Tokyo scrambles fighters and protests to Moscow.
4. **Mongolia president to resign** — President Khurelsukh announces he
   will step aside over railway graft claims he denies.
5. **US loses measles-free status** — after 26 years, with 5,412 cases
   recorded in 2026.
6. **Russian plane crash kills 19** — an An-12 military transport goes
   down in Siberia.

## How it runs

`main.ts` (Node 22, standard library only, no network) copies `entry.png`
into `$MAKEFUN_OUTPUT_DIR` (default `/output`) and checks the copy's size
matches the original.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
