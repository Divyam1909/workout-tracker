# LiftLog — Workout Tracker

A single-page workout tracker for logging strength training sessions: exercises, sets, reps, and weight, with rest timers, progressive-overload suggestions, and PR tracking.

## Features

- Start a workout from scratch or from a saved template, with sets pre-filled from your last session
- Rest timer, drag-to-reorder exercises, warm-up/drop-set tagging
- Automatic PR (personal record) detection via estimated 1-rep max
- Dashboard with volume and bodyweight charts (Chart.js)
- Full workout history with one-tap "Repeat" to redo a past session
- kg/lb unit conversion, light/dark/system theme
- JSON export/import for backups — all data is stored locally in the browser (`localStorage`)

## Tech

Plain HTML/CSS/JS — no build step. Styled with the Tailwind CDN, icons from Phosphor, charts from Chart.js.

## Running locally

Just open `index.html` in a browser, or serve the folder with any static file server.

## Deployment

Deploys as a static site on Vercel with zero configuration — `index.html` is the entry point.

## Data & backups

All workout data lives in your browser's `localStorage`, so it's local to one browser/device. Use **Settings → Export JSON** periodically to back up your data, and **Import Data** to restore it (e.g. after clearing browser storage or switching devices).
