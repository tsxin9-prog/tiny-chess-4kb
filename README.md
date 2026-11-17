# tiny-chess-4kb

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tsxin9-prog/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tsxin9-prog/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A 4 KB Python chess engine for [tiny-chess-01](https://make.fun/bounty/tiny-chess-01). `main.py` is an lzma-packed 0x88 searcher: tapered piece-square evaluation, principal variation search with iterative deepening, a transposition table, null-move pruning, late-move reductions, killers and quiescence. It plays a fixed node budget, so the same position always gets the same move.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```
