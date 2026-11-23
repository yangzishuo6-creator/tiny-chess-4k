# Tiny Chess 4K

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![Rank](https://make.fun/badge/tiny-chess-01/yangzishuo6-creator/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![Reward](https://make.fun/badge/tiny-chess-01/yangzishuo6-creator/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01)

`main.py` plays the make.fun gauntlet with deterministic principal variation search, tapered evaluation, and a bounded transposition table with aged move history reused across each game. Run it with Python 3.13 and `MAKEFUN_ENV_URL` set to the gauntlet server. The search uses up to 230,000 nodes per move and reduces that budget after 65 million nodes in a trial.
