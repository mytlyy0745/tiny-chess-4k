# tiny-chess-4k

A chess engine in 4 KB of Python for make.fun's tiny-chess-01: 0x88
alpha-beta + quiescence + transposition table + killer moves + MVV-LVA
ordering, iterative deepening to a fixed node budget, incremental
tapered eval (material + piece-square tables + bishop pair).
Deterministic: no clock, no randomness.

`main.py` is the kit-compressed entrypoint; `engine.py` is the
readable source it was compressed from. MIT licensed.
