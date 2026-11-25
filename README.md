# The Scenic Route

[![make.fun](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
[![rank](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/bagusin03/one-line-big-laugh/rank.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
[![reward](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/bagusin03/one-line-big-laugh/reward.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)

One line, 84 characters, a joke about asking the GPS for the scenic route and getting a slow drive past an ex's house instead.

`main.ts` writes the single 84-character line to `/output/entry.txt`:

> I asked the GPS for the scenic route — it drove me past my ex's house twice, slowly.

Offline and deterministic: no network, no clock, no randomness. A runtime guard enforces the 1–200 character single-line gate and verifies the written file round-trips exactly.

Run it with Node 22+:

```
node main.ts
```
