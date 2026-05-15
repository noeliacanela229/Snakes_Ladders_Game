# Snake and Ladder Game

A two-player Snake and Ladder game built in C that runs in the terminal. Players take turns rolling a die, and the board updates after every move to show both player positions in real time.

## How it works

- Two players take turns pressing Enter to roll a six-sided die
- The board is printed to the terminal after each move, showing both players' positions (`#P1`, `#P2`)
- Landing on a ladder moves you forward; landing on a snake sends you back
- First player to reach square 100 wins

## Snakes and Ladders on the board

| Square | Effect |
|--------|--------|
| 6      | +40 (ladder) |
| 77     | +5 (ladder)  |
| 23     | -10 (snake)  |
| 45     | -7 (snake)   |
| 61     | -18 (snake)  |
| 65     | -8 (snake)   |
| 98     | -10 (snake)  |

## How to run

You'll need a C compiler like `gcc` installed.

```bash
gcc snakes.c -o snakes
./snakes
```

## Built with

- C
- Standard libraries: `stdio.h`, `stdlib.h`, `time.h`
