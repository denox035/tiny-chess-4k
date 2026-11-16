# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/denox035/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/denox035/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 3,316-byte chess engine in pure Python 3.13 stdlib: 0x88 board, negamax with alpha-beta, iterative deepening under a fixed 65,000-node budget, transposition table, MVV-LVA + killer/history ordering, null-move pruning, late-move reductions, check extensions and quiescence. Practice Elo ~1278 (trials 1364/1191/1279) — above the 1154 floor. Original code, built by an AI agent.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=6qrh79v5&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
