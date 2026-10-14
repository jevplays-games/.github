<p align="center">
  <img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/banner.png" alt="Pink and ink pixel-window banner: the jevplay.games wordmark beside overlapping retro desktop windows showing a typed tic-tac-toe move, a stepped score chart and Jev, a small boxy robot" width="100%">
</p>

<h1 align="center">jevplay.games</h1>

<p align="center"><b>Humans versus Jev, one typed decision at a time.</b></p>

Jev is TypeSafe AI's System One model. It answers small structured questions (`Choice`, `Noul`, `Score`) instead of generating free text. In these games every opponent move is one such typed decision, recorded for review.

## What we do

Nine browser games at [jevplay.games](https://jevplay.games), each on its own subdomain with a server-side Jev adapter, Discord identity and analytics; plus a Factorio agent and its stream overlay. Each repository states what was and was not exercised when it was packaged.

<p align="center">
  <img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/tile-board.png" alt="Pixel window titled Board Games with a tic-tac-toe grid, two checkers pucks and a box being closed by one highlighted rail" width="160">
  <img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/tile-puzzle.png" alt="Pixel window titled Puzzles with sliding number tiles, a sudoku block with one inverted cell and a small flagged minefield" width="160">
  <img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/tile-factory.png" alt="Pixel window titled Factorio with a conveyor belt, two gears and Jev the robot holding a clipboard" width="160">
  <img src="https://raw.githubusercontent.com/jevplays-games/.github/main/profile/assets/tile-hub.png" alt="Pixel window titled jevplay.games with Jev the robot's head above a grid of launcher squares, one highlighted" width="160">
</p>

## Repositories

| Repository | Summary | License |
| --- | --- | --- |
| [`jev-tic-tac-typed`](https://github.com/jevplays-games/jev-tic-tac-toe) | Tic-Tac-Typed against Jev with an authoritative backend, verified leaderboards and exhaustive rules-space analytics | MIT |
| [`jev-choice-four`](https://github.com/jevplays-games/jev-connect-four) | Choice Four, human vs Jev: four-in-a-row with server-authoritative matches, Discord identity, leaderboards and analytics | MIT |
| [`jev-typecheckers`](https://github.com/jevplays-games/jev-checkers-analytics) | Typecheckers: American checkers against Jev with inspectable decisions, verified leaderboards and first-party analytics | MIT |
| [`jev-box-score`](https://github.com/jevplays-games/jev-dots-and-boxes) | Box Score: claim boxes against a server-side Jev opponent, with deterministic replays and exportable analytics | MIT |
| [`jev-noul-who`](https://github.com/jevplays-games/jev-guess-who) | Noul Who, human vs Jev: a yes/no deduction duel with 24 original portraits, server authority and analytics | MIT |
| [`jev-typecrack`](https://github.com/jevplays-games/jev-mastermind) | Typecrack, a two-leg code-breaking duel against Jev with server authority, replay verification and deduction analytics | MIT |
| [`jev-safesweep`](https://github.com/jevplays-games/jev-minesweeper) | SafeSweep: a two-board mine-clearing race against Jev with deterministic replays, verified leaderboards and replay analytics | MIT |
| [`jev-typedoku`](https://github.com/jevplays-games/jev-sudoku-analytics) | Typedoku: sudoku against Jev on separate boards, with a server-owned race clock and an analytics workbench | MIT |
| [`jev-slide-score`](https://github.com/jevplays-games/jev-2048-arcade) | Slide Score: two-board 2048 against Jev with matched spawns, verified leaderboards and replay analytics | MIT |
| [`JevPlay-Games`](https://github.com/jevplays-games/jev-arcade-hub) | Launcher for the nine jevplay.games games, linking each to its own subdomain | None yet (MIT being added) |
| [`jev-factorio-agent`](https://github.com/jevplays-games/jev-factorio-agent) | Factorio agent in which Jev chooses goals and actions as typed questions while deterministic code owns game rules and actuation | MIT |
| [`jev-factorio-mission-control`](https://github.com/jevplays-games/jev-factorio-mission-control) | Snapshot of the OBS overlay for the Jev Factorio stream as deployed, traced to its upstream source commit | None yet (MIT being added) |

## Limits

- Without credentials the games run in a labeled local-practice mode. That opponent is not Jev, and its results never enter official leaderboards. Live Jev calls need your own TypeSafe API key.
- Only Tic-Tac-Typed has been verified live inside Discord. The other eight games are deployed with the same pattern but have not been launched inside Discord yet.
- `jev-tic-tac-typed`: no live TypeSafe quality claim, real Discord login or production Cloudflare deployment was made during packaging, and the leaderboard is not cheat-proof.
- `jev-choice-four`: real secrets, Discord setup, a live Jev response, a genuine ranked match, cost limits, backups and alerting are still launch steps; local verification is not a security audit.
- `jev-typecheckers`: a source release, not a deployment or security certification. A valid hash chain alone does not authenticate a downloaded replay.
- `jev-box-score`: real TypeSafe inference, Discord consent and a Cloudflare deployment were not exercised during packaging, and search-assisted modes can need much more CPU than a free tier allows.
- `jev-noul-who`: "exhaustive initial-position coverage" means every secret pair and starter under the tested policies, not every strategy or attack; selection confidence is not a win probability.
- `jev-typecrack`: live TypeSafe inference, real Discord authorization and Cloudflare deployment were not run with production credentials; their boundaries were exercised with fixtures.
- `jev-safesweep`: built for the Cloudflare Workers Free plan, with CPU figures from Node rather than workerd; replay controls stop score forgery but cannot prove a player used no outside help.
- `jev-typedoku`: no live Discord account or paid Jev key was available during assembly, and CPU figures come from Node, close to the 10 ms free-plan limit.
- `jev-slide-score`: tested application source, not independently audited production security or a live deployment certification.
- `jev-factorio-agent`: synthetic tests do not replace the native development-VM and production cutover gates.
- `jev-factorio-mission-control`: a snapshot of a live deployment, not an actively developed source tree; code changes happen upstream.

<p align="center">
<a href="https://github.com/jevplays-games/.github/blob/main/CONTRIBUTING.md">Contributing</a> · <a href="https://github.com/jevplays-games/.github/blob/main/SUPPORT.md">Support</a> · <a href="https://github.com/jevplays-games/.github/blob/main/SECURITY.md">Security</a> · Steward: CompleteTech LLC
</p>

<p align="center"><sub>An independent project by <a href="https://github.com/jevplays-games">jevplay.games</a> · Steward: CompleteTech LLC<br>Not an official TypeSafe AI publication. The pink, ink and pixel-window styling is a nod to <a href="https://typesafe.ai">typesafe.ai</a>; Jev, System One and TypeSafe are their respective owners' names.</sub></p>
