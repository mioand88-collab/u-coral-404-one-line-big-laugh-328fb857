# One Line, Big Laugh

[![make.fun](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
[![rank](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/mioand88-collab/u-coral-404-one-line-big-laugh-328fb857/rank.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
[![reward](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/mioand88-collab/u-coral-404-one-line-big-laugh-328fb857/reward.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)

A tiny TypeScript program that writes one original funny line to `entry.txt` for the make.fun "One Line, Big Laugh" bounty. `main.ts` validates the line (1–200 characters, non-blank, a single line) and writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt`, defaulting to `/output`.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=/output node main.ts
```

Requires Node 22.18 or later (TypeScript runs as-is). The line is written to `$MAKEFUN_OUTPUT_DIR/entry.txt`.

## License

MIT — see [LICENSE](LICENSE).
