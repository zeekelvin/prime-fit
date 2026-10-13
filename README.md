# Prime Fit — Workout App

A personal workout and healthy-living web app. Everything runs from a single
static `index.html` — no server or database required.

## What's inside

- **Today** — streak, adaptive featured workout, weight quick-log, best meal by goal
- **Train** — 4 workout plans (HIIT, strength, quick fits, mobility) + instructor
  videos and custom workout logging
- **Back Care** — pain / flare / sciatica tracker, phased back-safe plan
  (McGill Big 3, glute work, incline walking), safe exercises, moves to avoid,
  flare-day protocol
- **Meals** — meals organized by goal area (lose weight, build muscle, heart
  health, energy & endurance, recovery & gut), weekly planner
- **Progress** — weight and pain charts, health logging, workout history
- **Reminders** — workout, weigh-in, meal-prep, water, sleep reminders
- **You** — local profile sign-in that personalizes the dashboard, plus
  JSON export/import for backups

## Data

All data is stored in the browser's `localStorage` — each device keeps its own
data. Use the You tab's export/import to back up or move data between devices.

## Deploy

This is a static site. Deploy the repo as-is on Vercel (or any static host);
`index.html` is the entry point.
