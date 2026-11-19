# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/saikatmondal15356-hash/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/saikatmondal15356-hash/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python: 0x88 board, tapered PeSTO evaluation with incremental scores, Zobrist hashing, transposition table, killer moves, PVS with late-move reductions, null-move pruning, and quiescence search over a fixed 50,000-node budget per move. `main.py` is the entrypoint, packed from the readable `engine.py` with `makefun compress`. No model calls, no clock: every move searches the same fixed node count, so play is fully deterministic.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18080 NODES=50000 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=ddm5nwx4&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
