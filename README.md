# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/nemesis231002/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/nemesis231002/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python — alpha-beta search with piece-square
tables on a 0x88 board, playing through the make.fun env server.
Written for make.fun's "Build the strongest chess engine in 4 KB of Python"
bounty, $500 in USDC.

Practice trial 0: Elo 1451 (3 wins, 2 draws, 1 loss) — above the sunfish
baseline (~1365).

## Run it

```sh
python3 main.py
```

`main.py` is the packed entrypoint (a makefun-compress/v1 stub around an LZMA
stream of the readable source). It talks to the env server at
`$MAKEFUN_ENV_URL` and plays 8 games against the house gauntlet.

---

<sub>Entered on [make.fun](https://make.fun/?ref=amber-pika-68&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
