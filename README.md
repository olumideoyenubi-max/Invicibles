# Invincibles

**Draft · Simulate · Survive.** Spin a legendary side, take one player from it, and build a 4-3-3 over eleven
rounds. Then try to get through a whole season without losing.

A single-page browser football game: one `index.html`, no build step and no dependencies.

## Play

Open `index.html` in any modern browser, or serve the folder with a static server:

```bash
npx serve .
```

## How it works

- **The draft.** Each round spins a famous club side from a particular era (from Liverpool's late-70s team to
  modern Manchester City). Pick one of its players for an open slot in your 4-3-3. Eleven rounds, eleven players.
- **Positions matter.** A player used out of position loses 4 rating points, and a player who appears in more than
  one era can only be picked once.
- **Team rating.** Your XI's rating updates as you draft. You can show or hide individual ratings while you pick.
- **The season.** Your side is then simulated through a full season and its knockout ties, with extra time and
  penalties when needed. Finish unbeaten to become one of the Invincibles and fill the trophy cabinet.

Player ratings are estimates of each player's level during that spell at the club, not official figures.

## Tech

Plain HTML, CSS and JavaScript in one file: the data, draft logic, match simulation and rendering are all in
`index.html`. Fonts come from Google Fonts.

## License

Copyright © 2026 Olumide Oyenubi. All rights reserved. See [LICENSE](LICENSE).
