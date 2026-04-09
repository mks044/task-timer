# Task Timer

A minimal, browser-based task timer for tracking focused work sessions. No accounts, no servers — everything runs locally in your browser using localStorage.

## Features

- **Pomodoro-style time tracking** — set a time allocation per task and track how long you actually spend
- **Scheduled / Backlog / Completed** — organize tasks into three sections
- **Drag and drop** — reorder scheduled tasks by priority
- **Inline editing** — click any task name or time to edit it directly
- **Break tasks** — schedule breaks between work sessions
- **Notes** — attach notes to any task
- **Overtime alerts** — timer turns red when you exceed the allocated time
- **Tab title updates** — see your running timer without switching tabs
- **Dark theme** — easy on the eyes for long sessions

## How to Use

1. **Open `index.html` in your browser** — that's it, no build step or install needed
2. **Add a task** — type a name, pick a time (or enter custom minutes), and click Add
3. **Start the timer** — hit Start on any scheduled task to begin tracking
4. **Pause / Complete / Stop** — use the controls in the timer banner
5. **Reorder** — drag tasks up or down to change your schedule
6. **Edit** — click a task name or time badge to change it inline
7. **Track progress** — the header shows total time worked and tasks completed today

All data is stored in your browser's localStorage. Clearing browser data will reset your tasks.
