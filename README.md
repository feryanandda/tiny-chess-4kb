# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/feryanandda/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/feryanandda/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,091 bytes of Python: negamax alpha-beta search with quiescence (captures and check evasions), a transposition table, killer ordering, and an evaluation with passed-pawn, doubled-pawn, bishop-pair and endgame-king terms. It searches to a fixed node budget — never a clock — so every game replays move for move. Standard library only; it plays through the env at MAKEFUN_ENV_URL.

## Run it

```sh
python3 main.py   # with MAKEFUN_ENV_URL set to a tiny-chess env server
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=heyyw288&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
