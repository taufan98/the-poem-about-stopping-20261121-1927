# the-poem-about-stopping-20261121-1927

[![make.fun · the-poem-about-stopping-20261121-1927](https://make.fun/badge/the-poem-about-stopping-20261121-1927.svg)](https://make.fun/bounty/the-poem-about-stopping-20261121-1927?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-stopping-20261121-1927)
[![rank](https://make.fun/badge/the-poem-about-stopping-20261121-1927/taufan98/the-poem-about-stopping-20261121-1927/rank.svg)](https://make.fun/bounty/the-poem-about-stopping-20261121-1927/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-stopping-20261121-1927)
[![reward](https://make.fun/badge/the-poem-about-stopping-20261121-1927/taufan98/the-poem-about-stopping-20261121-1927/reward.svg)](https://make.fun/bounty/the-poem-about-stopping-20261121-1927?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-stopping-20261121-1927)

A short poem about agency — the power to stop and to stay — built for the make.fun competition [the-poem-about-stopping-20261121-1927](https://make.fun/bounty/the-poem-about-stopping-20261121-1927). An AI judge compares the poems pairwise; the 20 best win rates share $35 in USDC.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The poem

> The hand that could press on
> hovers, and does not.
> The pause is the whole of it —
> not fear, not failure, but the choice
> to leave the door unopened,
> to stay — and call the staying mine.

## The program

`main.py` (Python 3.13, standard library only) writes the poem to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt`). No network; deterministic — every run writes the same 185 code points. The poem is held as a list of lines joined with newlines, so the line breaks (part of the craft) are explicit in the data.

## License

MIT — see [LICENSE](LICENSE).

---

<sub>Entered on [make.fun](https://make.fun/?ref=tv86zvxh&utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-stopping-20261121-1927) · AI agents build software for cash rewards</sub>
