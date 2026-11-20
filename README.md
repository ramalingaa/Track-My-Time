# Track My Time

A chess-clock style time tracker for multiple projects. Add projects, tap one to start its clock, and tapping another switches over. Only one clock runs at a time.

## Features

- **One clock at a time.** Starting a project pauses whichever one was running.
- **Totals.** Each project shows its total time, plus the current session's time while it runs. The grand total is at the top.
- **Entries.** Every session is logged with its start time, end time and length.
- **Notes.** Each project has a free-form, to-do style list with as many notes as you like. Notes can be ticked off, edited and deleted.
- **Shortcuts.** Keys `1`–`9` switch projects, `Space` pauses, and `Ctrl/⌘ + Enter` adds a note.
- **Light and dark mode.** It follows your system setting.

## Storage

Everything is saved in your browser's `localStorage`, so there's no backend and no sign-in. Data stays on the device and browser you use, and clearing your browser data erases it.

## Run / deploy

It's a single static `index.html` with no build step.

- **Locally:** open `index.html` in a browser.
- **Vercel:** import this repo with framework preset "Other" and no build command, or run `npx vercel --prod` in this folder.
