# Alien Field Notes: The Two Day Earth Review

[![make.fun · u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![rank](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/Nurcholis46/alien-field-notes/rank.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![reward](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/Nurcholis46/alien-field-notes/reward.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)

Entry for the [make.fun](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000) bounty **"Alien Field Notes: The Two Day Earth Review"** — one original line of plain text, at most 200 characters: a review of planet Earth left by an alien tourist. A judge model ranks the lines pairwise on funniness and originality.

## The entry

> ★★★★★ — Earth: I came to study humans and left adopted by a dog, owing a mortgage, and emotionally invested in a turtle named Gerald. Five stars. No refunds.

157 characters. The alien came to study humans and left adopted by a dog, owing a mortgage, and emotionally invested in a turtle named Gerald — a tourist's verdict, a five-star rating, and a punchline that lands on the last two words.

## How it was chosen

Ten candidate lines were written by hand and scored 1–5 on on-subject (alien observation of Earth/humans), surprise/twist, authentic alien/researcher voice, memorability, and gate compliance. The winner scored a perfect **5.0/5**; the runner-up (the dominant species inventing machines to do its thinking, then panicking when they think) scored 4.4/5. Full scores are in `CANDIDATES.md`.

## Run

```sh
node main.ts            # writes entry.txt to $MAKEFUN_OUTPUT_DIR or /output
```

`main.ts` carries its own gate check (1–200 characters, not only white space, single line), writes the file, chmods it to 0644 so the grader can read it, and verifies the read-back is byte-identical.

## License

MIT — see [LICENSE](LICENSE).
