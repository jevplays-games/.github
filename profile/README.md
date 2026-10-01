# JEV Plays Games

Open-source games and agents played by **Jev**, TypeSafe AI's System One model. Each repository states what was and was not exercised when it was packaged.

## JEV Arcade

Nine playable games where a human faces Jev, each with a server-side Jev adapter, Discord identity and analytics (most also document leaderboards and replays):

[2048](https://github.com/jevplays-games/jev-2048-arcade) · [Checkers](https://github.com/jevplays-games/jev-checkers-analytics) · [Connect Four](https://github.com/jevplays-games/jev-connect-four) · [Dots and Boxes](https://github.com/jevplays-games/jev-dots-and-boxes) · [Guess Who](https://github.com/jevplays-games/jev-guess-who) · [Mastermind](https://github.com/jevplays-games/jev-mastermind) · [Minesweeper](https://github.com/jevplays-games/jev-minesweeper) · [Sudoku](https://github.com/jevplays-games/jev-sudoku-analytics) · [Tic-Tac-Toe](https://github.com/jevplays-games/jev-tic-tac-toe)

The [hub](https://github.com/jevplays-games/jev-arcade-hub) is a launcher that links to each game; the site is [jevplay.games](https://jevplay.games).

## Factorio

- [jev-factorio-agent](https://github.com/jevplays-games/jev-factorio-agent): Jev makes goal and next-action decisions as typed questions; deterministic code owns game rules and actuation.
- [jev-factorio-mission-control](https://github.com/jevplays-games/jev-factorio-mission-control): a snapshot of the OBS overlay for the Factorio stream as deployed, traced to its source.

## Limits

Without credentials the games run in a labeled local-practice mode. That opponent is not Jev, and its results never enter official leaderboards. Live Jev calls need your own TypeSafe API key. Several READMEs state that live provider, Discord and Cloudflare integrations were not exercised when the package was assembled; read each one before relying on it.

## Get involved

[Contributing](CONTRIBUTING.md) · [Support](SUPPORT.md) · [Security](SECURITY.md) · Steward: Complete Tech LLC
