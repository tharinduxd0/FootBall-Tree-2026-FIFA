# World Cup 2026 Tracker

A lightweight single-page HTML tracker for the 2026 FIFA World Cup group stage and knockout bracket.

## Features

- Group stage standings and round-robin match inputs
- Automatic group progress and knockout bracket preview
- Live analysis summary with leading teams, struggling teams, and performance metrics
- Team search and matchup filters
- Local state persistence for results
- Live score entry with goals for / against and clean sheet tracking
- Group sorting by tiebreakers: points, goal difference, goals scored, head-to-head
- Export standings to CSV and import/export fixtures via JSON
- Reset all or reset individual group results

## How to use

1. Open `world-cup-2026-tracker.html` in a browser.
2. Use the group stage fixtures to record wins, draws, and losses.
3. The summary cards at the top update automatically.
4. When all groups are complete, the knockout bracket becomes active.

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