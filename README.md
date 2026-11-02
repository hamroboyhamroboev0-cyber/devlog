# DevLog — Personal Developer Journal

A local-first personal journal for developers. Track what you learn, the errors you fix, the code you save, and the goals you're chasing.

## Features
- Dashboard with computed stats, activity heatmap, weekly hours and technology distribution
- Learning Journal with search, filter, sort, difficulty and time tracking
- Error Tracker with resolution status, statistics and search
- Code Snippet Manager with copy-to-clipboard
- Review Center with simple scheduling (1/3/7/30 days)
- Goals with automatic progress from journal entries
- Dark/light theme, fully responsive
- JSON export and import (validated)
- Sample data loader

## Stack
React 18 · Vite · React Router 6 · Lucide React · Recharts · plain CSS · localStorage

## Run locally
npm install
npm run dev
Open http://localhost:5173

## Data
All data is stored in localStorage under the key devlog:v1. Nothing leaves your browser. Use Settings to export/import JSON.

## Limitations
- Data is local to one browser only
- No authentication or cloud sync
- Review scheduling uses simple fixed intervals, not full spaced repetition

## License
MIT