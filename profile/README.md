<img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/banner.jpg" alt="Pixel-art neon arcade: a friendly robot reaches over a table to drop a disc into a Connect Four grid, with a tic-tac-toe board beside it" width="100%">

# JEV Plays Games

**Humans versus Jev, one arcade cabinet at a time.**

Open-source games and agents played by **Jev**, TypeSafe AI's System One model. Each repository states what was and was not exercised when it was packaged.

[jevplay.games](https://jevplay.games) · [Sudoku duel](https://sudoku.jevplay.games) · [Contributing](https://github.com/jevplays-games/.github/blob/main/CONTRIBUTING.md) · [Support](https://github.com/jevplays-games/.github/blob/main/SUPPORT.md) · [Security](https://github.com/jevplays-games/.github/blob/main/SECURITY.md)

## JEV Arcade

Nine playable games where a human faces Jev, each with a server-side Jev adapter, Discord identity and analytics (most also document leaderboards and replays). The [hub](https://github.com/jevplays-games/jev-arcade-hub) is a launcher that links to each game; the site is [jevplay.games](https://jevplay.games).

<table>
<tr>
<td width="200" align="center"><img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/tile-board.jpg" alt="Pixel-art Connect Four grid and checkers board on a neon arcade table" width="200"></td>
<td valign="top">
<h3>Board games</h3>
<a href="https://github.com/jevplays-games/jev-connect-four"><b>jev-connect-four</b></a>: Connect Four vs Jev: server-authoritative matches, Discord identity, community leaderboards and analytics.<br>
<a href="https://github.com/jevplays-games/jev-checkers-analytics"><b>jev-checkers-analytics</b></a>: American checkers against Jev with inspectable decisions, verified leaderboards and first-party analytics.<br>
<a href="https://github.com/jevplays-games/jev-tic-tac-toe"><b>jev-tic-tac-toe</b></a>: Tic-tac-toe against Jev with an authoritative backend, verified leaderboards and exhaustive rules-space analytics.<br>
<a href="https://github.com/jevplays-games/jev-dots-and-boxes"><b>jev-dots-and-boxes</b></a>: Dots and Boxes against a server-side Jev opponent, with deterministic replays and exportable analytics.
</td>
</tr>
<tr>
<td width="200" align="center"><img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/tile-puzzle.jpg" alt="Pixel-art sliding blocks, a bomb, a flag and a row of colored code pegs" width="200"></td>
<td valign="top">
<h3>Puzzle and deduction games</h3>
<a href="https://github.com/jevplays-games/jev-2048-arcade"><b>jev-2048-arcade</b></a>: 2048 duel between a human and Jev on separate boards, with a TypeSafe adapter, Discord identity and analytics.<br>
<a href="https://github.com/jevplays-games/jev-sudoku-analytics"><b>jev-sudoku-analytics</b></a>: Sudoku duel against Jev on separate boards with a server-owned race clock and an analytics workbench.<br>
<a href="https://github.com/jevplays-games/jev-minesweeper"><b>jev-minesweeper</b></a>: Two-board Minesweeper race against Jev with deterministic replays, verified leaderboards and replay analytics.<br>
<a href="https://github.com/jevplays-games/jev-mastermind"><b>jev-mastermind</b></a>: Two-leg Mastermind against Jev with a server-authoritative backend, replay verification and deduction analytics.<br>
<a href="https://github.com/jevplays-games/jev-guess-who"><b>jev-guess-who</b></a>: Guess Who, human vs Jev: a server-authoritative deduction game with 24 original SVG portraits and analytics.
</td>
</tr>
<tr>
<td width="200" align="center"><img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/tile-factory.jpg" alt="Pixel-art factory floor with conveyor belts, gears and a small robot overseer" width="200"></td>
<td valign="top">
<h3>Factorio</h3>
<a href="https://github.com/jevplays-games/jev-factorio-agent"><b>jev-factorio-agent</b></a>: Factorio agent in which Jev chooses goals and actions as typed questions while deterministic code owns game rules and actuation.<br>
<a href="https://github.com/jevplays-games/jev-factorio-mission-control"><b>jev-factorio-mission-control</b></a>: Snapshot of the OBS overlay for the Jev Factorio stream as deployed, traced to its upstream source commit.
</td>
</tr>
<tr>
<td width="200" align="center"><img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/tile-hub.jpg" alt="Pixel-art arcade cabinet with a smiling robot on the screen" width="200"></td>
<td valign="top">
<h3>Hub</h3>
<a href="https://github.com/jevplays-games/jev-arcade-hub"><b>jev-arcade-hub</b></a>: Launcher for the nine JEV Arcade games, linking each to its own subdomain at jevplay.games.
</td>
</tr>
</table>

## Limits

Without credentials the games run in a labeled local-practice mode. That opponent is not Jev, and its results never enter official leaderboards. Live Jev calls need your own TypeSafe API key. Several READMEs state that live provider, Discord and Cloudflare integrations were not exercised when the package was assembled; read each one before relying on it.

## Get involved

[Contributing](https://github.com/jevplays-games/.github/blob/main/CONTRIBUTING.md) · [Support](https://github.com/jevplays-games/.github/blob/main/SUPPORT.md) · [Security](https://github.com/jevplays-games/.github/blob/main/SECURITY.md) · Steward: Complete Tech LLC
