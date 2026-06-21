# World Cup 2026 Tracker

A lightweight single-page HTML tracker for the 2026 FIFA World Cup group stage and knockout bracket.

## Features

- Group stage standings and round-robin match inputs
- Automatic group progress and knockout bracket preview
- Live analysis summary with leading teams, struggling teams, and performance metrics
- Team search and matchup filters
- Live score entry with goals for / against and clean sheet tracking
- Group sorting by tiebreakers: points, goal difference, goals scored, head-to-head
- Reset all or reset individual group results
- Loads match data from repository JSON file

## How to use

1. Open `world-cup-2026-tracker.html` in a browser.
2. Use the group stage fixtures to record wins, draws, and losses.
3. The summary cards at the top update automatically.
4. When all groups are complete, the knockout bracket becomes active.

## Data

- The application loads match data from the repository's `data/repo-state.json` file.

## Shared repo data

- The site now loads its public match state from `data/repo-state.json`.
- Update that JSON file in the repository when you want everyone to see new results.
- Visitors can view the page and local changes in their browser, but only repo updates are shared.
## Live Demo

- https://tharinduxd0.github.io/FootBall-Tree-2026-FIFA/

## Tech

- Plain HTML, CSS, and JavaScript
- Uses browser `localStorage` for state persistence
- Fetches country metadata for flags when available

## Screenshots

![Tracker view 1](https://i.postimg.cc/NM39w4zY/image.png)

![Tracker view 2](https://i.postimg.cc/MK8MP9BZ/image.png)

## Credit

Created by `tharinduxd`.