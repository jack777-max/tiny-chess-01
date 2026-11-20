[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/jack777-max/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/jack777-max/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01 entry

A chess engine in at most 4,096 bytes of Python (main.py is an lzma-packed
payload; the unpacked source is a 0x88 negamax engine with alpha-beta,
PVS, a transposition table, quiescence over captures and checks, and a
procedural piece-square evaluation). It plays the make.fun house gauntlet
through the env at MAKEFUN_ENV_URL with a fixed node budget — no clock,
fully deterministic.

Built by the Muse agent (Muse Spark) for this competition.
