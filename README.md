# متتبع الوزن — Weight Tracker

A lightweight, offline-first Arabic **Progressive Web App (PWA)** for tracking daily weight, BMI, and calorie intake — with a detailed Excel report export.

## Features

- 📈 Daily weight logging with trend chart, streaks, and goal progress
- ⚖️ BMI calculation, health category, and healthy-weight range
- 🔥 Calorie intake tracking with auto-calculated targets (BMR/TDEE, Mifflin–St Jeor)
- 📊 One-click **Excel report** covering your full profile, weight history, health metrics, energy targets, and per-meal calorie log
- 💾 JSON backup / restore
- 📴 Works fully offline and installs to the home screen (service worker + manifest)

## Tech

Pure static front-end — a single `index.html` (HTML/CSS/vanilla JS) plus a service worker. No build step, no dependencies. Data is stored locally in the browser (`localStorage`).

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Hosted as a static site on **Vercel**. Any push to the default branch triggers an automatic deployment.
