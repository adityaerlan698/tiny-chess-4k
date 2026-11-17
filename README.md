# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/adityaerlan698/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/adityaerlan698/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 120,000-node alpha-beta chess engine in 4,079 bytes of Python 3.13 stdlib. Transposition table, null-move pruning, LMR, futility pruning, quiescence, king-safety pawn shield, rook open-file bonus, bishop-pair bonus. No model calls, fully deterministic. Practice Elo 1,858 mean over 3 trials (2,112 / 1,809 / 1,654; 15 wins, 3 draws, 0 losses) vs the house baseline sunfish at 1,365.

## Run it

```sh
python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=6vzrd6ez&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
