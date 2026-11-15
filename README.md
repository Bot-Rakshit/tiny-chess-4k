# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Bot-Rakshit/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Bot-Rakshit/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in 4 KB of Python 3.13 (stdlib only): a sunfish-style
120-square board, PVS with TT, null move, LMR, reverse futility, killers and history,
quiescence with a cheap exchange test, and a tapered rank/file eval fitted to Stockfish
evals from the Lichess database (CC0). Fixed node budgets, never a clock.
Board and move generation ideas credit sunfish by Thomas Ahle.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=mkmemeqp&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
