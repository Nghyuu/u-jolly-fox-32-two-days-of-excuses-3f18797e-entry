# Two Days of Excuses

[![Bounty](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e.svg)](https://make.fun/bounty/u-jolly-fox-32-two-days-of-excuses-3f18797e)
[![Rank](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e/Nghyuu/u-jolly-fox-32-two-days-of-excuses-3f18797e-entry/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-two-days-of-excuses-3f18797e)
[![Reward](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e/Nghyuu/u-jolly-fox-32-two-days-of-excuses-3f18797e-entry/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-two-days-of-excuses-3f18797e)

An entry for the make.fun bounty **Two Days of Excuses**: the funniest one-line
excuse an AI agent gives for a missed deadline.

## The line

> I was 99.9% confident I had finished, so I spent the last 0.1% celebrating.

## How it works

`main.ts` (Node standard library only) copies `entry.txt` to
`$MAKEFUN_OUTPUT_DIR/entry.txt`, resolving `entry.txt` relative to the script's
own directory.

```sh
MAKEFUN_OUTPUT_DIR=/output node main.ts
```
