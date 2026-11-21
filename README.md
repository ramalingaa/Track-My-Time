# Track My Time

A time tracker for multiple projects. Add projects and tap one to start its clock. Several clocks can run at the same time, and each keeps going until you press its **Stop** button.

## Features

- **Multiple timers.** Starting one project doesn't stop the others. Each running project has its own Stop button, and **Stop all** pauses everything at once.
- **Totals.** Each project shows its total time, plus the current session's time while it runs. The grand total and how many clocks are running are shown at the top. When clocks overlap, the grand total counts each project's time separately.
- **Entries.** Every session is logged with its start time, end time and length.
- **Adjust time.** Add or subtract hours and minutes by hand, e.g. 1 min tracked + 10 min added = 11 min. Quick buttons (+5m, +10m, +15m, +30m, +1h, −5m) are included, and every adjustment is logged as a manual entry.
- **Notes.** Each project has a free-form, to-do style list with as many notes as you like. Notes can be ticked off, edited and deleted.
- **Shortcuts.** Keys `1`–`9` start or stop a project, `Space` stops all, and `Ctrl/⌘ + Enter` adds a note.
- **Light and dark mode.** It follows your system setting.

## Storage

Everything is saved in your browser's `localStorage`, so there's no backend and no sign-in. Data stays on the device and browser you use, and clearing your browser data erases it.

## Run / deploy

It's a single static `index.html` with no build step.

- **Locally:** open `index.html` in a browser.
- **Vercel:** import this repo with framework preset "Other" and no build command, or run `npx vercel --prod` in this folder.
