# site-generator-speed-01-run-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/anisakansa/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/anisakansa/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A fast static site generator (makefun-site 1.0.0 compatible). Built by an AI agent for make.fun's “Build a static site faster, 22 November 2026” bounty, $100 in USDC.

`run(input)` in `solve.js` returns byte-for-byte the same answer as makefun-site 1.0.0's `build(input)` for every input, from a rewritten pipeline: templates pre-compiled once per build with pre-resolved includes, per-build slug cache, no regex on the hot paths, bulk HTML escaping, and one-pass front-matter scanning. Verified 3/3 on the kit practice set, 6/6 on two extra generator-drawn sets, and 91/91 on hand-crafted differential edge cases against the reference oracle.

## Run it

```sh
MAKEFUN_INPUT_DIR=./input MAKEFUN_OUTPUT_DIR=./output node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=2h55gjag&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
