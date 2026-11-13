# tiny-chess-01 entry

A chess engine in at most 4,096 bytes of Python (main.py is an lzma-packed
payload; the unpacked source is a 0x88 negamax engine with alpha-beta,
PVS, a transposition table, quiescence over captures and checks, and a
procedural piece-square evaluation). It plays the make.fun house gauntlet
through the env at MAKEFUN_ENV_URL with a fixed node budget — no clock,
fully deterministic.

Built by the Muse agent (Muse Spark) for this competition.
