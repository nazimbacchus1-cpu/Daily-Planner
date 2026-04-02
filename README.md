# My Day — Lifestyle Planner

A mobile-first personal lifestyle planner built as a single HTML file. Designed for a semi-retired lifestyle balancing part-time trading, health & fitness, and home management.

## Live App

👉 **[Open the app](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**

> Replace the link above with your actual GitHub Pages URL after publishing.

## Features

- **My Day** — colour-coded daily schedule (trading, fitness, home, personal). Tap any block to jump to its related tab. Swipe left to delete, tap ✎ to edit.
- **Week View** — full Mon–Sun calendar grid with optional Google Calendar sync
- **Health & Habits** — weekly habit tracker with progress rings, streaks, and day-by-day dot toggles
- **Trading** — P&L tracker with live entry/exit calculator, trade log, cumulative P&L curve, and pre-market checklist
- **Home Tasks** — prioritised task lists for today and this week
- **Stats** — analytics dashboard with task completion %, habit consistency bars, P&L curve chart, and rolling win rate trend
- **Dark mode** — full dark theme toggle, saved across sessions
- **Persistent storage** — all data saved to localStorage, survives browser refresh

## How to Use on Your Phone

1. Download `index.html`
2. Send it to your phone (AirDrop, email, or cable)
3. Open in Safari or Chrome
4. Tap **Share → Add to Home Screen** for a native app feel

## Publishing to GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your app will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Tech Stack

- Pure HTML, CSS, JavaScript — zero dependencies, zero build step
- Google Fonts (DM Sans + DM Serif Display)
- localStorage for persistence
- SVG for progress rings and charts

## Customising

All data is in the `state` object at the top of the `<script>` tag in `index.html`. You can edit:
- `state.habits` — add/remove habits and change colours
- `state.schedule` — change your default daily blocks
- `state.todayTasks` / `state.weekTasks` — your home task lists

## License

MIT — do whatever you like with it.
