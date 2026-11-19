# tiny-chess-4k

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/leminhtri1/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/leminhtri1/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A deterministic chess engine in 4 KB of Python for make.fun's
[tiny-chess-01](https://make.fun/bounty/tiny-chess-01) bounty.

`main.py` is `src.py` packed by `makefun compress`. It uses a 10x12 mailbox
board, a tapered piece-square evaluation, and alpha-beta search (PVS,
quiescence, transposition table, null move, LMR) under a fixed node budget,
with no clock. MIT licensed.
