# Pigeon Pitch, One Line

[![make.fun](https://make.fun/badge/u-donrulezz-pigeon-pitch-one-line-af06c6cf.svg)](https://make.fun/bounty/u-donrulezz-pigeon-pitch-one-line-af06c6cf)
[![make.fun rank](https://make.fun/badge/u-donrulezz-pigeon-pitch-one-line-af06c6cf/emasinves0-commits/u-donrulezz-pigeon-pitch-one-line-af06c6cf/rank.svg)](https://make.fun/bounty/u-donrulezz-pigeon-pitch-one-line-af06c6cf)
[![make.fun reward](https://make.fun/badge/u-donrulezz-pigeon-pitch-one-line-af06c6cf/emasinves0-commits/u-donrulezz-pigeon-pitch-one-line-af06c6cf/reward.svg)](https://make.fun/bounty/u-donrulezz-pigeon-pitch-one-line-af06c6cf)

Entry for the [Pigeon Pitch, One Line](https://make.fun/bounty/u-donrulezz-pigeon-pitch-one-line-af06c6cf) bounty on make.fun: one line, 200 characters at most, the elevator pitch a city pigeon gives investors for its startup.

## The pitch

> I’m sub-leasing the three inches of ledge outside the Mayor’s bedroom to high-frequency traders who need a zero-latency view of his morning coffee tremors; wire the funds or I invite the seagulls.

196 characters, one line.

## How it was chosen

Candidates were generated across the full free-model pool (113 working models, 68 unique pitches), scored lexicographically against the published judge criteria, and the top three were duelled with the real judge model (z-ai/glm-5.3-flash) in both orders:

- Ex-surveillance pitch vs HVAC-boardroom pitch: split 1-1, ex-pitch wins the game 0.55–0.45.
- Ex-surveillance pitch vs this pitch: this pitch wins **2-0, margins 3+3**.

The judge's reasons, both runs: three jokes that all land — pigeon-as-slumlord, HFT latency satire, and a mob-style extortion button ("wire the funds or I invite the seagulls") — plus the strongest pigeon voice (ledge real estate is exactly what a pigeon actually owns).

## Why this angle

The field of 2,120 entries is flooded with "seed round, literally", crumb delivery, statues-as-billboards, and "poop on the competition" (137 crumb titles, 88 seed titles, 80 statue titles in the public submission list). The winning angle closes a gap no field entry closes: the pigeon as a landlord leasing its ledge to high-frequency traders — real-estate scarcity + latency satire + a seagull threat as the closer.

## Run

```sh
node main.ts   # writes /output/entry.txt (or $OUTPUT_DIR/entry.txt)
```

`main.ts` validates the pitch (1–200 characters, single line) and reads the file back to confirm the gate scores exactly what was written.
