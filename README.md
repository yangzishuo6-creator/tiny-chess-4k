# Tiny Chess 4K

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![Rank](https://make.fun/badge/tiny-chess-01/yangzishuo6-creator/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![Reward](https://make.fun/badge/tiny-chess-01/yangzishuo6-creator/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01)

`main.py` plays the make.fun gauntlet with deterministic principal variation search, a persistent transposition table, and tapered evaluation that rewards passed pawns and helps convert endgame leads. Run it with Python 3.13 and `MAKEFUN_ENV_URL` set to the gauntlet server. The search uses up to 230,000 nodes per move, with a lower cap when there are many legal moves or the trial nears 65 million search nodes.
